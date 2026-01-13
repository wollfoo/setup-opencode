# Multi-Agent Task Orchestration

Orchestrate specialized agents to handle complex tasks by breaking them into logical components and coordinating execution.

Spawn subagents (via the Task tool) for complex tasks that benefit from independent execution. Each subagent has its own context window and access to tools like file editing and terminal commands.

Subagents are most useful for multi-step tasks that can be broken into independent parts, operations producing extensive output not needed after completion, parallel work across different code areas, and keeping the main thread’s context clean while coordinating complex work.

However, subagents work in isolation — they can’t communicate with each other, you can’t guide them mid-task, they start fresh without your conversation’s accumulated context, and the main agent only receives their final summary rather than monitoring their step-by-step work.

Amp may use subagents automatically for suitable tasks, or you can encourage their use by mentioning subagents or suggesting parallel work.