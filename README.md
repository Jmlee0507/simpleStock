
# 📈 Stock Report Generator

Streamlit을 활용한 **주식 투자 보고서 생성 웹 앱**입니다.  
실시간 금융 데이터를 기반으로 특정 종목의 **기초 정보**, **재무제표**, **투자 분석 리포트**를 자동으로 생성합니다.

---

## 🚀 데모 사이트

👉 [앱 실행하기](https://share.streamlit.io/your-username/your-repo-name/main/app.py)

> ※ 실제 URL은 GitHub에 푸시한 후 Streamlit Cloud에서 생성됩니다.

---

## 📌 주요 기능

- 🏢 기업 기본 정보 조회 (`회사명`, `산업`, `시가총액`, 등)
- 📊 재무제표 확인 (`손익계산서`, `대차대조표`, `현금흐름표`)
- ✨ GPT를 활용한 투자 보고서 요약 생성
- 🌐 웹 앱 형태로 누구나 사용 가능

---

## 🧰 사용 기술

| 기술 | 설명 |
|------|------|
| `Python` | 주 언어 |
| `Streamlit` | 웹 앱 UI 프레임워크 |
| `yfinance` | 실시간 주식 데이터 수집 |
| `OpenAI GPT` | 투자 보고서 자동 생성 |
| `Pandas` | 데이터 처리 및 출력 포맷 |

---

## ⚙️ 설치 방법

```bash
# 1. 리포지토리 클론
git clone https://github.com/your-username/stock-report-app.git
cd stock-report-app

# 2. 가상환경 설치 (선택)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. 의존성 설치
pip install -r requirements.txt

# 4. 실행
streamlit run app.py
```

---

## 📝 사용 예시

```text
✅ 종목 입력: 005930.KS (삼성전자)
👉 [기업명], [산업군], [시가총액], [총자산], [영업이익] 등
🧠 GPT 기반 요약:
"삼성전자는 반도체 중심의 글로벌 IT 기업으로, 견고한 재무구조와 높은 수익성을 보유하고 있습니다..."
```

---

## 📂 파일 구조

```
📁 stock-report-app/
├── app.py                # Streamlit 메인 앱
├── stock.py              # yfinance 기반 정보 수집 클래스
├── report_generator.py   # GPT 기반 리포트 생성 모듈
├── requirements.txt
└── README.md
```

---

## 🧑‍💻 개발자

- 👨‍💻 GitHub: [your-username](https://github.com/your-username)
- 📫 문의: your.email@example.com

---

## 📢 참고사항

- OpenAI API 키가 필요합니다 (`.env` 또는 직접 코드 내 입력)
- 종목코드는 Yahoo Finance 기준입니다 (예: 삼성전자 → `005930.KS`)

---

## 💡 To Do

- [ ] 종목 검색 기능 추가
- [ ] 산업/섹터별 리포트 비교
- [ ] 투자 지표 시각화 (차트)

---

## 📄 라이선스

MIT License
