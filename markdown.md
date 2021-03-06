# 마크다운 문법

## 제목(heading)

문서의 구조를 잡기 위한 제목은 #을 통해 표현한다.

#의 갯수로 제목의 레벨을 지정한다.

### 제목3

#### 제목4

##### 제목5

###### 제목6

## 목록(list)

목록은 순서가 있는 목록과 순서가 없는 목록으로 구분된다.

1. 목록1
2. 목록2
   1. 목록 2-1 (tab)
   2. 목록 2-2 
3.  shift + tab
   * 순서가 없는 목록
   * 순서가 없음
     * tab하면 하위로
   * shift + tab

## 코드 블록

코드를 작성할때 코드 블록을 활용하면, 언어별 syntax highlighting 기능이 제공됨



(``` 언어)

``` python
print("hello!") # 'hello!' 출력

# 짝수 판별 조건식

num = 10
if num % 2 == 0:
    print('짝수')

 
```

```html
<!-- Html 주석 -->
<h1>
    안녕하세요
</h1>
```

``` bash
& git init
```

### 인라인 코드블록

`if`는 파이썬 조건문에서 활용되는 키워드 입니다.

## 표

| 이름   | 나이 | 비고 |
| ------ | ---- | ---- |
| 홍길동 | 100  |      |
| 김철수 | 40   |      |
| 최영희 | 20   |      |

## 이미지

![1212DD1D4AF7F51885](C:\Users\jh367\Desktop\2019 AI 공모전\1212DD1D4AF7F51885.jpg)

* typora 에 아래와 같이 설정하면, 상대 경로로 쉽게 이미지 파일관리를 할수 있다.

## 링크

[구글](https://google.com)

## 인용문

> 인용문은 >를 통해 만듭니다. 

## 기타

**굵게(볼드체)**

*기울임(이탤릭체)*

~~취소선~~ (~~ 물결표 두개)

