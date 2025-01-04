##  도시락 (DOSI:RAK) 🍴
지구를 위해 '용기'내! 다회용기 사용장려 어플리케이션 
> 🏆 2024 제 13회 피우다 프로젝트 장려상 수상작

![piuda_main](https://github.com/user-attachments/assets/0bed80b9-aa8c-4029-ab57-fb10e656c8ab)

1. [**서비스 소개**](#1)

2. [**기술 스택**](#2)

3. [**주요 기능**](#3)

4. [**부가 기능**](#4)

5. [**프로젝트 구성도**](#5)
  
6. [**팀원 소개**](#6)

7. [**레포지토리**](#7)

<hr/>

<div id="1"></div>

### 1. 📌 서비스 소개

#### ⌚️ 개발기간
` 2024.10.09 ` → `2024.12.06`

#### 🌏 지구 지킬 용기, 도시락 (DOSI:RAK) 
>  DOSI:RAK은 사용자가 **다회용기 사용을 간편하게 인증하고 이를 통해 부여받는 리워드를 통해 환경 보호를 실천할 수 있도록 돕는 인공지능 기반 친환경 애플리케이션**으로
게임화 요소를 포함해 즐거움을 더하고 다양한 네트워킹 기능을 통해 누구나 쉽게 환경 보호 활동에 동참할 수 있는 기회를 제공합니다. </br>
저희 **팀 GPU**는 DOSI:RAK 어플리케이션 개발을 통해 다회용기 사용 문화를 확산시키는 것을 목표로 합니다.  
<!--①②③④⑤⑥⑦⑧⑨⑩-->

<hr></hr>

<div id="2"></div>

### 2. 🛠 기술 스택

<table>
  <tr>
    <td align="center" width="180"><strong>mobile 기술 스택</strong></td>
    <td>
      <div>
        <img src="https://img.shields.io/badge/xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white"> 
        <img src="https://img.shields.io/badge/swift-F05138?style=for-the-badge&logo=swift&logoColor=white"> 
      </div>
    </td>
  </tr>
  <tr>
    <td align="center" width="180"><strong>Back-end 기술 스택</strong></td>
    <td>
        <img src="https://img.shields.io/badge/springboot-green?style=for-the-badge&logo=springboot&logoColor=white">
        <img src="https://img.shields.io/badge/spring JPA-green?style=for-the-badge&logo=hibernate&logoColor=white">
        <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&style=for-the-badge&logoColor=white">
    </td>
  </tr>
  <tr>
    <td align="center" width="180"><strong>Server 기술 스택</strong></td>
    <td>
        <img src="https://img.shields.io/badge/NGINX-009639?&logo=nginx&style=for-the-badge&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?&logo=docker&style=for-the-badge&logoColor=white"/>
        <img src="https://img.shields.io/badge/Amazone RDS-527FFF?logo=amazonrds&style=for-the-badge&logoColor=white">
      <img src="https://img.shields.io/badge/letsencrypt-003A70?logo=letsencrypt&style=for-the-badge&logoColor=white">
  </tr>
  <tr>
    <td align="center"><strong>배포</strong></td>
    <td>
      <a href="https://newjeaps.com" target="_blank">
      </a>
    </td>
  </tr>
<table>

<hr></hr>

<div id="3"></div>

### 3. 🚀 주요기능

<table>
  <thead>
    <tr>
      <th align="center">기능이름</th>
      <th align="center">기능설명</th>
      <th colspan="2" align="center">screenshots</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>① GREEN GUIDE</strong></td>
      <td align="center">
        <strong> <em> 나도 다회용기 포장 실천해보고 싶은데...</br>가게에서 싫어하면 어떡하지?</em></strong></br></br>
        DOSI:RAK 의 GREEN GUIDE는 지도기반으로 다회용기 포장을 지원하는 내 주변 '제로식당' 정보와 다회용기 포장 할인
        혜택 정보를 제공합니다.다회용기 포장이 원활할 수 있도록 메뉴 별 '1인분 기준' 다회용기 추천 용량 정보도 제공해 드립니다.
      </td>
      <td><img src="./screenshots/greenguide-1-resize.gif" alt="GreenGuide GIF" width="250" /></td>
      <td><img src="./screenshots/greenguide-2-resize.gif" alt="GreenGuide GIF" width="250" /></td>
    </tr>
    <tr>
      <td align="center"><strong>② GREEN CLUB</strong></td>
      <td align="center">
        <strong> <em> 음식물 쓰레기를 줄일 수 있도록 </br> 마감세일을 하는 가게 정보를 제공합니다. </em></strong></br></br>
        제시간에 판매되지 못하고 폐기되는 음식물이 줄 수 있도록, 마감임박세일을 제공하는 가게의 정보를 제공합니다.
        할인율, 마감할인 시간, 나와의 거리 등의 정보를 제공합니다. 
      </td>
      <td><img src="./screenshots/greenclub-resize.gif" alt="GreenClub GIF" width="250" /></td>
      <td></td>
    </tr>
    <tr>
      <td align="center"><strong>③ GREEN AUTH</strong></td>
      <td align="center">
        <strong> <em> '용기내 챌린지' 제대로 해볼까요? </br> 당신의 다회용기 사용을 인증해드립니다. </em></strong></br></br>
        다회용기 포장사진을 찍어서 어플에 업로드만 해주시면, 인공지능을 활용해 다회용기 사용여부를 인증해드립니다!
        이를 통해 리워드도 얻고, green commit에 활동기록을 남길 수 있습니다.
      </td>
      <td><img src="./screenshots/greenauth-1-resize.gif" alt="GreenAuth GIF" width="250" /></td>
      <td><img src="./screenshots/greenauth-2-resize.gif" alt="GreenAuth GIF" width="250" /></td>
    </tr>
    <tr>
      <td align="center"><strong>④ GREEN TRACK</strong></td>
      <td align="center">
        <strong> <em> 다회용기 포장까지 가는 여정도 </br> 탄소배출량을 줄일 수 있도록.. </em></strong></br></br>
        다회용기 포장가게 까지 가는길도 도보나 따릉이를 이용해보는건 어떨까요?
        원하는 다회용기 가게를 선택하면, 가까운 순으로 따릉이 보관소까지의 시간/거리를 보여드립니다.
        더불어 `측정하기`를 누르시면 사용자의 이동을 추적하고 거리를 기반으로 리워드를 제공합니다.
      </td>
      <td><img src="./screenshots/greentrack-8x.gif" alt="GreenTrack GIF" width="250" /></td>
      <td></td>
    </tr>
  </tbody>
</table>

<!--①②③④⑤⑥⑦⑧⑨⑩-->

<div id="4"></div>

###  4. 💡 부가기능

<table>
  <thead>
    <tr>
      <th align="center">기능이름</th>
      <th align="center">기능설명</th>
      <th colspan="2" align="center">screenshots</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong> ⑤ GREEN TALK </strong></td>
      <td align="center">
        <strong> <em> 환경을 생각하는 사람들과 친해지면 </br> 함께 다양한 환경활동을 할 수 있을텐데... </em></strong></br></br>
        그리너스(GREENERS)끼리 함께 하면 좋잖아요? 
        그리너스가 모일 수 있도록 지역기반 채팅기능을 제공합니다.
        다회용기 사용인증을 통해 얻은 리워드 기반으로 내 위치 근방 채팅방에 참여하거나, 채팅방을 직접 생성할 수 있습니다. 
      </td>
      <td><img src="./screenshots/greentalk-1.gif" alt="GreenTalk GIF" width="250" /></td>
      <td><img src="./screenshots/greentalk-2.gif" alt="GreenTalk GIF" width="250" /></td>
    </tr>
    <tr>
      <td align="center"><strong>⑥ GREEN COMMIT</strong></td>
      <td align="center">
        <strong> <em> 나의 환경활동 자랑하고 </br> 친구들에게도 이 어플을 소개하고 싶어 !! </em></strong></br></br>
        나의 다회용기 포장실천활동 자랑해보야요
        그리너스의 활동들이 매일 달력형태의 GREEN COMMIT에 기록됩니다.
        날마다 환경활동을 실천하고 기록해보아요! SNS 공유를 통한 자랑은 덤 +
      </td>
      <td><img src="./screenshots/greencommit-resize.gif" alt="GreenCommit GIF" width="250" /></td>
      <td></td>
    </tr>
    <tr>
      <td align="center"><strong> ⑦ GREEN HEROES </strong></td>
      <td align="center">
        <strong> <em> 환경 활동으로 리워드를 쌓고 </br> 매달 순위에 도전하세요! </em></strong></br></br>
        `GREEN AUTH` 와 `GREEN TRACK`으로 얻은 리워드들을 기반으로 매달 순위가 매겨집니다.
        우리함께 `GREEN HEROES`로 설정될 수 있도록 환경활동을 실천해보아요!
      </td>
      <td><img src="./screenshots/greenheroes-resize.gif" alt="GreenHeroes GIF" width="250" /></td>
      <td></td>
    </tr>
    <tr>
      <td align="center"><strong> ⑧ GREEN ELITE </strong></td>
      <td align="center">
        <strong> <em> 당신이 환경지식을 함양할 수 있도록 - </em></strong></br></br>
        사람들이 헷갈려하는 환경문제를 수집하여 O/X 형태로 제공합니다.
        지속적인 어플 사용을 위해, 하루에 한문제씩만 풀 수 있도록 구현하였습니다.
      </td>
      <td><img src="./screenshots/greenelite-1-resize.gif" alt="GreenElite GIF" width="250" /></td>
      <td><img src="./screenshots/greenelite-2-resize.gif" alt="GreenElite GIF" width="250" /></td>
    </tr>
  </tbody>
</table>

<hr></hr>

<div id="6"></div> 

### 👩‍💻 팀원소개

|[박해인](https://github.com/femmefatalehaein)|[정재현](https://github.com/hyeonjaez)|[이유진](https://github.com/yyujin1231)|[권민재](https://github.com/gomminjae)|
|:---:|:---:|:---:|:---:|
| <img src="https://avatars.githubusercontent.com/u/75514808?v=4" width="100">  | <img src="https://avatars.githubusercontent.com/u/50399586?v=4" width="100">|<img src="https://avatars.githubusercontent.com/u/118620724?v=4" width="100">|<img src="https://avatars.githubusercontent.com/u/48856104?v=4" width="100">|
|Lead, BACKEND| BACKEND | BACKEND | iOS |

<hr></hr>

<div id="7"></div>

### 📦 레포지토리

- 🔗 mobile repository  [바로가기](https://github.com/DOSI-RAK/dosirak-ios)
- 🔗 bakcend repository  [바로가기](https://github.com/DOSI-RAK/dosirak-be)

<hr></hr>

