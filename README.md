# Microsoft Webinar Customer Page

정적 고객용 웨비나 페이지입니다. GitHub Pages에 올릴 때는 이 폴더의 파일을 그대로 저장소 루트에 업로드하면 됩니다.

## 파일 구조
- `index.html`: 화면/모달/스타일/스크립트가 모두 포함된 단일 정적 페이지
- `webinar-sessions.json`: 매월 교체할 세션 데이터

## 업데이트 방법
1. 편집자용 Spark 페이지에서 JSON을 Export합니다.
2. GitHub 저장소의 기존 `webinar-sessions.json`만 교체합니다.
4. GitHub Pages가 켜져 있으면 변경사항이 반영됩니다.

## GitHub Pages 설정
Repository > Settings > Pages > Deploy from a branch > `main` / root 선택

## 주의
브라우저 보안 정책 때문에 로컬에서 `index.html`을 더블클릭하면 JSON fetch가 막힐 수 있습니다. 확인은 GitHub Pages 배포 후 하거나 간단한 로컬 서버로 확인하세요.
