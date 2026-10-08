# 무역영어 학습 대시보드

## 1. 프로젝트 개요

### 프로젝트명
**Trade English Dashboard**

### 한 줄 소개
> 무역영어를 단순 암기하는 것이 아니라, 실제 무역서류를 읽고 퀴즈를 풀면서 실무형 무역영어를 익히는 학습 대시보드

### 프로젝트 목표

무역영어에 익숙하지 않은 학습자가 다음 능력을 단계적으로 키울 수 있도록 한다.

- 무역영어 핵심 용어 이해
- 실제 무역문서에 등장하는 영어 표현 익숙해지기
- Commercial Invoice, Packing List, B/L, L/C 등의 문서 구조 이해
- 무역서류의 주요 항목을 영어로 읽고 의미 파악
- 매일 퀴즈를 통한 반복 학습
- 틀린 문제를 자동으로 관리하여 취약 영역 보완
- 학습 결과와 성장 정도를 한눈에 확인

---

## 2. 핵심 컨셉

### 핵심 차별점

일반적인 영어 단어 암기 서비스가 아니라,

**실제 무역서류 → 영어 항목 확인 → 의미 학습 → 관련 표현 학습 → 퀴즈**

의 흐름으로 학습한다.

예시:

`B/L 문서 보기`

→ `Consignee 클릭`

→ `수하인 / 화물을 인도받는 당사자`

→ 관련 무역영어 표현 학습

→ 미니 퀴즈

→ 오답이면 오답노트에 자동 저장

---

# 3. 주요 사용자

## Target User

- 무역영어를 처음 공부하는 취준생
- 해외영업 / 구매 직무를 준비하는 사람
- 무역 관련 전공자
- 실제 무역서류가 낯선 학습자
- 무역영어 자격시험을 준비하는 학습자

특히 **해외영업 및 구매 직무 취업 준비생**을 주요 사용자로 설정한다.

---

# 4. 전체 메뉴 구조

```text
HOME
 ├─ 오늘의 학습
 ├─ 오늘의 퀴즈
 ├─ 오늘의 무역서류
 ├─ 학습 연속 기록
 └─ 최근 오답

TRADE ENGLISH
 ├─ 무역용어
 ├─ 무역영어 문장
 └─ 실무 표현

DOCUMENT LIBRARY
 ├─ Commercial Invoice
 ├─ Packing List
 ├─ Bill of Lading
 ├─ Air Waybill
 ├─ Letter of Credit
 ├─ Insurance Policy
 └─ Certificate of Origin

DAILY QUIZ
 ├─ 오늘의 퀴즈
 ├─ 용어 퀴즈
 ├─ 문장 퀴즈
 ├─ 서류 해석 퀴즈
 └─ 실무 상황 퀴즈

WRONG ANSWERS
 ├─ 전체 오답
 ├─ 무역용어 오답
 ├─ B/L 오답
 ├─ L/C 오답
 └─ 취약 영역

MY REPORT
 ├─ 전체 점수
 ├─ 학습량
 ├─ 분야별 실력
 ├─ 정답률
 └─ 성장 그래프
```

---

# 5. HOME

## 목적

사용자가 대시보드에 접속했을 때 **오늘 무엇을 공부해야 하는지 바로 알 수 있도록 구성**한다.

## 주요 UI

### 오늘의 학습

예시:

```text
TODAY'S STUDY

오늘의 목표
□ 무역용어 10개
□ 무역영어 문장 5개
□ 무역서류 1개
□ 퀴즈 10문제

진행률
████████░░ 80%
```

### 오늘의 퀴즈

```text
TODAY QUIZ

오늘의 퀴즈 10문제

[ QUIZ START ]
```

### 오늘의 무역서류

예:

```text
TODAY'S DOCUMENT

Bill of Lading

오늘 배울 핵심 항목
• Shipper
• Consignee
• Notify Party
• Port of Loading
• Port of Discharge

[ 문서 학습하기 ]
```

### 학습 연속 기록

```text
STREAK

🔥 7 DAYS

최근 7일 동안 매일 학습했습니다.
```

