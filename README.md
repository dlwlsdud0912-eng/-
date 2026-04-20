# DSR Calculator Portable

이 폴더만 노트북으로 옮기면 바로 이어서 작업할 수 있도록 정리한 휴대용 작업본입니다.

## 현재 공개 주소

- Cloudflare Pages: `https://dsrchamjoeun.pages.dev`
- 최신 배포 확인용: `https://4f77660d.dsrchamjoeun.pages.dev`

## 파일 설명

- `index.html`
  - 현재 작업 중인 메인 파일
  - 브라우저에서 바로 열면 계산기가 실행됩니다
  - 스트레스 DSR은 DSR 산정에만 반영되고, 월 납부액은 기본 입력 금리 기준으로 표시되도록 수정됨
  - 주담대 최대(역산) 카드에 희망금액 대비 차이와 기준 설명이 보이도록 정리됨

- `genspark-original.html`
  - 처음 받아온 원본 참고용 HTML
  - 비교하거나 계산 로직 확인할 때 참고용으로 보관

- `open-local.bat`
  - 더블클릭하면 현재 폴더의 `index.html`을 기본 브라우저로 엽니다

## 노트북에서 바로 쓰는 방법

1. 이 폴더 전체를 노트북으로 복사
2. `open-local.bat` 더블클릭
3. 또는 `index.html`을 브라우저로 직접 열기

## 이어작업 메모

- 현재 프로젝트는 단일 HTML 파일 기반입니다
- 별도 빌드 도구 없이 수정 가능
- 쿼리스트링으로 현재 입력값을 URL에 저장합니다
- 최근 작업: 숨겨져 있던 역산 비교/설명 정보를 결과 카드에 표시하도록 반영
- 최근 작업: Cloudflare Pages `dsrchamjoeun.pages.dev`에 공개 배포
- GitHub 업로드 저장소: `https://github.com/dlwlsdud0912-eng/-`
- GitHub Pages 예상 주소: `https://dlwlsdud0912-eng.github.io/-/`
  - 2026-04-20 확인 기준 아직 `404`였음

## 추천 작업 순서

1. `index.html`만 수정하면서 UI/계산식 계속 다듬기
2. 배포가 필요하면 Vercel/Cloudflare Pages/GitHub Pages 중 하나 연결
3. 안정화되면 폴더를 별도 저장소로 옮겨 관리
