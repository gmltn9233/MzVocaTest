# MzVocaTest
MZ를 위한 어휘력 고사 웹 사이트
> **어휘력 테스트** 웹 사이트
> 나의 **어휘력**과 **MZ 용어**에 대한 이해를 테스트할 수 있으며  
> **랭킹 조회**를 통해 **오답률**이 높은 단어에 대해서 확인할 수 있습니다!

## 실행화면
<div align="center">
  <img src="https://github.com/gmltn9233/MzVocaTest/assets/63588364/5837fcc6-3360-4f13-8c2a-b48727c38bc6 " width="40%" height="40%">
  <img src="https://github.com/gmltn9233/MzVocaTest/assets/63588364/f55076eb-aad2-4b2c-b836-01de8aee50b9" width="40%" height="40%">
</div>
<div align="center">
  <img src="https://github.com/gmltn9233/MzVocaTest/assets/63588364/4b3ab82d-ed89-44f6-b022-ff66506bf377" width="40%" height="40%">
  <img src="https://github.com/gmltn9233/MzVocaTest/assets/63588364/e620d5bf-cfeb-4408-8c63-bffac06c8f50" width="40%" height="40%">
</div>


## 팀원 소개
1. **조태현** (https://github.com/whxogus215)
2. **박유한** (https://github.com/LimitedPark)
3. **이희수** (https://github.com/gmltn9233)

## 서비스 기획 의도
- 흔히 MZ라고 불리는 **10대,20대의 어휘력 부족 문제**가 사회적으로 조명을 받으면서 해당 주제를 다루는 웹 서비스의 필요성을 느낌
- 오답률이 높은 단어들을 시각적으로 보여줌으로써 **어휘력 부족 문제에 대한 객관적인 지표**가 될 수 있음
- 현재 운영되는 여러 테스트 사이트들은 응답에 대한 결과만 보여주고, 전체 랭킹을 보여주지 않음
  - **전체 랭킹과 복습하기 기능**을 통해 웹 서비스가 줄 수 있는 **교육적인 측면**을 강화
- MZ 세대들에게 익숙한 **수능, 모의고사와 유사한 UI**를 제공함으로써 보다 친숙하고 경험을 제공

## 개발 자료
<details>
<summary>코드 컨벤션</summary>
  
## 코드 컨벤션
  
🐪 **함수명, 변수명, 패키지명은 소문자 카멜케이스로 작성** : ex) `public void addItem(), String itemName`  

🐪 **클래스명, 생성자명은 대문자 카멜케이스로 작성** : ex) `ItemRepository`

❕ **상수명은 CONSTANT_CASE로 작성** : ex) `MAX_SIZE`

1. 메서드명은 동사, 혹은 동사구로 작성 : ex) `sendMessage(O) mesasage(x)`

2. 다른 변수와 상수들은 명사, 혹은 명사구로 작성 : ex) `makeResult(X) taskResult(O)`

- 하나의 메소드와 클래스는 하나의 목적만 수행하게 만드는 것을 권장 **(SRP 원칙 준수)**

❗ **메소드 컨벤션**

- 리소스 생성 `create()`
- 리소스 조회 `getXXX()`
- 리소스 목록 조회 `getList()`
- 리소스 수정 `update()`
- 리소스 삭제 `delete()`

❗ **기능단위 별로 주석 작성하기**
```java
// 아이템 항목 추가 메서드
void addItem(){
      ...
}
```

❗ **이항** **연산자 사이에는 공백을 추가**

```java
a+b+c+d // bad
a + b + c + d // good
```

❗ **콤마 다음에 값이 올 경우 공백을 추가**

```java
int[] arr = [1,2,3,4]; //bad
int[] arr = [1, 2, 3, 4]; //good
```
</details>

<details>
<summary>Git 컨벤션</summary>
  
## Git 컨벤션
  
https://velog.io/@archivvonjang/Git-Commit-Message-Convention  

해당 게시물을 참고하여 깃 메시지를 작성하도록 한다. 
  
</details>

<details>
<summary>Git 브랜치 컨벤션</summary>
  
## Git Branch 컨벤션
  
`이름/기능` 형식으로 브랜치 이름을 만든다. ex) `taehyeon/frontcss`
  
</details>
