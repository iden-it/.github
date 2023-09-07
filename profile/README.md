# iDEN.iT

iDEN.iT Github 사용 가이드입니다.

---

## 🔖 Repository Convention

Repository는 프론트와 백엔드, 프로젝트의 구분으로 prefix를 사용합니다. \
백엔드의 경우에는 프로젝트의 구분은 굳이 두지 않습니다.

> Repository의 구분을 위해 규칙을 지켜주세요.
 
<br>

### 📖 가이드

- 개발 구분 (필수)
  - `FE`: 프론트
  - `BE`: 백엔드
- 프로젝트 구분 (필수)
  - `WEB`: 웹 프로젝트
  - `APP`: 앱 프로젝트
  - `WAPP`: 웹/앱 프로젝트
  - `IDENIT`: 사내 프로젝트
- 프로젝트명 (선택)
  - 프로젝트명을 작성하고, 뒤에 `하이픈(-)`을 이용하여 `admin`또는 `client(user)`의 구분을 합니다.

### 💪🏻 예시

- Front-End
  1. `FE_WAPP_orderhero-admin`
  2. `FE_APP_momsnote`
  3. `FE_IDENIT_components`
- Back-End
  1. `BE_orderhero-admin`
  2. `BE_orderhero-client`

---

## ✅ Commit Message

커밋 메시지를 일관성있게 통일시킵니다.

<br>

### 📖 가이드

- `feat`: 새로운 기능 추가 
- `fix`: 버그 수정 
- `docs`: 문서 수정 
- `style`: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 
- `refactor`: 코드 리펙토링 
- `test`: 테스트 코드, 리펙토링 테스트 코드 추가 
- `chore`: 빌드 업무 수정, 패키지 매니저 수정

### 💪🏻 예시

- `feat`
  - `feat: 주문기능 개발`
  - `feat: 상품 목록 UI`
- `fix`
  - `fix: 버튼 UI 개선`
- `docs`
  - `docs: README.md 추가 가이드 작성`