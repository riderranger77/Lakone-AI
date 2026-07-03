# Prompt Patterns

Reusable prompt frameworks for any AI model.

## 1. Role Pattern

```text
You are an expert [ROLE].
Your task is to [TASK].
```

## 2. Context Pattern

```text
Context:
[background information]

Task:
[specific request]
```

## 3. Goal Pattern

```text
Objective:
[goal]

Success criteria:
- [criteria 1]
- [criteria 2]
```

## 4. Step-by-Step Pattern

```text
Solve this step by step.
Check each step before continuing.
```

## 5. Output Format Pattern

```text
Return the answer as:
- Markdown table
- Bullet list
- JSON
- CSV
- Checklist
```

## 6. Critic Pattern

```text
Review the answer.
Find mistakes, missing context, and weak assumptions.
Then produce an improved version.
```

## Best Practice

Always provide:

- Context
- Goal
- Constraints
- Audience
- Output format
- Examples when useful
