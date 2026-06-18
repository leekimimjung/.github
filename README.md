# Contributing Guide

## 브랜치 네이밍
이름/기능 형식으로 생성한다.

예시
- jemin/frontend-chat
- gildong/backend-crawler
- sunyi/dify-kb

## 커밋 컨벤션
type: 내용 형식으로 작성한다.

| type | 설명 |
|------|------|
| feat | 새로운 기능 추가 |
| fix | 버그 수정 |
| docs | 문서 수정 |
| style | 코드 포맷, 세미콜론 등 (기능 변경 없음) |
| refactor | 코드 리팩토링 |
| chore | 빌드, 패키지 등 기타 작업 |

예시
- feat: 채팅 UI 컴포넌트 추가
- fix: 워크넷 API 연동 오류 수정
- docs: README 업데이트
- chore: 패키지 설치

## PR 규칙
- main 직접 push 금지
- PR 올리면 팀원 1명 이상 리뷰 후 merge
- PR 제목은 커밋 컨벤션과 동일하게