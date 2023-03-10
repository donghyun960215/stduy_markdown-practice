# 제목(Herder)

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하늼이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
동해물과 백두산이 마르고 닳도록  
하늼이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세  
띄어쓰기 2번 하면 줄바꿈 처리된다.

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a herf="https://google.com">GOOGLE</a>  

[GOOGLE](https://google.com)

<a herf="https://naver.com" 
title="NAVER로 이동">NAVER</a>  

[NAVER](https://naver.com "NAVER로 이동!")

<a herf="https://naver.com" 
title="NAVER로 이동"
target="_blank">NAVER</a>  

# 이미지(Images)

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직적 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문1  
>>> 중중첩된 인용문2  
>>> 중중첩된 인용문3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a herf="https://naver.com" 
target="_blank">NAVER</a>  
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func(){
  var a = 'aaa';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)


동해물과 
<span style = "text-decoration: underline;">백두산</span>
이 마르고 닳도록</br>
하느님이 보우하사 우리나라 <u>만세</u>

<a herf="https://naver.com" 
title="NAVER로 이동"
target="_blank">NAVER</a>  

<img width="70" src = "https://heropy.blog/css/images/logo.png" 
alt = "HEROPY">

# 수평선(Horizontal Rule)

---

***

___

