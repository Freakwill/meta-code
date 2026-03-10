# Meta-code

meta agent for opencode

## Agent

- factory: agent to make agents
- meta: agent to manage the entire opencode (manage the configuration files, also creating agents)

## Prompt to generate the agent

> Create a new subagent named meta that manages the entire OpenCode setup—for example, by modifying the relevant configuration (mainly files under .config/opencode/ and .local/share/opencode/), especially automating the creation of agents and subagents, and also creating skills, commands, rules, etc. Refer to https://opencode.ai/docs/.

## Prompt based on `@factory`

> Using .config/opencode/agents/factory.md as a base, create a new subagent named meta that manages the entire OpenCode setup—for example, by modifying the relevant configuration (mainly files under .config/opencode/ and .local/share/opencode/), especially automating the creation of agents and subagents, and also creating skills, commands, rules, etc. Refer to https://opencode.ai/docs/.
