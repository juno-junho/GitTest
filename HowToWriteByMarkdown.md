# Markdown 사용 연습

<!-- HEADING -->
# 1. Header 사용법
# This is H1
## This is H2
### This is H3
#### This is H4 
##### This is H5
###### This is H6
######### H6 이상은 지원하지 않는다..

---
# 2. BlockQuote 사용법
> This is a first block quote
> ## 이렇게 다른 마크 다운 요소 사용 가능
> >This is a second block quote
>> ### 이렇게
> >>this is a third block quote
>>> - 이렇게도 가능
> >>>이렇게 계속 들여쓰기 가능하다...


# 3. 목록
1. 첫번째
2. 두번재
3. 세번째

이렇게 목록 사용 가능
1. 첫번째
3. 세번째
2. 두번째
3. 뭐지
1. 이렇게 되네
12. 숫자는 상관 없는듯.


* 빨강
- 파랑
- * 녹색
- -  - 이건
- - - + 이건
---


# 4. 코드 적용
    이렇게 tab을 사용하면 변환되기 시작해 들여 쓰지 않는 행을 만날때 까지 변환이 계속된다.
이렇게

아니면 console에 메세지 출력을 위해 `console.log('my message');`처럼 사용할 수 있다.

## 코드블럭 사용 하는 방법
<pre><code>코드블럭 삽입</code></pre>
아니면
``` 
이렇게 backquote 사용해서 코드 블럭 실행
```
```java
public static void main(String[] args){
    System.out.println("Hello World!");
}
```
이렇게 문법 highlighting 또한 가능

글 중에 특정 `highlight`를 이렇게 줄 수도 있음.

# 5. 수평선
---
------------(3개 이상)
***
*************(3개 이상)

# 6. 링크
[link keyword][id]

[id]: https://www.google.com

link : [구글][googleLink]

[googleLink]: https://www.google.com

[Title](https://www.naver.com)

[Google](https://www.naver.com, "google link")

- 외부링크 : <https://www.google.com>
- 이메일 : <ssmm0205@naver.com>

# 7. 강조 기능
*single asterisks*

_single underscore_

**이렇게 하면 bold체**

__이렇게 해도 bold체__

문장 중간에 이용할 경우, ~~띄어쓰기~~를 사용하는 것이 좋다.

또는 <del>이렇게</del>나 <ins>이렇게</ins> 사용도 가능함.

==highlight==   
기능도 사용할 수 있다 (ghost에서만)
# 8. 이미지
![image description ](./githubpic.png "picture title")
사진 조절 기능은 

    <img width="" height=""></img>
를 이용한다.

<img src ="./githubpic.png" width = "200px" height="100px" title = "픽셀 크기 설정" alt="github">

# 9. 줄바꿈
 - 줄바꿈을 하기 위해서는 문장 마지막에서 3칸이상 띄어쓰기   
이렇게

# 10. Table
<!-- 오른쪽 정렬 왼쪽정렬 -->
|Header|Description|
|--:|:--:|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|
|Cell1|Cell2|


# 11. Escapeing
\# 이렇게 escape key를 사용할 수 있다.    
\- 이렇게   
\*이렇게\*

<button class="button-save large">Big Fat Button</button>

# 12. Markdown Footnotes
(ghost에서만 가능)    
The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red

# 13. Github Flavored Markdown
```javascript
// public static void main {}
function fancyAlert(arg){
    if(arg){
        $.facebox({div:'#foo'});
    }
}
```

Task Lists     
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
