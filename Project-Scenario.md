## Team 21  BWLOVERS

| 항목 | 내용 |
| --- | --- |
| **프로젝트명** | 태아보험 특약 선택과 보장 범위 이해를 위한 산모 맞춤형 RAG 기반 보험 분석 서비스 |
| **프로젝트 키워드** | 산모, 태아보험, 보장 여부 분석, 맞춤형 가이드, RAG |
| **트랙** | 산학 |
| **프로젝트 멤버** | 백소영, 양은서, 우윤수 |
| **팀지도교수** | 이형준 교수님 |
| **무엇을 만들고자 하는가** | 산모가 태아보험 가입 전후 과정에서 복잡한 약관과 특약 조건을 쉽게 이해하고, 본인 상황에 맞는 보험을 선택할 수 있도록 돕는 RAG 기반 보험 분석 서비스입니다. 보험 용어를 쉽게 설명하고 사용자가 자신의 조건(임신 주차, 건강 상태, 필요 보장 항목 등)을 입력하면 챗봇은 보험 약관·소비자 가이드·판례 데이터를 검색하여 가장 적절한 보험을 추천합니다. 또한, 이미 가입한 보험에 대해서는 특정 상황에서 보장이 가능한지를 판단해주며, 보장·면책 조항을 직관적으로 시각화하여 산모의 합리적인 의사결정을 지원합니다. |
| **고객** | 김지현(30세 직장인, 첫 산모보험 가입)<br>- Pain Point: 보험 설계사 설명만으로는 관련 약관을 이해하기 어렵고, 불리한 조항을 놓칠 수 있다. 또한, 다양한 특약 중, 어떤 특약이 꼭 필요한지에 대해서 쉽게 알기 어렵다.<br>- Needs: 본인 상황(임신 주차, 건강 상태)에 맞는 보험을 올바르게 선택하고, 갱신·해지 조건을 미리 파악해 재정적 손실을 피하고 싶어 한다.<br><br>박소연(32세, 임신 28주, 임신성 당뇨 진단, 이미 태아보험 가입)<br>- Pain Point: 임신성 당뇨 진단으로 고위험 임신 상황이지만, 현재 가입한 보험이 조산이나 합병증을 실제로 보장하는지 확신이 없다.<br>- Needs: 본인의 건강 상태를 반영해 가입한 보험의 보장 여부와 한계를 확인하고, 부족하다면 추가 특약이나 다른 대안을 알고 싶다.|
| **Pain Point** | - 보험사마다 태아 보험 상품이 다양하고 항목, 보험료, 특약 조건 등이 달라 자신에게 가장 적합한 보험을 선택하는 것이 어렵고 시간이 많이 걸린다. <br> - 길고 방대한 약관과 난해한 전문 용어 때문에 보험의 보장 범위와 조건을 직관적으로 이해하기 어렵다. <br> - 기존 서비스 만으로는 산모의 건강 상태와 특정 상황에 따라 실제로 보장 대상이 되는지 판단하기 어렵다.|
| **사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오** | - **Spring Boot**: 사용자 관리, 로그 기록 등 백엔드 서버 구현<br>- **PostgreSQL**: 사용자 프로필(임신 주차, 건강 상태 등), 보험 계약서 메타데이터, 챗봇 대화 로그 저장<br>- **React**: 챗봇 인터페이스, 건강 상태 입력/수정 UI, 특약 선택 및 보장 범위 시각화<br>- **OpenAI API (GPT-5), Gemini 2.5, Claude, Llama 4**: 태아보험 관련 질의응답, 맞춤형 가이드 및 추천 생성<br>- **LangChain / LangGraph**: RAG 기반 약관·가이드·판례 검색 및 챗봇 워크플로우 관리<br>- **Ragas / LangSmith**: LLM 응답 품질 평가, RAG 파이프라인 성능 모니터링 및 디버깅<br>- **CLOVA OCR**: 약관 PDF·스캔 이미지에서 한글 텍스트·표·키-값 필드를 추출해 구조화 |
| **사용할 소프트웨어 패키지의 명칭과 URL** | **[ Backend ]**<br>- [Spring Boot](https://spring.io/projects/spring-boot)<br>- [PostgreSQL](https://www.postgresql.org/)<br>- [FastAPI](https://fastapi.tiangolo.com/)<br>- [AWS RDS](https://aws.amazon.com/rds/)<br>- [Docker](https://www.docker.com/)<br><br>**[ Frontend ]**<br>- [React](https://ko.react.dev/)<br><br>**[ AI ]**<br>- 자연어 처리 (NLP) : [GPT-5](https://openai.com/research/gpt-4), [Gemini 2.5](https://ai.google.dev/gemini-api/docs?hl=ko), [Claude](https://docs.claude.com/en/home), [Llama 4](https://www.llama.com) <br>- RAG 프레임워크 : [LangChain](https://www.langchain.com/) <br>- StateGraph 워크플로우 : [LangGraph](https://www.langchain.com/) <br>- LLM 생성 평가 (Evals) : [Ragas](https://docs.ragas.io/en/stable/), [LangSmith](https://www.langchain.com/langsmith) <br>- OCR : [CLOVA OCR](https://www.ncloud.com/product/aiService/ocr)|
| **팀그라운드룰** | [BWLOVERS GroundRule](https://github.com/BWLOVERS/docs/blob/main/GroundRule.md) |
| **최종수정일** | 2025-12-01 |
