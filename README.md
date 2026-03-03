# AURA-PROTOTYPE
AURA is an autonomous AI-powered learning assistant designed to actively support and optimize a student’s study journey. It goes beyond answering questions by continuously reasoning, planning, recalling, and retrieving relevant knowledge—even when the user isn’t actively studying.

**Key Highlights**
Four specialized AI agents run in parallel, coordinated by a central Orchestrator:

1. **The Coordinator:** Master brain that partitions work among 12 specialist sub-agents, handles task queues, resolves conflicts, and maintains high reliability (≈98% uptime, ~4 ms response).

2. **Daily Planner:** Decision engine that analyzes performance (struggles vs. strengths) to adjust the learning path and focus areas.

3. **Recall Engine:** Applies the forgetting curve to schedule timely reviews, tracking hundreds of concepts with proactive nudges.

4. **Resource Hunter:** Real-time knowledge retrieval that embeds user queries and searches a large corpus for the top 3 most relevant sources.

**Real-time, proactive learning experience:**
Personalized dashboard with study streaks, mastery scores, topics covered, exam countdown, and live AI insights.
Dynamic learning path updates driven by the Daily Planner.

**Robust knowledge layer:**
RAG pipeline: Documents embedded into vectors stored in a vector database for instant retrieval.
1,248 indexed documents (textbooks, notes, past exams) with high retrieval accuracy to ensure source-grounded responses.

**Proactive orchestration:**
The Orchestrator enables cross-agent communication and triggers re-planning when performance changes, delivering a truly autonomous learning assistant.


