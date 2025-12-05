  <div align="center"><img src="https://github.com/user-attachments/assets/e4066a2a-511d-4e4f-9f49-1c76aee96c53" width="20%"/></div>
  <br>  
</p>

<p align="center"><b>"fintory"</b><br> <span>아동용 모의 주식 투자 서비스입니다.</p>

<br>

## 💡 기능
이 프로젝트는 아이들을 위한 모의 주식 투자 모바일 애플리케이션을 구현합니다.
주요 기능은 다음과 같습니다:
* **국내/외 주요 40종목에 대한 모의투자 기능**
* **[모의투자]** - [실시간 가격을 바탕으로 매매, 투자현황/내역, 그래프 확인]
* **[인증/인가]** - [카카오, 구글 소셜 로그인 및 jwt를 활용한 일반 로그인/회원가입 기능]
* **[출석,포인트]** - [출석체크 기능 및 포인트 환전 시스템]
* **[경제뉴스,용어]** - [최신 경제 관련 어린이 뉴스, 경제 용어 검색/학습]

## :bicyclist: 무엇을 경험했나요?

- 웹소켓을 통한 외부 api 사용 경험
- 트래픽 로드 테스트 및 명확한 근거를 바탕으로한 개선 경험
- 모바일 환경에서 인증인가 구조 경험
- 메트릭 수집 및 대시보드를 통한 모니터링 서버 구축 경험
- 논블로킹 비동기 처리 서버 리팩토링 경험

## :bicyclist: 서비스 UI
<img width="160" height="330" alt="스크린샷 2025-12-05 오전 8 53 06" src="https://github.com/user-attachments/assets/4cd7883a-9ea6-40d9-87e0-b2a29566eab3" />
<img width="160" height="330" alt="스크린샷 2025-12-05 오전 8 53 40" src="https://github.com/user-attachments/assets/5e70f046-29ca-47e1-827d-8e788f99d04f" />
<img width="160" height="330" alt="스크린샷 2025-12-05 오후 4 50 25" src="https://github.com/user-attachments/assets/3fdd1181-dab9-433e-b610-c85ff1372f64" />
<img width="160" height="330" alt="스크린샷 2025-12-05 오전 10 23 35" src="https://github.com/user-attachments/assets/d12ab134-c790-41ac-9295-a08bfae8ec08" />

## :bicyclist: 프로젝트를 통해 개선한 문제들
- [개선전 데이터 통신 구조(Stomp Websocket)](https://velog.io/@ugiuk00/Fintory-%EC%B4%88%EA%B8%B0-%EC%8B%A4%EC%8B%9C%EA%B0%84-%ED%86%B5%EC%8B%A0-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-Spring-WebSocket-STOMP-SimpleBroker-%ED%8A%B8%EB%9E%98%ED%94%BD-%ED%85%8C%EC%8A%A4%ED%8A%B8-%EB%B0%8F-%ED%95%9C%EA%B3%84)
- [개선후 데이터 통신 구조(Webflux+Rsocket)](https://velog.io/@ugiuk00/Fintory-Spring-Webflux-Rsocket%EC%9D%84-%ED%99%9C%EC%9A%A9%ED%95%98%EC%97%AC-%EC%8B%A4%EC%8B%9C%EA%B0%84-%ED%86%B5%EC%8B%A0-%EC%84%9C%EB%B2%84-%EC%84%B1%EB%8A%A5-%EA%B0%9C%EC%84%A0%ED%95%98%EA%B8%B0)
- [도커 빌드 최적화(layer cache)](https://velog.io/@ugiuk00/Fintory-docker-%EB%B9%8C%EB%93%9C-%EC%B5%9C%EC%A0%81%ED%99%94)
- [데드락 트러블 슈팅](https://velog.io/@ugiuk00/Fintory-%EB%8D%B0%EB%93%9C%EB%9D%BD-%ED%95%B4%EA%B2%B0-%EB%B0%8F-%EC%A0%95%ED%95%A9%EC%84%B1-%EB%B3%B4%EC%9E%A5-%EB%A6%AC%ED%8C%A9%ED%86%A0%EB%A7%81%EB%9D%BD-%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98)


### :bicyclist: 서비스는 어떻게 구성되어있나요?
<img width="1240" height="624" alt="스크린샷 2025-12-05 오후 5 52 59" src="https://github.com/user-attachments/assets/7cd924f8-5d52-445c-9f7f-919b962ab6b6" />


