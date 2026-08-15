# Orca 조정 기록

## 목표

사람·Codex의 내러티브 작업과 Claude의 구현·실행 검증을 같은 **로컬 Mac 작업 공간**에서 분리해 추적한다. `qa-pc`는 사용하지 않는다.

## 현재 Run

- 상태: 준비 검토 Dispatch됨 — Claude 완료 보고 대기
- Run: `run_b04aef087112`
- 목적: 이야기가 합의되면 Claude가 로컬 Mac에서 `game/index.html`을 구현하고 브라우저 실행을 검증한다.
- 작업자: Claude
- 준비 검토 Task: `task_ce6655589177`
- Claude Dispatch: `ctx_817310bd6a13`

## 현재 작업 흐름

1. 기반 검토 — Claude가 역할 문서와 경로를 읽고 준비 상태만 보고한다.
2. 구현 대기 — `narrative/STORY_SPEC.md`가 **구현 가능**이 될 때까지 코드 변경 금지.
3. 구현·검증 — 합의된 명세를 구현하고 실제 브라우저 플레이 결과를 보고한다.

## 기록 원칙

- Orca Run/Task/Dispatch는 조정용 실행 메타데이터다.
- 확정된 이야기·경로·검증 결과는 이 문서, `SESSION_HANDOFF.md`, `qa/PLAYTEST.md`, Notion에 남긴다.
- 완료 보고는 구현 여부와 실제 실행 검증 여부를 분리한다.
