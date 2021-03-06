# 💡2학년 1학기 사물인터넷💡


### 1주차
------------
아두이노 프로젝트를 기획해보기


### 2주차
------------
아두이노 웹에디터 계정 생성하기 <https://create.arduino.cc/>


### 3주차
------------
> blink 예제에서 value 변수는 전역으로 선언되어져 있다. <br>
  이 변수는 loop 함수에서 사용되므로 만약 loop 함수 안에 선언하게 되면 어떻게 될까?

> LED는 13번 GPIO에 연결되어있다. 10번 GPIO로 변경하고 싶다면 어떻게 코드를 수정해야 하는가?

> "Hello Arduino"라는 문자열을 시작할 때 한번만 출력하고 싶다. <br>
   Serial.begin과 Serial.print문을 어디서 추가해야 될까?


### 4주차
------------
첨부된 회로를 브레드 보드에 그리기
> LED 3개 연결


### 5주차
------------
* 디지털 출력을 위한 함수는 무엇인가?

* 아두이노는 3가지 통신을 지원한다. 이름을 쓰시오.

* 아날로그 출력 핀과 아날로그 입력 핀을 쓰시오.


### 6주차
------------
결선도를 회로도로 그리기


### 7주차
------------
첨부 파일의 BLANK1, 2, 3을 채워 코드를 완성하시오.
> 3개의 LED가 1초의 한개씩 돌아가면서 켜지게 한다.


### 8주차 
------------
첨부된 코드의 결선도를 그려서 제출하시오.

~~~
void setup()
{
  pinMode(3,OUTPUT);
}

void loop()
{
  int lp;
  
  for(lp=0; lp<256; lp++)
  {
    analogWrite(3, lp);
  }
}
~~~


### 9주차
------------
코드와 결선도를 제출하시오.
> 4번 핀에 스위치를 연결하고 스위치를 누르면 모터의 방향이 바뀔 수 있게 한다. 


### 10주차 
------------
온도, 습도 센서에 두 개의 LED를 연결하고 표현해보기. <br>
> 온도가 20도에서 23도이고 습도가 20%에서 25%일 경우 녹색 LED를 켜고 그렇지 않을 경우 적색 LED를 켜지게 한다.


### 11주차
------------
C-LCD의 코드를 학번과 이름이 나오도록 하여 제출하시오.


### 12주차
------------
서보 모터에 스위치를 연결하여 회전 축의 각도를 조절해 보시오.
> GPIO 9번에 서보모터, GPIO 8번에 스위치를 연결하고 <br> 
  스위치를 누르면 90도 위치로 이동하고 스위치를 때면 원래 위치로 이동하도록 한다.
  


### 13주차
-------------
부저를 사용하여 '나비야 나비야'를 재생하시오.


### 중간고사
-------------
코드와 결선도를 제출하시오.
> SW1을 누르면 녹색 LED를 켜고 "반짝 반짝 작은별" 멜로디를 재생하고 <br>
  SW2를 누르면 노란색 LED를 며고 "나비야 나비야" 멜로디를 재생한다.


### 기말고사
-------------
* I2C 통신에 대해서 간단하게 설명하시오.
* ADC에 대해서 간단하게 설명하시오.
* 폴업 저항과 폴다운 저항의 차이점을 설명하시오.
* (코드와 결선도 참고) 위의 코드에서 map 함수를 사용한 이유를 쓰시오.
* (코드와 결선도 참고) LED를 제어하기 위해 PWM 핀을 사용하고 있다. 그 이유를 쓰시오.




