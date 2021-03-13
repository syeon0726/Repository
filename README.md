# GFM의  표준 Markdown에 대한 확장 부분 사용법
## *1. 테이블*

 + 용도</br>

표를 추가하기 위해 활용된다


+ 사용법</br>

세 개 이상의 하이픈( --- )을 사용하여 각 열의 제목 부분을 만들고 파이프문자( | )를 이용하여 열을 구분해준다.</br>
맨 왼쪽과 맨 오른쪽의 파이프문자는 추가 할 수도 있고 생략 할 수도 있다.

> **example ( 1 )**</br>

    | 이름 | 나이 |
    | --- | --- |
    | 황서현 | 21 |
    | 쿠로미 | 48 |
    
> 출력 결과</br>

  | 이름 | 나이 |
  | --- | --- |
  | 황서현 | 21 |
  | 쿠로미 | 48 |
  
> **example ( 2 )**</br>

     이름 | 나이 
     --- | --- 
     황서현 | 21 
     쿠로미 | 48 
    
> 출력 결과</br>

   이름 | 나이 
   --- | --- 
   황서현 | 21 
   쿠로미 | 48 
   
   ___
  
  
  
## *2. 작업 목록 항목*

 + 용도</br>


 작업 항목을 만들기 위해 사용된다.




+ 사용법</br>

작업 목록을 만들려면 일반 공백 문자 [ ]를 적은 후 뒤에 내용을 작성한다.</br>
작업을 완료했다면 공백문자 [ ] 안에 x표시를 작성해준다.

>  **example**</br>

    Today's plan
    
    1. [x] example sentence1
    2. [ ] example sentence2
    3. [ ] example sentence3
    
> 출력 결과</br>


  Today's plan
  
   1. [x] example sentence1
   2. [ ] example sentence2
   3. [ ] example sentence3
 
 ___
 
  
## *3. 취소선*
+ 사용법</br>

물결기호( ~ ) 2개로 텍스트를 감싸준다.

>  **example**</br>

    ~~example sentence1~~
    
> 출력 결과</br>

 ~~example sentence1~~

___


## *4. 자동 링크*
일반적인 URL 혹은 이메일 주소일 경우 적절한 형식으로 링크를 형성하도록 한다.
>  **example**</br>

    외부 링크 : <https://www.google.co.kr/>
    이메일 주소 : <hyk4648@naver.com>
    
> 출력 결과</br>

외부 링크 : <https://www.google.co.kr/> </br>
이메일 주소 : <hyk4648@naver.com>

___


## 5. 허용되지 않는 원시 HTML
GFM ( GitHub Flavored Markdown ) 은 tag filter를 확장시킨다. </br>
**example**의 표준 HTML tag를 렌더링 할 경우 GFM 방식으로 필터링 되어서 렌더링 된다.

>  **example**</br>

    <title>
    <textarea>
    <style>
    <xmp>
    <iframe>
    <noembed>
    <noframes>
    <script>
    <plaintext>
    



___
