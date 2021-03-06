# IoT 프로젝트 - 스마트 도어락 시스템
 - [웹, 서비스](./SmartDoorLock-WebApplication) : 관리자 페이지 이며 앱보다 더 넓은 관리기능 제공 (Spring Framework, JSP)
 - [앱](./SmartDoorLock-HybridApplication) : 실제 도어락을 여는 주체이며 웹보다 적은 관리기능을 제공한다. (Cordova, HTML5, CSS3, jQuery)
 - [하드웨어](./SmartDoorLock-Arduino) : 블루투스 모듈과 Wi-Fi모듈을 이용한 하드웨어 도어락 (Arduino, C)
 - [배치 프로세스](./SmartDoorLock-LogAnalyzers) : 서비스에 발생된 로그를 분석하여 서비스 이용자에게 그래프를 제공한다. (Java)

<br/>

## 시스템 소개

 - 블루투스로 도어락의 문을 열고 닫으며, 인터넷으로 도어락의 열쇠들을 관리한다.
 - 사용자에게는 앱과 웹 서비스가 제공된다.
 - 앱은 도어락을 제어하는 매개체이며, 관리의 기능이 일부 포함되어있다.
 - 웹은 앱보다 더 넓은 의미의 관리 기능을 제공한다.
 - 도어락은 스마트폰의 블루투스로 제어된다.
 - 배치프로세스는 앱,웹,도어락 서비스 이용에 발생되면서 생긴 로그를 분석하는 프로세스이다. 

<br/>

## 시연 동영상

**이 서비스가 어떤 것인지 이해할 수 있도록 영상을 만들었습니다. <br/> 지나치지 마시고 꼭 봐주세요. 부탁드립니다.!!!**

[![Youtube 영상](https://img.youtube.com/vi/J4H5Q9bNlK4/0.jpg)](https://www.youtube.com/embed/J4H5Q9bNlK4)

<br/>

## 구성 요소 UI

![main](./img/main.png)
![img01](./img/img01.png)
![img03](./img/img03.png)
![app](./img/app.png)
![HW](./img/Hardware.png)

<br/>

## 시스템 구성도

![architecture of system](https://github.com/yung6699/SmartDoorLock/raw/master/docs/images/architecture.png)

<br/>

## 시스템 기능도

![functions of system](https://github.com/yung6699/SmartDoorLock/raw/master/docs/images/functions.png)

<br/>

## 프로젝트 산출문서
 
 - [제안설계서.pdf](https://github.com/yung6699/SmartDoorLock/raw/master/docs/%EC%A0%9C%EC%95%88%EC%84%A4%EA%B3%84%EC%84%9C.pdf)
 - [설계서(간소화).pdf](https://github.com/yung6699/SmartDoorLock/raw/master/docs/%EC%84%A4%EA%B3%84%EC%84%9C_%EA%B0%84%EC%86%8C%ED%99%94.pdf) 
 - [완료보고서.pdf](https://github.com/yung6699/SmartDoorLock/raw/master/docs/%EC%99%84%EB%A3%8C%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)
 - Trello [프로젝트 현황](https://trello.com/b/JC3rUHSw/-)
 - Trello [이슈 관리](https://trello.com/b/yQseIG1l/smartlock)

<br/>

## 참여자
 - [윤태영](https://github.com/yung6699)
 - [조용진](https://github.com/drake-jin)
 - [진영균](https://github.com/ywnwalone)
 - 황대건

<br/>

## 한이음 공모전
- [2016 한이음 공모전](./hanium2016)    

