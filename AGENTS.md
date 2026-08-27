Project: Cyber Sufistik Lab

Architecture:
- Frontend: Next.js + TypeScript
- Backend: Laravel
- Database: PostgreSQL
- Cache: Redis
- AI: OpenAI API through AI Gateway
- Vector Search: pgvector

Rules:
- Use UUIDv7 for main entities.
- Never expose database IDs unnecessarily.
- All sensitive endpoints require authorization.
- All user inputs must be validated.
- Use REST API under /api/v1.
- Follow modular monolith architecture.
- Do not create LMS, RPS, attendance, KRS, or grading modules.
- Academic identity comes from the university system.
- Private reflections are private by default.
- AI must never generate clinical diagnoses.
- Add tests for every major feature.
- Add audit logging for sensitive actions.
