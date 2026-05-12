# GOE Messenger Viewer

GOE 메신저(경기도교육청) 백업 파일을 복호화하여 브라우저에서 쪽지·대화를 열람하는 로컬 실행 도구입니다.

본 저장소는 **공개 문서·약관 호스팅 전용** 입니다.
프로그램 소스코드는 비공개입니다.

---

## 다운로드

[Dropbox 공유 폴더](https://www.dropbox.com/scl/fo/j0i9yeza857dw9u7wtcm3/ABNeXufKGDPmiCeYwRHiEVQ?rlkey=bc5j0yamy2kirbdrz0pkjj60k&dl=0)
에서 최신 ZIP 또는 MSIX 패키지를 받을 수 있습니다.

Microsoft Store 등재 진행 중입니다.

---

## 동작 환경

- Windows 10 / 11 (64-bit)
- 추가 설치 불필요 (Python·VC++ 모두 EXE 에 내장)
- 완전 오프라인 동작 (텔레메트리 외 데이터 송신 없음 — [이용 약관 §4](eula.md) 참고)

---

## 주요 기능

- 라이브 DB(`@Talk.db`) 또는 백업 파일(`.bak`) 변환
- 쪽지·대화 인덱스, 검색·필터·정렬
- 통계 페이지 (연도별·월별 추세, 대상자 Top 10)
- 인쇄 친화 레이아웃
- PIN 게이트 (4자리, 5회 실패 5분 잠금)
- 모든 처리 로컬 — 대화 내용은 외부 송신 없음

---

## 이용 약관 / 개인정보 처리방침

[**전체 이용 약관 보기 → eula.md**](eula.md)

요약:
- 본인 계정 백업 파일에 한해 사용
- 감시·조사·징계·평가·분쟁 유도 목적 사용 금지
- 모든 처리는 로컬 PC 내부에서만 수행
- 버전·익명 통계 외 송신 데이터 없음 (자세한 항목은 약관 §4)

---

## 문의

- 버그 제보·기능 제안: purehermit+gmv@gmail.com

---

Copyright 배추아빠. All rights reserved.
