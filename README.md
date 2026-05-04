# 알고리즘 일기 (My Feed Diary)

오늘 본 SNS 콘텐츠 중 좋았던 것 / 별로였던 것을 기록하면  
Claude AI가 분석해서 **"내가 진짜 좋아하는 것"** 을 요약해주는 웹 앱.

## 실행 방법

1. `index.html` 파일을 브라우저에서 열기
2. 파일 상단의 `API_KEY` 자리에 [Anthropic API 키](https://console.anthropic.com) 입력
3. 바로 사용 가능 (서버 설치 불필요)

```js
const API_KEY = "여기에_API_키를_입력하세요";
```

## 기능

- ✍️ 오늘의 피드 기록 (좋았던 것 / 별로였던 것)
- 🤖 Claude AI 취향 분석 (요약 + 6개 카테고리 키워드 + 한 마디)
- 📖 날짜별 기록 아카이브 (localStorage 저장)
- 📱 모바일 최적화 UI

## 기술 스택

- HTML / CSS / JavaScript (단일 파일)
- Claude API (`claude-sonnet-4-20250514`)
- localStorage

> ⚠️ API 키는 절대 GitHub에 커밋하지 마세요.
