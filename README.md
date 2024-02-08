# YouTube Assistant

A helpful YouTube assistant that can answer questions about videos based on the video's transcript.

In the PromptTemplate, the LLM is given the template:
```
Only use the factual information from the transcript to answer the question.

If you feel like you don't have enough information to answer the question,
say "I don't know".

Your answers should be detailed.
```
