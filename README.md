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



![img](img width="724" alt="스크린샷 2021-06-02 오후 9 37 17" src="https://user-images.githubusercontent.com/62235737/120486959-7e17fa00-c3f0-11eb-8ab5-91541a7771fe.png)

