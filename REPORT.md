# A1 리포트

- 이름:조예원
- 학번:2025402051
- GitHub ID:jjjs0404-lab

## 어디를 둘러봤는지

열어본 awesome-nodejs 카테고리, 터미널에서 써본 검색어, 링크를 따라간 경로 등을 적습니다.

korean 관련 패키지들을 찾고싶어서 korean hangul을 검색했고, 그 중 가장 재미있어 보이는 패키지를 선정했다. 또 패키지들을 둘러보다가 random-int 항목도 재미있어 보여 추가했고, 다른 random과 관련된 항목들도 알아보고 싶어 Keywords에서 random을 클릭하여 다른 패키지들을 탐색했다.

---

## 선정한 패키지

### 1. `korean-unpacker`

**선정 이유:**
unpacker라고 해서 한글을 어떻게 unpack할 수 있는지 궁금해서 살펴봤다. 한 글자 한 글자 분리되는 것이 아니라 자음과 모음이 분리된다고 하기에 신기해서 선정하였다.

**이것으로 무엇을 할 수 있을지:**
단어나 문장으로 되어있는 한글들을 모음과 자음 단위로 쪼개서 볼 수 있다. 의미적 분석이 아닌 한글 그 자체에 대한 분석에서 용이하게 사용될 것 같다. 어떠한 글에서 가장 많이 사용되는 모음이라거나, 가장 많이 사용되는 자음같은 것들을 알아볼 수 있을 것이다.

**확인 결과:**

```
$ npm view korean-unpacker version time.modified license dependencies
version = '1.0.3'
time.modified = '2023-12-22T06:56:57.893Z'
license = 'MIT'

$ npm view korean-unpacker deprecated

```

**출력을 보고 알게 된 것:**
time.modified가 2023년인 것을 보아 한 가지 기능만 하는 작은 패키지라서 완성 후 수정되지 않은 것 같다.
---

### 2. `random-int`

**선정 이유:**
지금까지 프로그래밍을 할 때에는 random 숫자를 얻기 위해 time과 같은 툴들을 사용했어야 했는데 이 패키지를 사용하면 보다 간편하게 random 숫자를 생성할 수 있을 것 같았다.

**이것으로 무엇을 할 수 있을지:**
주사위를 굴린다든가, 아니면 벌칙을 수행할 사람의 번호를 뽑는다든가 하는 방식으로 사용할 수 있을 것 같다. 프로그램을 만들지 않더라도 간단하게 노트북을 켜서 random 숫자를 뽑을 때 사용할 수 있을 것 같다.

**확인 결과:**

```
$ npm view random-int version time.modified license dependencies
version = '3.1.0'
time.modified = '2025-09-15T12:06:44.280Z'
license = 'MIT'

$ npm view random-int deprecated


```

**출력을 보고 알게 된 것:**
이또한 매우 간단해 보이는 패키지라서 version 첫 자리가 1일 줄 알았는데, 3인 것을 보아하니 수정을 몇 번 거치긴 한 것 같다. 간단해 보이는 것과는 별개로 코드는 엄청나게 간단하진 않은가보다.
---

### 3. `nanoid`

**선정 이유:**
random키워드로 들어가서 이번주 다운로드 순으로 정렬했을 때 가장 상단에 위치하고 있어서 어떤 패키지이기에 사람들이 애용하는지 궁금해서 선정하였다.

**이것으로 무엇을 할 수 있을지:**
짧은 uuid를 생성하는 패키지이다. 간단하게 url을 만들 일이 있을 때 이 패키지를 사용하여 많은 고민 없이 생성할 수 있을 것 같다. 

**확인 결과:**

```
$  npm view nanoid version time.modified license dependencies
version = '6.0.1'
time.modified = '2026-09-10T18:00:48.371Z'
license = 'MIT'

$ npm view nanoid deprecated

```

**출력을 보고 알게 된 것:**
$ npm view nanoid deprecated가 빈 것으로 보아 지원이 중단되지는 않은 것 같다. 다운로드 수가 가장 많다고 해서 당연히 완성도가 매우 높은 패키지일 줄 알았는데 version이 0으로 시작하는 것을 보고 아니라는 것을 알았다. 이번주 다운로드 순위가 높은 것이었으니 출시된 지 얼마 되지 않아 많은 관심을 얻고 있는 패키지인 듯 하다.
---

## 설치해본 패키지

```
$ npm install korean-unpacker

$ node try.js

```
ㅇㅏㄴㄴㅕㅇ
ㄱㄱㅏㅊㅣ
---

## 막혔던 부분 (채점하지 않음)

에러 메시지든 헷갈렸던 부분이든 하나. 두 문장이면 됩니다. 없었으면 없었다고 적습니다.

```
없었다.
```

---

## AI 사용

사용했다면 프롬프트와, AI의 설명이 실제와 달랐던 부분을 적습니다.
사용하지 않았다면 "사용하지 않음"이라고만 적으면 됩니다.

사용하지 않음
---

## 제출 전 확인

- [ ] 저장소 이름이 `oss2026-a1`, 공개 범위가 Public
- [ ] `git status` 결과가 `nothing to commit, working tree clean`
- [ ] `node_modules` 폴더를 지우고 `npm install` → `node try.js` 를 다시 해도 실행됨
- [ ] 마지막 커밋을 push함
