---
title: "Markdown 연습"
excerpt: "Markdown 테스트"

categories:
  - Blog
tags:
  - Blog
  - Markdown
last_modified_at: 2021-01-22T16:01:00
toc: true
toc_sticky: true
toc_label: "목차"
---

## 1. 출처
* <https://devinlife.com/howto%20github%20pages/markdown-syntax/>  
* <https://theorydb.github.io/envops/2019/05/22/envops-blog-how-to-use-md/>  
* <https://gist.github.com/ihoneymon/652be052a0727ad59601>  

## 2. 텍스트 효과
줄바꿈은 라인 끝 스페이스 2번이다  
줄  
바  
꿈  

```markdown
*기울임*은 애스터리스크(*) 또는 언더바(_)를 강조 할 부분 양 옆에 한개씩,  
**볼드**는 애스터리스크(**) 또는 언더바(__)를 강조 할 부분 양 옆에 두개씩,  
<u>밑줄</u> 은 <u> 태그를,  
~~취소선~~은 물결표시 2개다.  
`기호로 `강조` 할 수 있다. 
```  
*기울임*은 애스터리스크(*) 또는 언더바(_)를 강조표시 할 부분 양 옆에 한개씩,  
**볼드**는 애스터리스크(**) 또는 언더바(__)를 강조표시 할 부분 양 옆에 두개씩,  
<u>밑줄</u> 은 \<u> 태그를,  
~~취소선~~은 물결표시 2개다.  
\`기호로 `강조` 할 수 있다. 


## 3. 인용문
```markdown
> 이거는 인용이다

> 여러개를
>> 쓰면
>>> 깊어진다
```

> 이거는 인용이다

> 여러개를
>> 쓰면
>>> 깊어진다

## 4. 번호달린 목록(Ordered List)
```markdown
1. 사과
2. 바나나
3. 귤
```
1. 사과
2. 바나나
3. 귤

## 5. 번호없는 목록(Unordered List)
별표(*), 더하기(+), 빼기(-) 기호를 사용한다.  
혼합 사용도 가능.
```markdown
* 감
  * 배
    * 사과
```
* 감
  * 배
    * 사과

## 6. 코드 인용
backtick(`) 기호 3개로 열고 닫는다.


```java
system.out.println("Hello World!");
```

```java
system.out.println("Hello World!");
```

## 7. 수평선
```markdown
* * *
***
*****
- - -
---------------------------------------
```
-------------------------

## 8. 링크
```markdown
[네이버](https://naver.com)
```
[네이버](https://naver.com)


```markdown
<https://naver.com>
```
<https://naver.com>

## 9. 이미지
```markdown
![](https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg)
```
![](https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg)

```markdown
![](https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg){: .align-center}
```
![](https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg){: .align-center}



```markdown
![강아지](https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg "강아지임"){: .align-center}
```
![강아지](https://i.ytimg.com/vi/MPV2METPeJU/maxresdefault.jpg "강아지임"){: .align-center}

## 10. 표
```markdown
| 메뉴 | 가격 | 개수 |
|:---:|:----:|:----|
| 떡볶이 | 3000원 | 2개 |
| 김밥 | 2500원 | 3개 |
```

| 메뉴 | 가격 | 개수 |
|:---:|:----:|:----|
| 떡볶이 | 3000원 | 2개 |
| 김밥 | 2500원 | 3개 |