### 최근 오답

최근 틀린 문제 3~5개를 보여준다.

---

# 6. TRADE ENGLISH

## 6-1. 무역용어

무역에서 자주 사용하는 단어를 카테고리별로 제공한다.

### 카테고리 예시

- Shipping
- Payment
- Contract
- Customs
- Insurance
- Documents
- Incoterms
- Logistics

### 단어 카드

```text
CONSIGNEE

수하인

화물을 인도받는 사람 또는 회사

Example
The consignee is responsible for receiving the goods.

[ 관련 문서 보기 ]
[ 퀴즈 풀기 ]
```

---

## 6-2. 무역영어 문장

실제 무역 이메일 및 서류에서 자주 볼 수 있는 문장을 학습한다.

예:

```text
Please find attached the Commercial Invoice.

첨부된 상업송장을 확인해 주세요.

관련 표현
• attached
• Commercial Invoice
• please find attached
```

문장마다 다음 정보를 제공한다.

- 영어 문장
- 한국어 의미
- 핵심 단어
- 문장 구조
- 실무에서 사용하는 상황
- 관련 문서
- 퀴즈

---

## 6-3. 실무 표현

해외영업에서 자주 사용할 수 있는 표현을 상황별로 제공한다.

### 예시 카테고리

- 견적 요청
- 주문 확인
- 선적 안내
- 서류 전달
- 결제 요청
- 납기 안내
- 클레임
- 배송 지연

---

# 7. DOCUMENT LIBRARY

이 프로젝트의 핵심 기능.

실제 무역서류와 유사한 형태의 샘플 문서를 제공한다.

## 지원 문서

### 1. Commercial Invoice

주요 항목:

- Seller / Exporter
- Buyer / Importer
- Invoice No.
- Invoice Date
- Description of Goods
- Quantity
- Unit Price
- Total Amount
- Currency
- Country of Origin
- Terms of Delivery

### 2. Packing List

주요 항목:

- Shipper
- Consignee
- Description
- Quantity
- Net Weight
- Gross Weight
- Package
- Dimensions
- Shipping Marks

### 3. Bill of Lading

주요 항목:

- Shipper
- Consignee
- Notify Party
- Port of Loading
- Port of Discharge
- Place of Receipt
- Place of Delivery
- Vessel
- Voyage No.
- Description of Goods
- Gross Weight
- Container No.

### 4. Air Waybill

주요 항목:

- Shipper
- Consignee
- Airport of Departure
- Airport of Destination
- Handling Information
- Gross Weight
- Chargeable Weight

### 5. Letter of Credit

주요 항목:

- Applicant
- Beneficiary
- Issuing Bank
- Advising Bank
- Credit Amount
- Expiry Date
- Latest Date of Shipment
- Port of Loading
- Port of Discharge
- Documents Required
- Terms and Conditions

### 6. Insurance Policy

주요 항목:

- Insured
- Policy No.
- Voyage
- Description of Goods
- Amount Insured
- Coverage
- Risk
- Premium

### 7. Certificate of Origin

주요 항목:

- Exporter
- Consignee
- Country of Origin
- Description of Goods
- Quantity
- Invoice No.
- Certification

---

# 8. 인터랙티브 문서 학습

문서를 단순히 이미지로 보여주는 것이 아니라 **클릭하면서 학습할 수 있도록 구성**한다.

## 예시

B/L 화면에서:

```text
SHIPPER
ABC COSMETICS CO., LTD.

CONSIGNEE
XYZ BEAUTY INC.

NOTIFY PARTY
XYZ BEAUTY INC.

PORT OF LOADING
BUSAN, KOREA

PORT OF DISCHARGE
LOS ANGELES, USA
```

사용자가 `CONSIGNEE`를 클릭하면:

```text
CONSIGNEE

수하인

화물을 인도받는 당사자

쉽게 말하면:
"누가 이 화물을 받는가?"

관련 표현:
• consignee
• consignee's name
• delivery to consignee

관련 문서:
B/L
AWB

[ 퀴즈 풀기 ]
```

