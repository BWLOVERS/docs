## Team 21  BWLOVERS

| 항목 | 내용 |
| --- | --- |
| **프로젝트명** | 어린이를 위한 119 긴급상황 대비 교육용 시뮬레이션 RAG 챗봇 |
| **프로젝트 키워드** | 긴급상황, 어린이, 챗봇 |
| **트랙** | 산학 |
| **프로젝트 멤버** | 백소영, 양은서, 우윤수 |
| **팀지도교수** | 황의원 교수님 |
| **무엇을 만들고자 하는가** | 어린이를 위한 119 신고 교육용 RAG 기반 챗봇 서비스입니다. 이 서비스는 화재, 응급 환자 발생, 교통사고 등 다양한 긴급 상황을 대화형 시뮬레이션으로 제공합니다. 어린이는 가상의 상황 속에서 위치, 상황, 인원, 부상 정도, 위험 요소와 같은 필수 정보를 정확하고 신속하게 파악하고 119에 신고하는 연습을 할 수 있습니다. 이를 통해 실제 위급 상황에 대한 위기 대응 능력을 향상시키고, 올바른 신고 습관을 기르며, 위기 상황에 대한 자신감을 키우는 것을 목표로 합니다. |
| **고객** | 박민서(초등학교 3학년, 10세)<br>- Pain Point: 긴급 상황에서 당황해서 말이 잘 안 나오고, 어떤 정보를 말해야 하는지 기억하기 어려워 한다.<br>- Needs: 실제 긴급 상황에서 당황하지 않고 침착하게 대처할 수 있는 능력을 키우고, 위기 대응에 대한 자신감을 얻고 싶어 한다. |
| **Pain Point** | 긴급 상황 발생 시 당황하여 신고에 필요한 핵심 정보를 정확하고 신속하게 전달하지 못하는 경우가 많습니다. 특히 어린이의 경우와 같이 어른에 비해 상대적으로 위기 대응 경험이 부족한 경우, 실제 119 긴급상황에서 당황하기 때문에 효과적으로 구조 요청을 전달하는 데 어려움을 겪으며, 이 경우 출동이 지체될 수 있습니다. 즉, 기존의 안전 교육은 실제 상황에 적용하기 어렵다는 문제점을 가지고 있습니다. |
| **사용할 소프트웨어 패키지의 명칭과 핵심기능/용도, 사용시나리오** | - **Spring Boot**: 백엔드 서버 구현, API 관리, 사용자 요청 처리<br>- **MySQL**: 사용자 학습 기록, 시뮬레이션 데이터 저장<br>- **React**: 시뮬레이션 UI, 챗봇 인터페이스, 배지/스티커 시각화<br>- **Speech-to-Text (STT) API**: 어린이 음성 입력을 텍스트로 변환<br>- **Text-to-Speech (TTS) API**: 구급대원 음성 피드백 제공<br>- **OpenAI API (GPT-5)**: RAG 기반 Q&A, 신고 문장 합성, 공식 문서 근거 인용<br>- **LangChain**: RAG 기반 챗봇을 구현하기 위한 핵심 프레임워크 |
| **사용할 소프트웨어 패키지의 명칭과 URL** | **[ Backend ]**<br>- [Spring Boot](https://spring.io/projects/spring-boot)<br>- [MySQL](https://www.mysql.com)<br>- [AWS RDS](https://aws.amazon.com/rds/)<br>- [Docker](https://www.docker.com/)<br><br>**[ Frontend ]**<br>- [React](https://ko.react.dev/)<br><br>**[ AI ]**<br>- 음성 인식 : [Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text)<br>- 음성 변환 : [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech?hl=ko)<br>- 자연어 처리 (NLP) : [GPT-5](https://openai.com/research/gpt-4)<br>- RAG 프레임워크 : [LangChain](https://www.langchain.com/) |
| **팀그라운드룰** | [BWLOVERS GroundRule](https://github.com/BWLOVERS/docs/blob/main/GroundRule.md) |
| **최종수정일** | 2025-09-16 |
