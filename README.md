# JavaScript_coding-apple

<hr>
[1. 2020-12-06 js 기본](#1. 2020-12-06)
<hr>

## 1. 2020-12-06

요약 : Brackets 에디터 설치, 웹, html, css 등 간단한 배경설명, js 기본문법

1. js의 존재이유: 
    <strong>html의 요소 변경</strong>, 웹 ui요소 개발, 서버데이터 전송 및 수신
    
2. 코드를 구성하는 방법:
    가능한 상세히, 정확히 설명

3. document.getElementById('[1]').[2]=[3];
    [1] 바꾸자하는 element의 id
    [2] 바꾸자하는 element의 type
    [3] 바꾸는 값

4. ui 만드는 법:
    1) 미리 html, css로 만들어놓고 숨김
    2) 버튼을 눌렀을 때 보여줌
    3) 닫기버튼 누르면 숨김
    eg) onclick="document.getElementById('[1]').style.display='none';" -> 숨김
        onclick="document.getElementById('login').style.display='block';" -> 보여줌

5. function [name]([parameter]){} 
    1) 긴 코드 축약
    2) parameter를 이용할 수 있음
    
6. document.getElementById('[1]').addEventListener('[2]',[3])
    [1] element의 id
    [2] 발동 조건 eg) click, mouseoser, scroll, ...
    [3] 실행 함수

7. 변수 : 선언, 할당, 변수가 쓰여지는 범위
    1) var [name] = [value]; // 재선언 o, 재할당 o, function(){}
    2) let [name] = [value]; // 재선언 x, 재할당 o, {}
    3) const [name] = [value]; // 재선언 x, 재할당 x, {}
    eg) function(){
            var age=30;
        }
        //age 사용불가

8. 함수의 return
 
9. if문 : 조건에 따라 실행하는 코드
  1) == : 값을 비교함
  2) === : 엄격한 비교 - data의 type까지 비교함