---
layout: single
title: "[Markdown]기본 문법 개념정리"
---

# 마크다운 문법
## 1. Heading
- 크키별로 H1~H6까지 존재(H1이 제일 크고 H6가 제일 작다)

# H1 Test (#H1)
## H2 Test (##H2)
### H3 Test (### H3)
#### H4 Test (#### H4)
##### H5 Test (##### H5)
###### H6 Test (###### H6)

H1과 H2는 자동으로 밑줄이 생상된다.

## 2. Line
- ___을 이용하면 해당 위치에 밑줄을 그어줄 수 있다.


## 3. Quote
- 블럭인용문자 > 를 이용하여 원하는 문장을 qoute로 넣을 수 있다.

>Quote Test 1
>>Quote Test2
>>>Quote Test 3

기호 '>'를 하나씩 더 사용하여 중첩 quote를 만들 수 있다.


## 4. List
### 4-1. Bullet List
- '*' , '-' 를 이용하여 list를 표현할 수 있다.

* Bullet List Test1

### 4-2. Numbered List
- 앞에 1,2,3 숫자를 붙여서 순서가 있는 list를 표현할 수 있다.

1. Numbered List Test1
2. Numbered List Test2
3. Numbered List Test3

- 들여쓰기(공백 3칸)를 이용하여 중첩 list를 만들 수 있다.

1. List Test1
   - sub list test1
   - sub list test2
2. List Test2
    1. sub list test1
    2. sub list test2

## 5. Emphasis
- 별('*') 하나로 감싸면 italic으로 만들 수 있다.

> *Italic Test*

- 별('*') 두개로 감싸면 bold로 만들 수 있다.

> **Bold Test**

- 물결 모양('~') 두개로 감싸면 strikethrough로 만들 수 있다.

> ~~Strikethrough Test~~

## 6. Table
### 6-1. Table 생성
- table안의 내용과 '|'를 이용해 만들 수 있다.

```
|제목|내용|기타|
|--|--|--|
|title1|content1|etc1|
|title2|content2|etc2|
|title3|content3|etc3|
```

|제목|내용|기타|
|--|--|--|
|title1|content1|etc1|
|title2|content2|etc2|
|title3|content3|etc3|

### 6-2. Table 정렬
- table내부의 '|--|'사이에 ':'를 추가하여 정렬할 수 있다
   1. 우측정렬 '|'내부의 우측에 ':'를 추가
   2. 좌측정렬 '|'내부의 좌측에 ':'를 추가
   3. 중앙정렬 '|'내부의 양쪽 모두 ':'를 추가


```
|제목|내용|기타|
|:----|:----:|----:|
|title1|content1|etc1|
|title2|content2|etc2|
|title3|content3|etc3|
```

|제목|내용|기타|
|:----|:----:|----:|
|title1|content1|etc1|
|title2|content2|etc2|
|title3|content3|etc3|

### 6-3 Table 셀 확장/강조
- '|' 사이를 비우고 다음 셀을 작성하면 자동으로 셀이 확장된다.
- 일반적인 text와 마찬가지로(title 5.Emphasis) 강조할 수 있다.

## 7, Code Emphasis(코드 강조)
### 7-1. Inline code
- 코드의 시작과 끝에  `를 사용하여 코드부분을 따로 표현할 수 있다.

`System.out.println("Hello World!");`

### 7-2. Block code
- 코드가 여러줄일 경우 코드의 시작과 끝을 ```(`3개)로 감싸주면 코드부분 강조처리가 된다.

```
for(int i=1 ; i<10; i++){
   System.out.println("i")
}
```

## 8. Link

## 9. Image


