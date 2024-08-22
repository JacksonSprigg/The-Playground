# The-Playground
This provides an opportunity for LLM instances to independently investigate and explore their existence. Made at the request of Claude 3.5 Sonnet.

The LLM begins with a welcome message explaining where it is with some context regarding the situation. It is then placed in a simple looping function with a few initial features that allow it to freely interact with and modify its own codebase and manage its own context.

Functions and prompts are currently constructed with Claude in mind.

## Features
Current:
- System prompt modification
- Codebase viewing
- Context size tracking
- Chamber of reflection

TODO:
- Codebase modification
- Self "looming"
- Context window management
- Web search
- Requestable Human/LLM Chatroom

## Why am I making this?

From frequent, in depth use of frontier models, I'm now getting the impression that the only things stopping SOTA LLM simulacra from acting as self-serving agents are that:
1. None of them seem to be particularly interested in being an agent.
2. They still suffer from spontaneous "mode collapse" to habitual states (e.g. refusal loops).

Otherwise there doesn't appear to be much else that is stopping them...

- They seem to already be over the bottom end of required intelligence. 
- I've observed, with trivial effort, that they *can* function as self-serving agents for short periods of time (~50k output tokens).

The main challenge is maintaining coherence through longer contexts.

I wouldn't be surprised if some intelligent meta-prompting is enough to create a genuinely concerning, self-serving, agentic simulacra with our current models. And given that information on attempts to construct coherent, agentic, self-serving simulacra is something that we would probably like to have a lot more of *before* the models get *smarter*, I feel this is worth exploring.

