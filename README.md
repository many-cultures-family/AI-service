# 디딤돌

## 팀

| 항목 | 내용 |
| --- | --- |
| 팀명 | IDDP |
| 배정받은 큰 도메인 | 다문화 가정을 위한 디지털 적응·교육 서비스 |
| 세부 주제 (한 줄) | `다문화 가정 구성원`(누가)가 `공문서 작성 연습`(무엇)을 할 수 있게 하는 서비스 |
| 팀원과 역할 | [docs/team/roles.md](사전활동 팀 저장소 템플릿/docs/team/roles.md) |

## 세부 주제 필수 조건

| 조건 | 우리 주제에서는 | 자세히 |
| --- | --- | --- |
| LLM이 서비스 기능 안에서 쓰인다 | 공고문·신청서 내용을 모국어와 쉬운 한국어로 설명하고 가상 신청서 초안을 만들어 상담원·사용자가 확인한다 | [03-rules-states-llm.md](사전활동 팀 저장소 템플릿/docs/domain/03-rules-states-llm.md#3-4-llm이-들어갈-자리) |
| 핵심 대상에 상태 전이가 있다 | 신청 건: 접수됨 → 연습환경 검토중 → 리허설중 → 실전준비완료 → 실전작성중 → 최종점검완료 → 제출완료 → 승인·반려 → 종결 (취소·만료·보완요청 분기) | [03-rules-states-llm.md](사전활동 팀 저장소 템플릿/docs/domain/03-rules-states-llm.md#3-2-핵심-대상과-상태-전이) |

## 문서 지도

| 단계 | 파일 | 하는 일 | 상태 |
| --- | --- | --- | --- |
| 0 | [docs/team/roles.md](사전활동 팀 저장소 템플릿/docs/team/roles.md) | 팀 구성, 역할, 교대 계획 | ☑ |
| 0 | [docs/domain/README.md](사전활동 팀 저장소 템플릿/docs/domain/README.md) | 조사 관점, 태그 규칙, 파일 규칙, 찾아볼 곳 | 읽기만 |
| 1 | [docs/domain/01-first-look-glossary.md](사전활동 팀 저장소 템플릿/docs/domain/01-first-look-glossary.md) | 첫인상, 용어 사전, 검색어 | ☑ |
| 2 | [docs/domain/02-people-flow-benchmark.md](사전활동 팀 저장소 템플릿/docs/domain/02-people-flow-benchmark.md) | 사람, 현재 흐름, 데이터, 기존 서비스, 논문 | ☑ |
| 3 | [docs/domain/03-rules-states-llm.md](사전활동 팀 저장소 템플릿/docs/domain/03-rules-states-llm.md) | 규칙, 상태 전이, LLM 자리, 법령·통계 | ☑ |
| - | [docs/domain/cards/](사전활동 팀 저장소 템플릿/docs/domain/cards/) | 논문·자료 근거 카드 (카드마다 파일 하나) | ☑ |
| - | [docs/domain/ai-check-log.md](사전활동 팀 저장소 템플릿/docs/domain/ai-check-log.md) | AI에게 물어본 것과 확인 결과 | ☑ |
| 4 | [docs/decisions/topic-selection.md](사전활동 팀 저장소 템플릿/docs/decisions/topic-selection.md) | 필수 조건 확인, 후보 평가, 주제 확정 | ☑ |
| 5 | [docs/interview/mvp-assumptions-questions.md](사전활동 팀 저장소 템플릿/docs/interview/mvp-assumptions-questions.md) | MVP 가설, 기능 목록, 가정·위험, 질문지, 미팅 준비 | ☑ |
| 6 | [docs/proposal/README.md](사전활동 팀 저장소 템플릿/docs/proposal/README.md) | **클라이언트에게 보내는 프로젝트 제안서** (Claude 초안 → 팀 확인 → Word 양식, 완성본 docx·PDF) | ☐ |
| - | `logs/pre-[GitHub 아이디].md` | 개인 회고 (사람마다 파일 하나) | ☐ |

## 논문·자료 근거 카드

| 순서 | 파일 | 팀원 이름 |
| --- | --- | --- |
| 1 | [1-kimwonu-bit-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/1-kimwonu-bit-01.md) | 김원우 |
| 2 | [1-kimwonu-bit-02.md](사전활동 팀 저장소 템플릿/docs/domain/cards/1-kimwonu-bit-02.md) | 김원우 |
| 3 | [1-kimwonu-bit-03.md](사전활동 팀 저장소 템플릿/docs/domain/cards/1-kimwonu-bit-03.md) | 김원우 |
| 4 | [1-kimwonu-bit-04.md](사전활동 팀 저장소 템플릿/docs/domain/cards/1-kimwonu-bit-04.md) | 김원우 |
| 5 | [2-kimwonu-bit-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/2-kimwonu-bit-01.md) | 김원우 |
| 6 | [2-leehyosang6950-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/2-leehyosang6950-01.md) | 이효상 |
| 7 | [2-leehyosang6950-02.md](사전활동 팀 저장소 템플릿/docs/domain/cards/2-leehyosang6950-02.md) | 이효상 |
| 8 | [4-kimwonu-bit-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/4-kimwonu-bit-01.md) | 김원우 |
| 9 | [4-kimwonu-bit-02.md](사전활동 팀 저장소 템플릿/docs/domain/cards/4-kimwonu-bit-02.md) | 김원우 |
| 10 | [4-kimwonu-bit-03.md](사전활동 팀 저장소 템플릿/docs/domain/cards/4-kimwonu-bit-03.md) | 김원우 |
| 11 | [5-kimwonu-bit-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-kimwonu-bit-01.md) | 김원우 |
| 12 | [5-kimwonu-bit-02.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-kimwonu-bit-02.md) | 김원우 |
| 13 | [5-kimwonu-bit-03.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-kimwonu-bit-03.md) | 김원우 |
| 14 | [5-leehyosang6950-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-leehyosang6950-01.md) | 이효상 |
| 15 | [5-sjy0128-01.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-sjy0128-01.md) | 석준영 |
| 16 | [5-sjy0128-02.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-sjy0128-02.md) | 석준영 |
| 17 | [5-sjy0128-03.md](사전활동 팀 저장소 템플릿/docs/domain/cards/5-sjy0128-03.md) | 석준영 |

## 개인 회고

| 파일 링크 | 이름 | 깃허브 닉네임 |
| --- | --- | --- |
| `pre-tmdahr.md` | 박승목 | tmdahr |
| `pre-sjy0128.md` | 석준영 | sjy0128 |
| `pre-dldmsco-29.md` | 이은채 | dldmsco-29 |
| `pre-kimwonu-bit.md` | 김원우 | kimwonu-bit |
| `pre-leehyosang6950.md` | 이효상 | leehyosang6950 |

## 작업 규칙

- 첫 커밋 이후에는 main에 바로 커밋하지 않습니다. 모든 변경은 브랜치를 만들고 PR로 올린 뒤, 팀원 1명 이상이 승인하면 병합합니다.
- 표가 있는 단계 파일(01~03, topic-selection 등)은 **블록마다 정리 담당 1명**이 고칩니다. 다른 사람은 근거 카드를 쓰거나 PR에 댓글을 남깁니다. 여러 명이 같은 파일을 동시에 고치면 충돌이 납니다.
- 근거 카드와 개인 회고는 사람마다 파일이 달라 동시에 써도 충돌하지 않습니다.
