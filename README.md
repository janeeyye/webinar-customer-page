# Microsoft 웨비나 추천 가이드

GitHub Pages용 정적 페이지입니다.

## 파일 구성

- `index.html`
- `webinar-sessions.json`

## 운영 방법

매월 `webinar-sessions.json` 파일만 같은 파일명으로 교체하면 됩니다.

## GitHub Pages 설정

1. Repository > Settings > Pages
2. Source: Deploy from a branch
3. Branch: `main`
4. Folder: `/ (root)`
5. Save

## JSON 필드

```json
{
  "id": "unique-id",
  "title": "세션 제목",
  "journey": "AI 시작하기",
  "level": 100,
  "category": "Copilot",
  "description": "세션 설명",
  "dateTime": "5월 21일 13:00",
  "targetAudiences": ["개발자", "IT 실무자"],
  "registrationUrl": "https://..."
}
```
