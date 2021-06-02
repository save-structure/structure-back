# structure-back

## 0. 프로젝트 실행 방법

```javascript
node index.js
```

Youtube Data API, Geolocation API, OpenWeatherAPI KEY는 개인 키로 입력

 - musicController.js 

   ```javascript
    const geolocation = require ('google-geolocation') ({
           key: '키입력',
           timeout: 2000
         });
   ```

   ```javascript
   const helper = new OpenWeatherMapHelper(
     {
       APPID: '키입력',
       units: "imperial"
     }
   );
   ```

   ```javascript
   youTube.setKey('키입력');
   ```

   

## 1. 개발 주제

음악과 날씨, 음악과 기분의 상관 관계에 주목하여 시작된 프로젝트 입니다. 현재 날씨와 어울리는 음악 한 곡과 사용자의 기분에 어울리는 음악 한 곡, 하루에 총 두 곡을 추천해 주는 노래 추천 서비스 입니다.


<img width="724" alt="스크린샷 2021-06-02 오후 9 37 17" src="https://user-images.githubusercontent.com/62235737/120486959-7e17fa00-c3f0-11eb-8ab5-91541a7771fe.png">


## 2. 개발 내용

- 2.1 내 위치를 기반으로 한 날씨 조회
- 2.2. 오늘의 날씨 정보를 바탕으로 음악 추천
- 2.3. 입력한 기분 저장 + 입력한 기분을 바탕으로 추천 음악 조회 [Youtube API 연동]
- 2.4. 날씨별 + 기분별 음악 정보 조회 [캘린더 팝업 화면]
- 2.5. 월별 기분별 통계 + 전체 기분별 통계
- 2.6. 플레이리스트



## 3. 각 기능 별 결과 화면 [영상] 

[[https://www.youtube.com/watch?v=fbOTWOqcsTk]](https://www.youtube.com/watch?v=fbOTWOqcsTk)


## 4. API 개발 명세서

![image](https://user-images.githubusercontent.com/62235737/117556327-8fe0d880-b0a2-11eb-909b-3571d8d7de8e.png)

진행상황 공유 : https://docs.google.com/spreadsheets/d/103wMBEkcPCmpo1utDZukKNsqYeI18PT2IPr2tM2VY2k/edit?usp=sharing

## 5. 사용 스택
### Server
- AWS(EC2, RDS)
- Linux
- Nginx

### Language
- Node.js

### Framework
- Express.js

### Database
- MySQL


## 6. 라이센스

### Artistic License

- 펄 언어 래리 월이 표준 펄 기능을 위해 만든 라이선스.

- NPM (Node Package Manager) (v2.0)

### Berkeley Software Distribution(BSD) License

- 버클리 캘리포니아대학 배포 공개 SW 라이선스

- Nginx



## 7. 도움을 준 사람
작성자 : [김민지](https://github.com/save-structure/structure-back)

### 프론트 
[김조현](https://github.com/save-structure/structure-front)
[한보은](https://github.com/save-structure/structure-front)





