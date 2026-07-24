# Circus PoC 배포 저장소 — 공통 작업 안내

> Claude·Codex 공통 규칙 원본. 이 저장소를 직접 열어 작업할 때 사용.

## 이 저장소의 역할

서커스 게임의 현재 HTML 프로토타입을 GitHub Pages에 공개하는 별도 저장소다. 게임 기획과 원본 프로토타입은 이 저장소 밖의 `game-project/`에서 관리한다.

## 시작할 때 읽을 문서

1. `../game-project/CLAUDE.md` — 게임 프로젝트 공통 작업 기준
2. `../game-project/concepts/circus_game.md` — 현재 서커스 게임 기준
3. `../game-project/poc/circus_live_show_poc.html` — 배포할 HTML 원본
4. `README.md` — 이 저장소의 공개 범위

`index.html`은 배포용 복사본이다. 기능을 바꿀 때는 원본 프로토타입을 먼저 수정하고, 확인한 파일을 `index.html`에 반영한다. 수정 작업은 공개 사이트 배포와 실제 주소 확인까지 포함한다.
