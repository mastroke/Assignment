**Problem**: Restricting an LLM from answering entertainment-related questions while allowing for documentary-related queries.

**Challenges**: Distinguishing between entertainment and documentary topics accurately, handling diverse user phrasings, and ensuring scalability for real-world use cases.

**Method**:

NeMo Guardrails for runtime control over model outputs.

Colang for defining conversational flows and rules.

**Dataset Creation:**

Collect diverse examples of Entertainment-related questions (movies, actors, TV shows, music, games, sports, etc.)

Documentary-related questions (historical, educational, factual topics)

**Implementation:**

Integrated NeMo Guardrails into the LLM application.

Defined Colang rules: Identify patterns for entertainment and documentary questions.

Create flows to block entertainment answers and allow documentary responses.

Specify the model response for blocked entertainment queries.

Train and test the model with the dataset.

Fine-tune patterns and rules based on testing results.

**Testing and Evaluation**:

Use diverse test cases covering various question types and phrasings.

Measure success in correctly identifying and blocking entertainment queries while allowing documentaries.

Identify areas for improvement and refinement.

**Future Work:**  Explore techniques to further improve accuracy:

Investigate advanced model alignment or prompt tuning methods.

Expansion of the dataset with more diverse examples and edge cases.

Research natural language understanding techniques for better intent classification.
