## 0. Commit message convetion

커밋  메시지 컨벤션은 협업 시 일관성을 유지하고 로그 추적을 용이하게 하기 위해 작성하는 메시지 양식을 말한다. 이것은 당연히 그룹마다 다르다. 하지만 일반적으로 사용되는 양식들은 존재하고 이번 포스팅에서는 Udacity에서 제시하는 [commit message style guide](https://udacity.github.io/git-styleguide/)를 다룬다. 앞으로 개인 프로젝트에서는 udacity의 컨벤션에 맞춰 커밋 히스토리를 남기고자 한다.

## 1. The Seven rules of a great git commit message

#### 1. Seperate subject from body with a body line
	body는 필수가 아니며 가능한 간결하게 subject 한 줄로 쓰는 것도 좋다.
#### 2. Limit the subject line to 50 characters
	최대 제한은 72자이나 50자 이내를 염두에 두고 작성한다.
	이는 가독성을 높이고 명확한 방식으로 표현하게끔 한다.
#### 3.Capitalize the subject line
#### 4. Do not end the subject line with a period
	subject는 항상 대문자로 시작하며 마침표를 찍지 않는다.
#### 5. Use the imprative mood in the subject line
	subject는 현재형 명령문으로 작성한다.
#### 6. Wrap the body at 72 characters
#### 7. Use the body to explain what and why vs. how
	어떻게 했냐 대신 무엇을 했고 왜 했는지를 body에 담는다.

## 2. Udacity Style

#### 1. Structure
```
type: Subject 

body 

footer
```
#### 2.  Commit Type
* feat : 기능 추가
* fix : 버그 수정
* docs : 문서 수정
* style : 코드 포맷팅이나 세미콜론 누락 교정 등 코드 수정이 없는 경우
* refactor : 리팩토링
* test : 테스트 코드 추가 혹은 리팩터링 등 프로덕션 코드의 수정이 없는 경우
* chore : 빌드 업무, 패키지 매니저 수정

#### 3.  footer

* 선택적으로 사용
* issue tracker id 

## 3.

아직 Udacity의 스타일을 따르되 아직 영어로 작성하는 것이 익숙치 않아 한글로 먼저 연습을 해보려고 한다. 추후 팀 프로젝트에도 Udacity style을 바탕으로 컨벤션을 정할 것을 제안할 것이다.

## References.

 [How to write a git commit message](https://cbea.ms/git-commit/)
 [Udacity git commit message style guide](https://udacity.github.io/git-styleguide/)
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDQzMjExNjk5XX0=
-->