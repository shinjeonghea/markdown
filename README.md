markdown 공부 주소1 : <https://gist.github.com/ihoneymon/652be052a0727ad59601>
</br>
markdonw 공부 주소2 : <https://gist.github.com/ninanung/6691b7d68a4c1b815c0cc85693929ca3>
</br>
마크다운 웹 에디터 : <https://dillinger.io/>   

This is an header
=================

This is an sub header
---------------------


# 글머리 (1~6까지 있음 그 이후는 적용 안됨)

### 블럭인용
> blockqute.
블럭인용을 통해 안에 다른 다크다운 요소 포함 가능 like this
>> '>'를 하나씩 추가하여 blockquote 분리 
>>> '>'를 하나씩 추가하면서 계속 만들어 본 결과 계속 분리하여 새로추가 하기 가능한 듯

### 숫자 리스트
일반 숫자와 숫자에 점을 붙인것은 다름   
1
1. 현재 1,1,3,2라고 기록했는데 실제로는1,2,3,4로 나온다.
1. 처음 숫자를 11로 바꾼경우 11,12,13,14로 나왔다.
3.
2.

### 순서없는 리스트
* "*" or "+" or "-" 입력
    * tab후 "*" or "+" or "-" 입력
        * tab 두번 후 "*" or "+" or "-" 입력
            * tab 두번 후 부터는 작은 네모로 고정인 듯
            * 또한 +,-,*은 혼합도 가능


This is a sample

    들여쓰기 : 한번 엔터 한 후 들여쓰기 하여 쓰면 이렇게 상자 안에 들어감(엔터 안하고 그냥 들여쓰기 하면 적용안됨)
    엔터 후 바로 다시써도 들여쓰기 되어있어서 안에 써짐
    
들여쓰기 풀면 다시 밖으로 나옴

### 수평선
`수평선(* * *, ***, *****, - - -, ---------------------------------------)`
* * *
*****
***
- - -
---------------------------------------

### 코드블럭     
    -> 네모난 상자안에 코드를 넣어 시각화한다고 생각하면 된다.   
    네가지 방식이 있다.   
    1.`<pre><code>{code}</code></pre>`   
    2.코드블럭코드("```") 을 이용하는 방법   
    3.'~~~'를 이용하는 방식     
    + ``를 사용할 경우에도 블럭이 생성, 플러스로 넣은 이유는 1번의 내용처럼 다른 블록과 다르게 더 찐하고 글자에 딱맞는 블록이 생기기 때문이다.   
    
### 링크
1. 참조링크 : [naver][id]

[id]: https://www.naver.com/
<pre><code>[naver][id]

[id]:https://www.naver.com/
</code></pre>

2. 외부링크 : [naver](https://www.naver.com/)
```
[naver](https://www.naver.com/)
```

3. 자동 연결 : <https://www.naver.com/>   
~~~
<htttps://naver.com>
~~~   


### 줄바꾸기   
-> 글의 마지막에 스페이스바를 3번친다.   
 
### 테이블

->안에 '----'안해주면 표로 인식 못함   
->안에 비워두면 표도 비워서 나옴다.
~~~ 
머리| 진하게 | 나옴 | 이렇게
---- | ---- | ---- | ----
이건 | 안에 | 내용 | 
~~~


머리글| 진하게 | 나옴 | 이렇게
---- | ---- | ---- | ----
이건 | 안에 | 내용 | 


### 세부목록 만들기
~~~
<details>
   <summary> 세부목록 </summary>

   * 우선순위의 개념에 큐를 도입한 자료구조
      - ㅇㅇㅇ
      
</details> 
~~~
<details>
   <summary> 세부목록 </summary>

   * 우선순위의 개념에 큐를 도입한 자료구조
      - ㅇㅇㅇ
      
</details>    
