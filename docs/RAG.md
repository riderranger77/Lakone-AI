# Retrieval Augmented Generation (RAG)

Retrieval Augmented Generation, or RAG, is a technique that combines information retrieval with AI text generation.

## Simple Explanation

Instead of asking an AI model to answer only from its internal knowledge, RAG first retrieves relevant information from a knowledge source and then asks the model to answer using that information.

## Why RAG Matters

RAG helps AI systems:

- Use private or custom documents
- Reduce hallucination
- Provide more grounded answers
- Keep knowledge easier to update
- Build question-answering systems

## Basic RAG Flow

1. Prepare documents.
2. Split documents into chunks.
3. Create embeddings for each chunk.
4. Store embeddings in a vector database.
5. Receive a user question.
6. Retrieve relevant chunks.
7. Send the chunks and question to the AI model.
8. Generate an answer.

## Use Cases

- Company knowledge base
- Legal document assistant
- Technical support chatbot
- Research assistant
- Personal document search
- Internal policy assistant

## Best Practices

- Use clean source documents.
- Chunk documents carefully.
- Store metadata.
- Retrieve only relevant context.
- Ask the model to answer only from provided sources when accuracy matters.
- Evaluate retrieval quality regularly.

## Limitations

- Bad retrieval leads to bad answers.
- Outdated documents can produce outdated responses.
- Poor chunking can break context.
- RAG still requires answer verification.

## Related Topics

- [Embeddings](EMBEDDINGS.md)
- [Vector Database](VECTOR_DATABASE.md)
- [LLM](LLM.md)
