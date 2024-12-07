# 📚 Team Collaboration Guide

## 🌿 Branch Strategy
### Main Branches
- **Production Branch**: 배포용 브랜치
- **Deploy Branch**: 개발용 브랜치

### Branch Naming Convention
- JIRA 이슈 번호를 사용하여 브랜치 생성

## 🤝 PR (Pull Request) Rules
1. **직접 Push 금지**
    - 모든 코드 변경사항은 PR을 통해 진행

2. **PR 공유**
    - PR 생성 시 팀 톡방에 공유 필수

3. **코드 리뷰**
    - 2일 이내에 2명의 코드 리뷰 승인 필수
    - 리뷰어의 피드백을 반영하여 코드 품질 향상

## 📝 Commit Convention

### 커밋 메시지 구조
```
[<type>]: <summary> (#<issue>)

<body>
```

### 커밋 메시지 제목 규칙
- 형식: `[<type>]: <summary> (#<issue>)`
- 제목 길이: 최대 50글자
- 예시: `[feat]: 메인 페이지 구현 (#21)`

### Commit Types
| Type | Description |
|------|-------------|
| `build` | 빌드 관련 파일 수정 |
| `ci` | CI 관련 파일 수정 |
| `docs` | 문서 파일 수정 |
| `feat` | 새로운 기능 구현 |
| `fix` | 버그 해결 |
| `perf` | 성능 개선 |
| `refactor` | 코드 리팩터링 |
| `remove` | 파일 삭제 |
| `rename` | 파일명/디렉토리명 수정 또는 파일/디렉토리 이동 |
| `story` | FE storybook 관련 story 추가/변경 |
| `style` | 코드 스타일 변경 (ex. 세미콜론 추가, 공백 추가 등) |
| `test` | 테스트 코드 추가/수정/삭제 |

### Summary 작성 규칙
- 한글로 작성
- 간결하고 명확한 내용 요약
- 명령형으로 작성
- 현재 시제 사용
- 문장 형식 지양

### 커밋 메시지 본문 (선택사항)
- 한글로 작성
- 변경 사항에 대한 상세 설명
- 변경 이유 및 변경 전과의 비교 내용 포함