## 학습 연결 구조

```text
문서 항목
   ↓
용어 설명
   ↓
실무 의미
   ↓
관련 표현
   ↓
관련 문서
   ↓
미니 퀴즈
   ↓
오답 저장
```

---

# 9. LETTER OF CREDIT 학습 화면

L/C는 실제 무역영어 학습에서 중요하므로 별도의 학습 화면을 제공한다.

## 화면 예시

```text
LETTER OF CREDIT

Applicant
ABC IMPORT CO., LTD.

Beneficiary
XYZ EXPORT CO., LTD.

Amount
USD 50,000

Latest Date of Shipment
2026-11-30

Port of Loading
BUSAN

Port of Discharge
LOS ANGELES

Documents Required
1. Commercial Invoice
2. Packing List
3. Bill of Lading
4. Certificate of Origin
5. Insurance Policy
```

각 항목을 클릭하면 설명을 보여준다.

특히 `Documents Required`를 클릭하면 필요한 서류를 연결해서 보여준다.

```text
L/C
 ↓
Documents Required
 ↓
Commercial Invoice
Packing List
B/L
C/O
Insurance Policy
```

이렇게 구성하여 **L/C와 다른 무역서류의 관계**까지 학습할 수 있도록 한다.

---

# 10. DAILY QUIZ

매일 학습자가 짧게라도 공부할 수 있도록 5~10문제의 데일리 퀴즈를 제공한다.

## 난이도

### Level 1 — Vocabulary

단어 뜻 맞히기

```text
What does "Consignee" mean?

① 수출자
② 수입자
③ 수하인
④ 운송인
```

### Level 2 — Sentence

문장의 의미 파악

### Level 3 — Document

문서에서 특정 항목 찾기

### Level 4 — Practical

실제 무역 상황에서 적절한 용어 선택

### Level 5 — Exam

무역영어 시험과 유사한 문제

---

# 11. 퀴즈 유형

다양한 문제 유형을 사용한다.

- 객관식
- 빈칸 채우기
- 영어 → 한국어
- 한국어 → 영어
- 문서 항목 찾기
- 문서 해석
- 상황에 맞는 용어 선택
- 잘못된 설명 찾기

---

# 12. WRONG ANSWERS

틀린 문제는 자동으로 오답노트에 저장한다.

## 오답 카드

```text
WRONG ANSWER

Question
What is the meaning of "Notify Party"?

My Answer
수하인

Correct Answer
도착통지처

Category
B/L

[ 다시 풀기 ]
[ 개념 학습 ]
```

## 취약 영역 분석

예:

```text
MY WEAK POINTS

B/L             72%
L/C             48%
Insurance       65%
Invoice         84%
Incoterms       57%
```

L/C가 가장 낮으면:

> "L/C 관련 문제를 집중적으로 복습해 보세요."

와 같은 추천을 제공한다.

---

# 13. MY REPORT

사용자의 학습 성과를 시각화한다.

## 주요 지표

- 전체 정답률
- 총 학습 문제 수
- 학습한 단어 수
- 학습한 문서 수
- 연속 학습일
- 최근 7일 정답률
- 최근 30일 성장률

## 분야별 점수

```text
TRADE ENGLISH SKILL

Vocabulary       85%
B/L              72%
L/C              61%
Invoice          88%
Packing List     79%
Insurance        65%
Incoterms        74%
```

## 성장 그래프

최근 7일 또는 30일의 정답률 변화를 그래프로 보여준다.

---

# 14. 오늘의 학습 알고리즘

매일 다음 순서로 학습하도록 설계한다.

```text
1. 오늘의 단어 10개
        ↓
2. 오늘의 무역영어 문장 5개
        ↓
3. 오늘의 무역서류 1개
        ↓
4. 문서 핵심 항목 학습
        ↓
5. 오늘의 퀴즈 10문제
        ↓
6. 오답 자동 저장
        ↓
7. 학습 결과 기록
```

다음 날에는 전날 틀린 문제 중 일부를 다시 출제한다.

