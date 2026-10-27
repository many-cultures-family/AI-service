# PRD (제품 요구사항 문서) v0.1 — 안내판

> **저장 위치:** `docs/PRD.md`

> **내용을 옮겨 적는 문서가 아니라, 어느 문서를 보면 되는지 알려 주는 안내판입니다.** 인수 조건은 `backlog.md`에, 제외 이유는 `mvp-scope.md`에 이미 있습니다. 같은 내용을 두 곳에 쓰면 한쪽만 고쳐졌을 때 어느 쪽이 맞는지 알 수 없습니다. 그래서 **문서 이름과 US 번호로 가리킵니다.**
> 기능은 `backlog.md`에 있는 `F-xx`와 `US`만 씁니다. 새 번호를 만들지 않습니다.
> 구현 순서와 API 라우트 상세는 쓰지 않습니다 (이후 로드맵, `API.md`).
> 모르는 것은 `미정`으로 씁니다. `>`로 시작하는 안내 문장은 지워도 됩니다.

- 버전: v0.1 (초안)
- 작성일:
- 상태: 검토 전

## 1. 개요
> 가져올 곳: 제안서(v2) 요약. 새로 쓰지 않고 한 줄씩만.

- 프로젝트명:
- 목적 (한 줄):
- 사용자 (한 줄):
- 개발 기간:

## 2. 사용자 여정
> 가져올 곳: `docs/requirements/user-flows.md`. 여정은 옮기지 않고 한 줄 요약과 링크만 둡니다.

- 핵심 흐름 (한 줄):
- 자세한 것: [docs/requirements/user-flows.md](requirements/user-flows.md)

## 3. 기술 스택
> 가져올 곳: `docs/STACK.md`. 다르게 쓰지 않습니다.

- 선택한 안 (한 줄):
- 자세한 것: [docs/STACK.md](STACK.md)

## 4. 기능 목록
> 가져올 곳: `backlog.md`의 **필수 스토리**. 취소·반려 스토리를 빠뜨리지 않습니다. **인수 조건 문장은 쓰지 않고 위치만 씁니다.**

| 기능 ID | 기능 | 스토리 (US) | 우선순위 | 경로 (정상 / 취소·반려) | LLM 관여 | 인수 조건 위치 |
| --- | --- | --- | --- | --- | --- | --- |
| | | | | | | `backlog.md` US-__ |

## 5. 데이터와 상태
> 가져올 곳: `docs/domain/03-rules-states-llm.md`. 상태값은 그 문서와 똑같이 씁니다. 데이터 구조 확정은 다음 차시입니다.

- 상태값: `03-rules-states-llm.md`의 상태 (이름 그대로)
- 자세한 것: [docs/domain/03-rules-states-llm.md](domain/03-rules-states-llm.md)

## 6. LLM의 역할
> 가져올 곳: `03-rules-states-llm.md`. 아래 두 가지를 그대로 가리킵니다.

- LLM이 맡는 일 (한 줄):
- **사람이 확인하기 전에는 상태가 바뀌지 않는다**: `03-rules-states-llm.md` 해당 부분
- LLM에 보내지 않을 정보: `03-rules-states-llm.md` 해당 부분

## 7. MVP 범위와 제외
> 가져올 곳: `docs/decisions/mvp-scope.md`. 포함 기능 ID만 쓰고, 제외 이유는 쓰지 않고 링크만 둡니다.

- MVP 포함 (기능 ID):
- 이번에 제외: [docs/decisions/mvp-scope.md](decisions/mvp-scope.md) 참고

## 8. 미정
> 실제로 아직 정하지 않은 것만 씁니다. 정한 것을 `미정`으로 남기지 않습니다.

| 항목 | 누가 언제 정하나 |
| --- | --- |
| | |
