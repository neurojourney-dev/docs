# hyprboost-ai 프로젝트 요약

1. **hyprboost-ai-engine**은 Hyprboost 서비스를 위한 백엔드 시스템으로, Python 3.12 기반의 FastAPI와 LangGraph를 활용해 구축된 AI 분석 엔진입니다.
2. OpenAI, Anthropic, Google GenAI 등 다양한 LLM 공급자와 Supabase, 웹 스크래핑 라이브러리를 결합하여 복잡한 에이전트 워크플로우와 데이터 처리를 수행합니다.
3. SSE(Server-Sent Events)를 통한 실시간 스트리밍 응답 기능을 제공하며, Railway 환경에 컨테이너 기반으로 손쉽게 배포할 수 있도록 구성되어 있습니다.
