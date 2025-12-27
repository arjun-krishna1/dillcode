# dillcode

Massively parallel coding agent using Gherkin files for spec-driven development. Written from scratch in Rust

## Features

- Coding agent
- Runs many agents in parallel using LLM council: https://github.com/karpathy/llm-council
- User should not see the actual code being written inside of dill code. Instead they see the specs being written and interact with the agent to write them. They see the LLM council thought process and outputs, the agent tells them how to try it out and use them etc
  - Gherkin file format: https://cucumber.io/docs/gherkin/reference/

## Code organization

- Clean architecture
- Separation of concerns
- Written from scratch
