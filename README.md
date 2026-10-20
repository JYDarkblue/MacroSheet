# 미국 시장 종합 대시보드 (US Market Dashboard)

실시간 금융 데이터와 거시경제 지표, 그리고 미국 시가총액 상위 30위 종목의 시세 변화를 한눈에 모니터링할 수 있는 반응형 웹 대시보드입니다.

---

## ✨ 주요 기능

1. **주요 시장 지표 요약**
   - S&P 500, NASDAQ, Dow Jones 등 주요 지수
   - 미국 10년물 및 2년물 국채금리
   - WTI 원유, 금 선물, 비트코인 등 주요 원자재 및 암호화폐 시세 제공
2. **원화 기준 환율 카드**
   - USD/KRW, JPY/KRW(100엔 기준), CNY/KRW 환율 및 전일 대비 등락 정보 제공
3. **핵심 거시경제 지표**
   - CPI, PPI, 실업률, 비농업 고용, GDP 성장률 최신 발표치 제공
4. **통합 주요 지표 추이 차트**
   - 선택한 기간(1주일 ~ 5년)에 따른 자산별 정규화 비교 차트 (마우스 호버 시 상세 툴팁 지원)
   - 범례 체크박스를 통한 개별 지표 켜기/끄기 기능
5. **미국 시가총액 상위 30위 종목 리스트**
   - 아코디언 토글 UI를 적용하여 깔끔하게 접고 펼칠 수 있는 30개 핵심 종목 리스트
   - 각 종목별 현재가, 전일 종가, 변동 금액, 등락률(%) 실시간 표기
6. **실시간 새로고침**
   - 상단 타이틀 옆 새로고침(🔄) 아이콘을 통해 언제든 최신 데이터 갱신 가능

---

## 🛠️ 기술 스택

- **Frontend**: Vanilla JavaScript (ES6+), HTML5, CSS3 (CSS Variables, Flexbox/Grid)
- **Chart**: HTML5 Canvas (커스텀 렌더링 및 인터랙티브 툴팁)
- **Data Sources**: Yahoo Finance API (비공식 엔드포인트), Frankfurter API, FRED 거시경제 데이터

---

## ScreenShot
<img width="999" height="865" alt="image" src="https://github.com/user-attachments/assets/9c09c873-dc85-41c7-8c50-7549ff0ed578" />
