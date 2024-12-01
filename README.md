# 🎯 Mind Goal Backend

## 📌 Git Convention

### 1️⃣ Commit Convention
커밋 메시지는 다음과 같은 형식을 따릅니다:
```
type: subject

body (optional)
```

#### ⭐ Commit Type
| Type | Description |
|------|-------------|
| `feat` | 새로운 기능 추가 |
| `fix` | 버그 수정 |
| `docs` | 문서 수정 |
| `style` | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 |
| `refactor` | 코드 리팩토링 |
| `test` | 테스트 코드 추가 또는 수정 |
| `chore` | 빌드 관련 수정, 패키지 매니저 수정 |

#### 📝 Subject 규칙
- 50자를 넘기지 않습니다
- 마침표를 붙이지 않습니다
- 한글로 작성합니다

### 2️⃣ Branch Convention
브랜치는 다음과 같은 형식을 따릅니다:
```
type/feature-name
```

#### 🌿 Branch Type
| Branch | Description |
|--------|-------------|
| `main` | 배포 브랜치 |
| `develop` | 개발 브랜치 |
| `feature` | 기능 개발 브랜치 |
| `hotfix` | 긴급 수정 브랜치 |

#### 예시
```
feature/login
feature/expert-profile
hotfix/user-auth
```

### 3️⃣ PR Convention
Pull Request는 다음 형식을 따릅니다:
```
[type] title

내용
```

#### 예시
```
[Feat] 로그인 기능 구현

- 소셜 로그인 추가
- JWT 토큰 발급 구현
- 예외 처리 추가
```

---
### ⚙️ Project Setup
```bash
git clone https://github.com/Mind-Goal/Mind-Goal-Backend.git
cd mind-goal-backend
```
