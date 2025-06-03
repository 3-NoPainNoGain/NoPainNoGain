# 🩺 handDoc 

handDoc는 청각장애인을 위한 수어-텍스트-음성 변환 비대면 진료 서비스를 제공하는 웹 애플리케이션입니다. 청각장애인의 수어를 인식하고 의사에게 텍스트로 변환되어 전송되며, 의사의 음성 또한 텍스트로 변환되어 환자에게 전달됩니다. 

---
## 📂 파트별 Repository 
- 각 파트별 기술 스택과 세부 구현 내용은 링크된 파트별 `README.md` 에서 확인할 수 있습니다.

  - [FastAPI](https://github.com/3-NoPainNoGain/FastAPI) : 
  - [AI](https://github.com/3-NoPainNoGain/AI) : 
  - [Frontend](https://github.com/3-NoPainNoGain/FE) : 
  - [Backend](https://github.com/3-NoPainNoGain/BE) : 사용자 인증, 

--- 
## 📌 Convention 
### Branch Convention 
| 머릿말 | 설명 |
| --- | --- |
| main | 서비스 브랜치 |
| develop | 배포 전 작업 기준 |
| feat | 기능 단위 구현 |
| chore | 기본 설정, 의존성, yml 등 기타 작업 브랜치 | 
| refactor | 리팩토링 브랜치 (기능 변화 없음) | 
| hotfix | 서비스 중 긴급 수정 건에 대한 처리 | 

Branch 생성 예시 
- feat/social-login-#5
- feat/기능요약-이슈번호

---
### ✨  PR 템플릿
<details>
<summary> PR 템플릿 보기</summary>
  
```
## 🪺 Summary


## 🌱 Issue Number
<!-- #뒤에 이슈넘버 써주시면 자동으로 이슈페이지 연결이 됩니다!-->
- #


## 🙏 To Reviewers

```
</details>

PR Title 규칙 
- 형식 : [issue_name] content
- 예시 : [Feat] 로그인 구현

PR 세부 규칙 
- merge 대상 브랜치 : develop
- 코드 리뷰 승인 최소 1명 필수

---
### ✨  이슈 템플릿 
<details>
<summary> 이슈 템플릿 보기</summary>
  
```  
---
name: 이슈 생성 템플릿
about: 해당 이슈 생성 템플릿을 사용하여 이슈를 생성해주세요.
title: ''
labels: ''
assignees: ''
---

## Description
해당 이슈에 대한 설명
## Changes
### 변경 사항 제목
- [ ] 세부 사항 1
- [ ] 세부 사항 2
## API
| URL                | method | Usage                | Authorization Needed |
| ------------------ | ------ | -------------------- | -------------------- |
| api 경로       | POST| API 용도| 인가 필요성                    |
## Additional context
추가적인 내용

```
</details>

<img src="https://github.com/user-attachments/assets/88589376-4644-46b5-94fe-dc913cb72db0" width="400"/>

### 🗨️ 커밋 메시지 컨벤션 

1. 커밋 유형 지정
- 커밋 유형은 영어 대문자로 작성하기

| 커밋 유형 | 의미 |
| --- | --- |
| `Feat` | 새로운 기능 추가 |
| `Fix` | 버그 수정 |
| `Docs` | 문서 수정 |
| `Style` | 코드 formatting, 세미콜론 누락, 코드 자체의 변경이 없는 경우 |
| `Refactor` | 코드 리팩토링 |
| `Test` | 테스트 코드, 리팩토링 테스트 코드 추가 |
| `Chore` | 패키지 매니저 수정, 그 외 기타 수정 ex) .gitignore |
| `Design` | CSS 등 사용자 UI 디자인 변경 |
| `Comment` | 필요한 주석 추가 및 변경 |
| `Rename` | 파일 또는 폴더 명을 수정하거나 옮기는 작업만인 경우 |
| `Remove` | 파일을 삭제하는 작업만 수행한 경우 |
| `!HOTFIX` | 급하게 치명적인 버그를 고쳐야 하는 경우 |

2. 제목과 본문을 빈행으로 분리
- 커밋 유형 이후 제목과 본문을 한글로 작성하여 내용이 잘 전달될 수 있도록 할 것
- 본문에는 변경한 내용과 이유 설명 (어떻게 보다는 무엇 & 왜를 설명)
3. 제목 첫 글자는 대문자로, 끝에는 `.` 금지
4. 제목은 영문 기준 50자 이내로 할 것
5. 마지막에 이슈번호 추가하기
6. 자신의 코드가 직관적으로 바로 파악할 수 있다고 생각하지 말자
7. 여러 가지 항목이 있다면 글머리 기호를 통해 가독성 높이기
```
- 변경 내용 1
- 변경 내용 2
- 변경 내용 3
```
8. 예시
```
BE
커밋유형: 기능 설명 (#이슈번호)
ex) Feat: 로그인 기능 구현 (#5)

FE
커밋유형: 기능 설명 (#이슈번호)
ex) Feat: 로그인 기능 구현 (#5)
```