---

# 15. 추천 학습 반복 시스템

단순히 문제를 한 번 풀고 끝내지 않는다.

```text
새로운 단어
   ↓
1차 학습
   ↓
오늘의 퀴즈
   ↓
오답 저장
   ↓
다음 날 복습
   ↓
3일 후 복습
   ↓
7일 후 복습
```

이를 통해 반복적으로 틀리는 개념을 집중 학습한다.

---

# 16. 데이터 구조

Flask 기반으로 다음과 같은 구조를 권장한다.

## User

```text
id
name
created_at
study_streak
total_score
```

## Vocabulary

```text
id
term
meaning
category
example_sentence
related_document
difficulty
```

## Document

```text
id
document_type
title
description
image_path
difficulty
```

## DocumentField

```text
id
document_id
field_name
korean_meaning
explanation
example
related_terms
```

## Quiz

```text
id
question
question_type
category
difficulty
answer
explanation
```

## QuizResult

```text
id
user_id
quiz_id
is_correct
selected_answer
answered_at
```

## WrongAnswer

```text
id
user_id
quiz_id
wrong_count
last_wrong_at
```

---

# 17. Flask 프로젝트 구조

```text
trade_english_dashboard/
│
├── app.py
│
├── config.py
│
├── requirements.txt
│
├── README.md
│
├── models/
│   ├── user.py
│   ├── vocabulary.py
│   ├── document.py
│   └── quiz.py
│
├── routes/
│   ├── home.py
│   ├── trade_english.py
│   ├── documents.py
│   ├── quiz.py
│   ├── wrong_answers.py
│   └── report.py
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── trade_english.html
│   ├── documents.html
│   ├── document_detail.html
│   ├── quiz.html
│   ├── wrong_answers.html
│   └── report.html
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── documents/
│
└── data/
    ├── vocabulary.json
    ├── documents.json
    └── quizzes.json
```

---

# 18. UI/UX 디자인 방향

## 전체 분위기

- 깔끔하고 현대적인 대시보드
- 학습 서비스이지만 너무 딱딱하지 않게 구성
- 카드 기반 UI
- 충분한 여백
- 가독성 높은 폰트
- 과도한 장식 최소화

## 색상

메인 컬러:

- Light Sky Blue
- Soft Blue
- White

포인트 컬러:

- Pastel Yellow
- Pastel Pink
- Pastel Green

전체적으로 부드러운 그라데이션을 활용한다.

단, 너무 화려한 금융앱 느낌보다는 **취업 준비생이 오래 사용하기 편한 학습 대시보드**를 지향한다.

---

# 19. HOME 화면 추천 레이아웃

```text
┌──────────────────────────────────────────────┐
│ TRADE ENGLISH                    🔥 7 DAYS  │
├──────────────────────────────────────────────┤
│                                              │
│  TODAY'S STUDY                               │
│  ────────────────────────────────────────    │
│  Vocabulary       10 / 10                    │
│  Sentences         5 / 5                     │
│  Document          1 / 1                     │
│  Quiz              7 / 10                    │
│                                              │
│  ████████████████░░░░ 80%                    │
│                                              │
├──────────────────────┬───────────────────────┤
│ TODAY'S DOCUMENT     │ TODAY'S QUIZ          │
│                      │                       │
│ Bill of Lading       │ 10 Questions         │
│                      │                       │
│ [Study Document]     │ [Start Quiz]          │
├──────────────────────┴───────────────────────┤
│                                              │
│ RECENT WRONG ANSWERS                         │
│ Consignee / Notify Party / Latest Shipment   │
│                                              │
└──────────────────────────────────────────────┘
```

---

# 20. MVP 개발 우선순위

처음부터 모든 기능을 구현하지 않고 다음 순서로 개발한다.

## STEP 1

기본 화면

- Home
- Trade English
- Document Library
- Daily Quiz
- Wrong Answers
- My Report

## STEP 2

무역용어 데이터

- 약 100~200개 용어
- 카테고리
- 영어
- 한국어
- 설명
- 예문

