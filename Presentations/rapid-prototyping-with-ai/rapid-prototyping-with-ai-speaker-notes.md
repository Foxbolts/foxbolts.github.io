# Rapid prototyping with AI — speaker notes

## 1. Rapid prototyping with AI
- Target: 0:20


## 2. Test more ideas. Get feedback sooner.
- Target: 0:55
- Rapid prototyping means building a quick, limited version of an idea so we can test it, get feedback, and decide whether to improve it or move on.
- As you can see, we have plenty of ideas. The question is which ideas hold value?
- Rapid prototyping itself isn’t new. So what has changed?

## 3. A first pass can start small
- Target: 0:10
- We now have capable AI models that can help us build a first pass in the actual project at a speed and cost that make more experiments practical.
- Before we look at a real example, let’s agree on what to expect from the code they produce.

## 4. AI may not code as good as you (yet)
- Target: 0:55
- It's like looking at someone else's code and saying “I wouldn’t have written it that way." Some of that reaction is about seeing choices you may not agree with, and some of it might actually be just crappy code.
- But a prototype doesn’t need polished code to answer its first question. AI may miss conventions or make poor tradeoffs, but it can produce a working first pass quickly.
- Let’s set aside our preferred implementation long enough to try the idea. If the code is worth keeping, we still review it, improve it, and test it.
- With that expectation set, where do we start?

## 5. Just use the chat box.
- Target: 1:05
- I really like Alex’s work on the address-bar close-tab gesture. Let’s see how quickly we can improve it.
- Start with the chat box in the project and describe the behavior you want. This prompt asks for left and right drag actions with visible hints in the existing app.
- Skills, MCP, and more elaborate workflows can help later. We don’t need them to make this first request.
- Now let’s see what the first pass produced.

## 6. Address bar gesture prototype
- Target: 0:20
- Well there you have it.
- The screenshot shows the request and implementation summary; the recording shows the gesture running in the app
- This first pass took 3 minutes and 19 seconds
- So, what happens if we give a more detailed refinement request?

## 7. Refined address bar gesture
- Target: 0:20
- Here is a more detailed request, with a stronger result
- The request was more specific: Add labels, animate the close and bookmark zones, return them on drag
- The point is the iteration: try a working version, notice what feels wrong, and describe the next change.
- This took 3 minutes and 32 seconds.
- A few tool choices can make that loop easier. Let’s look at those next.

## 8. Tips & tricks
- Target: 1:30
- Although I think this is currently disabled for our organization, when available, use fast mode to speed up development
- Start at the baseline models (Opus 5.5, GPT 6.1 Sol) and lower reasoning efforts (medium, high), and bump up to larger models (Astra and Fable)0 and higher reasoning effort (xhigh, max) when the task is ambiguous, complex, or the current model/reasoning effort just isn't getting it
- Give the agent visual context: share screenshots or recordings, and say exactly what should change.
- Ask it to show you the result (screenshots, recordings), too, using Simulator or iPhone Mirroring when available. Review what actually appears in the app.

## 9. The baseline has changed.
- Target: 1:10
- Models have improved substantially. A disappointing experience from months ago may not predict what one can do for you today.
- You don’t need to follow every launch. Try a current tool on one real task and judge the result yourself.

## 10. Your turn. Let’s build.
- Target: 0:50
