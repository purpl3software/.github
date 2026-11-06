# Purple

**What should an AI agent know before it changes a business record?**

It needs to know which record it’s acting on, which changes are allowed, and when to ask a person to step in. Those are the same questions you have to answer when building an internal tool or integrating two systems. Purple is a platform for modeling business processes around a shared set of objects and actions that people and AI can work with.

## Start with a purchase request

Imagine a team needs to buy a new piece of equipment. A developer modeling that process might define a purchase request, its line items, and the supplier quotes attached to it. Each object has a place in the process, and the relationships matter. An approval is only useful if it applies to the right request and the right quote.

Then come the actions. Someone submits the request. An agent can help compare quotes. A reviewer can select a quote, ask for more information, or reject the request. The workflow describes when those actions are available and where human approval is needed. If a quote changes after approval, the team can decide whether that change sends the request back for review.

## What developers model

| Part of the model | What it captures |
| --- | --- |
| **Objects and relationships** | What the business works with and how records relate, such as a request and its quotes. |
| **Actions** | What someone can do, what inputs the action needs, and what it changes. |
| **Workflows** | When actions are available and where responsibility passes between people and systems. |
| **Integrations** | How the process connects to the data and tools the business already uses. |

The shared model gives developers a reference when building a UI, wiring up an integration, or exposing an action to an agent. A UI can show a reviewer the quote and its approval history. An agent can help prepare the same decision by summarizing differences in cost or delivery time. Both are working with the same request, and the approval rule belongs to the process itself.

That separation matters when a process evolves. Say a team adds a second approval for purchases above a threshold. With the rule represented in the workflow, developers have a defined place to update it and a clear way to reason about how the change affects the UI, integrations, and agent behavior.

[Explore Purple →](https://purple.software)

**Shared by People and AI**
