# KkaiLab World Game Jam — 작업 공간

이 저장소는 **이야기부터 완성한 뒤, 한 장짜리 브라우저 게임으로 구현하는** 게임잼 작업 공간이다.

## 폴더의 역할

- `workshop/` — 수업 자료와 완성된 레퍼런스. 수정하지 않는다.
- `narrative/` — 참가자와 Codex가 합의한 이야기, 단서, 마지막 질문.
- `game/` — Claude가 구현하는 실제 게임. 최종 진입점은 `game/index.html`이다.
- `qa/` — Claude가 남기는 실행·플레이 검증 기록.
- `docs/` — 역할, 인수인계, Orca 조정 기록.

## 현재 단계

이야기 발산을 시작하기 전의 기반 단계다. `narrative/STORY_SPEC.md`가 **구현 가능** 상태가 되기 전에는 게임 기능을 만들지 않는다.

## 실행 환경

구현과 실행 검증은 현재 작업 중인 **로컬 Mac에서만** 수행한다. `qa-pc`를 연결하거나 사용하지 않으며, 다른 호스트의 결과는 이 게임잼의 검증 증거로 쓰지 않는다.

## 빠른 읽기 순서

1. 사람과 Codex: `narrative/STORY_SPEC.md`
2. Claude: `CLAUDE.md` → `docs/SESSION_HANDOFF.md` → `narrative/STORY_SPEC.md`
3. 모두: `docs/ORCHESTRATION.md`
