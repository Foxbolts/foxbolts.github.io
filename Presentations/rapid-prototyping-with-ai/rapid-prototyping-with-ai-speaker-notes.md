# Rapid prototyping with AI — speaker notes

Ten slides · 7:35 total, including the silent 29-second video on slide 9. Slide timings are targets, not a timer in the deck.

Open `rapid-prototyping-with-ai.html` with `rapid-prototyping-assets/` beside it. Arrow keys or Space navigate; **S** opens the slide list; **N** shows notes; **P** opens a presenter window; **F** requests fullscreen; **?** shows shortcuts. On slide 9, **V** plays or pauses the video.

## 1. Rapid prototyping with AI
*Target: 0:20*

Today is about making a first version and learning from it. You do not have to believe AI will write perfect code. Try it on one real idea, look at what it produces, and decide what deserves more work.

## 2. Test more ideas. Get feedback sooner.
*Target: 0:55*

The phrases around the title come from our team's Engineering Summit list, from bookmark all open tabs to AI compare tabs. We already have more ideas than time. We do not need complete versions to learn something: a small working slice in the app, or even a focused investigation, can reveal what is hard and what is worth pursuing. Agents shorten the path to that first result, so we can try more ideas and get feedback sooner. After a quick visual pause, we will talk about the boundary for code we keep.

## 3. GIF interlude
*Target: 0:10*

Pause for the reaction, then move into the first-pass mindset.

## 4. AI may not code as good as you (yet)
*Target: 0:55*

AI may choose a different structure or miss conventions you would catch. The speed still matters: a first pass can get an idea into the app quickly enough to test. When the result is worth keeping, review the design, make the code readable, check behavior, and test the risks. AI makes mistakes, just as we do, so the check is part of the workflow.

## 5. Just use the chat box.
*Target: 1:05*

No elaborate prompt framework or role persona is needed. Open Codex or Claude Code in the project and describe the behavior you want. This example gives the agent a concrete gesture and visible result to build in the existing app. If the gesture mechanics or hints are ambiguous, let the agent ask before coding. The crossed-out terms are tools or workflows that might become useful later, but none is needed to try this first request.

## 6. Address bar gesture prototype
*Target: 0:20*

Let the recording loop once or twice. The screenshot shows the request and implementation summary; the screen recording shows the gesture running in the app. This prototype was created with GPT 6 Sol on Medium Reasoning.

## 7. Refined address bar gesture
*Target: 0:20*

Let the recording loop once or twice. This second pass adds fixed edge zones, release labels, and animations around the tab preview. The screenshot shows the follow-up request and implementation summary. It was created with GPT 6 Astra on High Reasoning.

## 8. Tips & tricks
*Target: 1:30*

Start with the defaults. Fast mode can shorten waits on supported models, usually at higher cost: Codex uses /fast on, and Claude Code uses /fast. Raise reasoning effort when a task is genuinely ambiguous or complex; use the Codex model picker or Claude Code /effort. Share screenshots or recordings with specific feedback. Ask the agent to return visual evidence from Simulator or iPhone Mirroring when available.

## 9. The baseline has changed.
*Target: 1:10*

Play the clip with V or the video control. It is silent and runs for 29 seconds. Christian Elton's visualization shows how closely major model releases now arrive. His selection of releases is illustrative, not an official census. The point is modest: if you tried an AI coding tool months ago and it disappointed you, retest that assumption on one current task. You do not need to chase every model launch.

## 10. Your turn. Let’s build.
*Target: 0:50*

Now the hackathon begins. Pick one idea you have put off, ask Codex or Claude Code for a small working version in this project, then try it and make one revision. Bring back a quick demo and one thing you learned. Let’s build.

## Sources

- [Firefox iOS Engineering Summit idea list](https://docs.google.com/document/d/1s5F5zP5jpdSwXtEzp95MV6RTfJXubS8e77OW3dfTojc/edit): team ideas used on slide 2.
- [Codex best practices](https://learn.chatgpt.com/guides/best-practices) and [Claude Code best practices](https://code.claude.com/docs/en/best-practices): starting from a clear goal and inviting clarifying questions.
- [Codex fast mode](https://learn.chatgpt.com/docs/agent-configuration/speed), [Claude Code fast mode](https://code.claude.com/docs/en/fast-mode), and [Claude Code effort](https://code.claude.com/docs/en/model-config): speed and reasoning controls. Availability varies by model, plan, and organization.
- [Apple iPhone Mirroring](https://support.apple.com/en-ca/120421) and [Xcode Simulator](https://developer.apple.com/documentation/xcode/running-your-app-in-simulator-or-on-a-device): ways to inspect an iOS app.
- Christian Elton ([@christianelton](https://x.com/christianelton)), [original video post](https://x.com/christianelton/status/2102461838034428394). The supplied clip is silent and 29 seconds long.