## STEP 3

무역서류

우선 다음 4개부터 구현한다.

1. Commercial Invoice
2. Packing List
3. B/L
4. L/C

이후 확장:

5. AWB
6. Insurance Policy
7. Certificate of Origin

## STEP 4

퀴즈 시스템

- 객관식
- 정답 확인
- 해설
- 점수 계산
- 오답 저장

## STEP 5

학습 기록

- 학습일
- 정답률
- 오답 수
- 연속 학습일
- 분야별 점수

## STEP 6

인터랙티브 문서

문서의 특정 영어 항목을 클릭하면 설명이 나타나도록 구현한다.

---

# 21. 향후 확장 기능

MVP 이후 다음 기능을 추가할 수 있다.

### AI 문서 설명

사용자가 문서의 특정 부분을 선택하면 AI가 쉽게 설명한다.

### AI 무역영어 튜터

```text
"Notify Party가 뭐예요?"

→ 초보자 수준으로 설명
→ 실제 B/L에서의 역할 설명
→ 관련 용어 3개 추천
→ 미니 퀴즈 출제
```

### AI 문서 해석

사용자가 업로드한 무역서류에서 주요 항목을 찾아 설명한다.

### 실무 시뮬레이션

```text
[상황]

바이어가 선적서류를 요청했습니다.

어떤 서류를 준비해야 할까요?

① Commercial Invoice
② Packing List
③ B/L
④ Certificate of Origin
⑤ 모두 필요할 수 있음
```

### 직무별 학습

- 해외영업
- 구매
- 수출입
- 포워딩
- 무역사무

직무별로 자주 사용하는 표현과 문서를 다르게 제공한다.

---

# 22. 프로젝트의 핵심 포인트

이 프로젝트는 단순한 영어 단어 암기 앱이 아니다.

## 핵심 학습 구조

**영어 → 무역용어 → 무역서류 → 실무 상황**

을 하나로 연결한다.

예:

```text
Consignee
     ↓
수하인
     ↓
B/L
     ↓
실제 문서에서 위치 확인
     ↓
관련 문장 학습
     ↓
퀴즈
     ↓
오답 관리
```

따라서 사용자는 단어를 따로 외우는 것이 아니라 **실제 무역 업무의 맥락 속에서 영어를 익힐 수 있다.**

---

# 23. 포트폴리오 관점의 차별점

이 프로젝트를 단순한 영어 학습 서비스가 아닌 **무역 직무 포트폴리오 프로젝트**로 보여주는 것이 중요하다.

### 보여줄 수 있는 역량

- 무역 실무 이해
- 무역서류 이해
- 데이터 구조 설계
- 사용자 중심 UX 설계
- 학습 데이터 분석
- 웹 서비스 개발
- 해외영업/구매 직무 이해

### 프로젝트 소개 문구

> 무역영어에 어려움을 느끼는 취업 준비생을 위해 실제 무역서류 기반의 학습 경험을 제공하는 웹 대시보드입니다. 무역용어 암기부터 Commercial Invoice, B/L, L/C 등의 문서 학습, 데일리 퀴즈, 오답 분석까지 하나의 서비스에서 경험할 수 있도록 설계했습니다.

---

# 24. 최종 사용자 경험

사용자가 매일 서비스를 방문하면 다음 경험을 하도록 한다.

```text
로그인
 ↓
HOME
 ↓
오늘의 학습 확인
 ↓
오늘의 무역용어 학습
 ↓
오늘의 무역서류 확인
 ↓
문서의 주요 영어 항목 클릭
 ↓
의미 및 실무 설명 확인
 ↓
오늘의 퀴즈
 ↓
틀린 문제 자동 저장
 ↓
학습 결과 확인
 ↓
다음 날 복습
```

최종적으로 사용자가 서비스를 꾸준히 사용할수록

**"무역영어가 어렵다"**

에서

**"B/L이나 L/C를 보면 어떤 내용인지 대략 읽을 수 있다"**

로 성장하는 것을 목표로 한다.
