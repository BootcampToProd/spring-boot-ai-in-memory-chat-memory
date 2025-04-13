# Spring AI Chat Memory: Build Smarter Conversational Applications

This repository demonstrates how to use **Spring AI's InMemoryChatMemory** implementation to manage chat conversations efficiently.

🚀 **It covers two key use cases:**

- A shared in-memory chat memory for all users.
- A user-specific in-memory chat memory to maintain individual conversation history.

📖 **Dive Deeper:** For a complete walkthrough and detailed explanation, read our blog:  
👉 [Spring AI Chat Memory: Build Smarter Conversational Applications](https://bootcamptoprod.com/spring-ai-chat-memory-guide/)

🎥 **Prefer a visual walkthrough?** Here’s a YouTube demo wherein I’ve explained the implementation step by step:
👉 https://youtu.be/QTaCb7lxyL8

---

## 📌 Important Note

### 🧠 InMemoryChatMemory Focus

- This implementation uses `InMemoryChatMemory` — ideal for POCs or applications where persistent storage is not required.
- Supports both single-session and multi-user chat handling with configurable memory key resolvers.