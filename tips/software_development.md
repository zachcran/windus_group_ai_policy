# AI Tips for Software Development

## Software Design

- Spend time learning how to design code. Use the plan mode to write formal design docs that specify what the code should and shouldn't do. Use the more powerful model for planning/designing and a weaker model for writing the code. This should be the contract with which your code is written. Motivation: AI can generate and debug thousands of lines of codes quickly. With a good design, writing the code is largely mechanical. This means, with a good design, entire class hierarchies can be brought to life in minutes.

## Software Development

- Spend time learning how to identify and fix tech debt. Motivation: without a thorough design, the AI will likely generate verbose, repetitive code, and take shortcuts. While the AI will make fixing this tech debt much easier, it won't do so without prompting and guidance from you.

## Debugging

- AI is amazing at debugging code. While it is tempting to just ask the AI to fix a compilation error, an exception, or a segfault, it's important to understand why the error occurred so you can determine if the error is actually a symptom of a larger problem. Motivation: AI tends to approach problems greedily, it's going to do what is best for the specific situation, e.g., you asked it fix a segfault, maybe it copies to value to extend the lifetime. That solves the problem if you were supposed to be managing the lifetime, but if another piece of the code was, then the bug is there.

