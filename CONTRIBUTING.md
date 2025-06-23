# 📝 Contributing Guide

팀 프로젝트에 오시는 것을 환영합니다!
이 가이드는 우리 팀의 협업 규칙과 개발 컨버션을 정리한 문서입니다.

---

## 📌 프로젝트 참여 방법

### 1️⃣ Fork 하기

* 이 저장소를 자신의 GitHub 계정으로 Fork 합니다.
* 저장소 이름은 다음 규칙을 따릅니다:
  `NFE5-GIT-TEAM-{ud300번호}`

### 2️⃣ Clone 하기

Fork한 저장소를 복제해서 보는 방식입니다.

```bash
git clone https://github.com/{your-username}/NFE5-GIT-TEAM-{ud300번호}.git
cd NFE5-GIT-TEAM-{ud300번호}
```

### 3️⃣ 작업 브랜치 만들기

새로운 기능 개발은 항상 새 브랜치에서 시작합니다.

```bash
git checkout -b feature/{기능이름}
```

---

## 🔧 브랜치 규칙

* `main`: 안정된 배포용 브랜치
* `feature/{기능이름}`: 기능 개발 브랜치
* `fix/{수정내용}`: 버그 수정 브랜치

---

## ✨ 커미트 메시지 규칙

형식:
`ud0c입: 간단한 설명`

| ud0c입    | 설명                |
| -------- | ----------------- |
| feat     | 새로운 기능 추가         |
| fix      | 버그 수정             |
| docs     | 문서 수정             |
| style    | 코드 포맷팅 (기능 수정 없음) |
| refactor | 코드 리파트링           |
| test     | 테스트 추가/수정         |
| chore    | 기타 자바한 작업         |

예시:

```bash
feat: 로그인 기능 추가
fix: 회원가입 버그 수정
```

---

## 🔍 Pull Request 규칙

* PR 제목은 작업 내용을 간단히 작성
* PR 발생시 필요에 따라 리뷰어 지정 받기
* 통과한 후 main 브랜치로 머지

---

## 💻 코드 스타일

* 코드 스타일 통일을 위해 다음 도구 사용

  * Prettier (ud3ec매트터)
  * ESLint (ubb38리 검사)
* VSCode ud655산 추천:

  * Prettier - Code formatter
  * ESLint

---

## 😝 협업 매너

* 징무는 없습니다. 문의는 어느 것이든 환영!
* Git과 GitHub을 잘 못해도 그린가지로 가르치면 합니다 😄

---

