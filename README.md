# My templates for LLM

Use these with LLM 0.24a0 or later and the [llm-templates-github](https://github.com/simonw/llm-templates-github) plugin.

# Harper Reed's codegen workflow

https://harper.blog/2025/02/16/my-llm-codegen-workflow-atm/

Use the following templates to help bootstrap greenfield projects, using Harper's prompts and suggested models

## Idea Honing

```bash
llm -t gh:david-jarman/idea-honing "<idea>"
```

The model should ask you questions to help refine the idea. Continue the conversation with `-c`

```bash
llm -c "<answer to question from llm>"
```

## Planning

### TDD (test-driven development)

```bash
llm -t gh:david-jarman/planning-tdd -c
```
