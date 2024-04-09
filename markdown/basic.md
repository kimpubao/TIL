# Markdown Basic
markdown은 .md 확장자로 생성한다.


## Heading(제목)
제목은 #으로 시작하며, 한칸 띄고 작성한다.

총 6단계로 하위 제목을 분류할 수 있다.

편의상 H1 ~ H6로 지칭하며, #의 개수로 구분한다. 

#H1(대제목)
## H2(하위 제목)
## H3
### H4
#### H5
##### H6


##Paragrap(문단/내용)
글은 보통 쓰듯이 쓰면 된다.
하지만 엔터를 항ㄴ번 치면, 줄바꿈이 되지 않는다. 알을 길게 하면 어느 순간 알아서 내려간다.

엔터 두번 쳐야, 실 문단 구분이 일어난다.

## 가로선
하이폰(-) 3개를 연속핵서 작성시, 구분건 생성

---

## List(목록)
### Ordered List(순서 있는 목록)
1. 손 씻기
   1. 물로 적시기
   2. 비누칠하기
   3. 헹구기
2. 밥 차리기
    - 밥
    - 국
    - 반찬
3. 먹기
4. 치우기
5. 양치

## Unordered List(순서없는 목록)
- 한식
- 중식
  - 짜장
  - 짬봉
  - 볶음밥
- 분식
- 일식
  - 돈까스
  - 소바
  - 카레
    - 비프카레
    - 포크카레
    - 버섯카레

## 내용 강조

중요한 것은 **굵게 표시**하고, 주의할 것은 *기울이고*, `코드나 명령`는 따로 표시하고 ~~취소선~~도 만들 수 있다.
심지어 수식 $x + y$도 가능
- Bold:*두개
- Italic:*한개
- -Code:`한개
- Canle:~두개
- $math$: $한개

## 블럭 강조

## Table(표)

|id|name|age|location|major|
|---|---|---|---|---|
|1|김김김|20|`서울`|기계|
|2|***이이이***|25|부산|국문|
|3|박박박|28|대전|기계|
|4|유유유|30|광주|신방|

## Code Block(코드블럭)
백틱 3개로 김씨면 코드 블럭이 생성 된다.
처음에는 사용하는 언어를 명시하면, 문법 강조도 됨!

```
$cd~
$mkdir aaa
$cd aaa
$touch a.txt
$rm a.txt
```

```python
def function(x,y):
    return x+y

function(1,2)
```

```sql
SELECT*FORM users:

```

## Math Block(수식블럭)
`$` 두개로 감싸서 블럭 생성
Latex(레이텍) 전문 펴기법 학습 필요.
$$
\mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \}
$$

## 기타
### Quote(인용문)
부등호 `>` 로 시작.
> 일단 유명해져라.
> 
> 그러면 사람들이 박수를 쳐줄 것이다


### 이미지 / 하이퍼 링크
```
링크
[표시텍스트](링크 URL)

이미지
![대체텍스트](링크URL)
```

링크 : [Google](https://google.com)

외부 이미지 : ![이쁜 사진](https://cdn.travie.com/news/photo/first/201710/img_19975_1.jpg)

내부이미지 : ![내사랑 하나](./내%20사랑%20하나.jpeg)