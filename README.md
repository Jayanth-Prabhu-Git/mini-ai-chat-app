# gemini_gpt

Mini AI Chat App using flutter
Build a miniature ChatGPT/Gemini-style chat application using Flutter that runs on both Android and iOS. The app must support anonymous chat, Sign in with Google and Apple, a simple chat UI, and persistent conversations.

User Stories:
1.As a guest, I can link my account to Google/Apple without losing my chat history.
2.As a user, I can sign in with Google or Apple ID (Apple on iOS is required; Android web fallback is acceptable).
3.As a user, I can send a message and receive an AI response.
4.As a user, I can view my past conversations and continue one.
5.As a user, I can sign out; my guest session persists locally.

Minimum Scope (MVP):
1.Anonymous authentication (guest mode).
2.Google Sign-In (Android & iOS).
3.Sign in with Apple (iOS; Android optional via web).
4.Chat screen with message bubbles, timestamps, typing indicator, and simulated streaming response.
5.Handle "Empty States" (e.g., what the user sees when there are no chats yet).
6.Persist conversations and messages (Firestore suggested; local storage acceptable for guest).
7.Basic error states and loading indicators.
