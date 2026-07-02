# Claude Best Practices

## 1. Provide Rich Context

Claude performs well when the task includes enough background and clear instructions.

## 2. Use Structured Instructions

Break complex requests into sections:

- Role
- Context
- Task
- Constraints
- Output format

## 3. Ask for Careful Analysis

Claude is useful for summarizing, comparing, rewriting, and analyzing longer material.

## 4. Define the Desired Style

Example:

```text
Use a calm, precise, and professional tone.
```

## 5. Request a Clear Output

Example:

```text
Return the answer as:
1. Summary
2. Key points
3. Risks
4. Recommended next steps
```

## Simple Claude Prompt Formula

```text
You are helping me with [task].
Here is the context: [context].
Please analyze carefully and provide [output format].
Use these constraints: [constraints].
```
