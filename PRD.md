# 제품 요구 사항 정의서 (Product Requirements Document, PRD)

## 1. 개요(Overview)

- **프로젝트명:** Sigil 호환 ePub 3.0 eBook 제작 프로그램
- **목적:** Sigil에서 편집 및 열람이 가능한 ePub 3.0 이상 전자책을 효율적으로 제작할 수 있는 프로그램 개발
- **대상 사용자:** 전자책 제작자, 출판사, 교육기관 등

---

## 2. 목표(Goals)

- ePub 3.0 이상 표준을 완벽히 지원
- Sigil 등 주요 eBook 편집기와의 호환성 확보
- 직관적이고 사용하기 쉬운 UI 제공
- 다양한 멀티미디어(이미지, 오디오, 비디오) 삽입 지원

---

## 3. 주요 기능(Features)

- ePub 3.0 구조 자동 생성(폴더, 파일, manifest 등)
- 텍스트, 이미지, 오디오, 비디오 파일 추가 및 관리
- CSS, JS 등 스타일 및 스크립트 파일 관리
- 목차(nav.xhtml) 자동 생성 및 편집
- 미리보기 및 Sigil에서의 호환성 체크
- 메타데이터(content.opf) 편집 기능
- ePub 파일 패키징 및 내보내기

---

## 4. 비기능 요구사항(Non-functional Requirements)

- Windows, Mac, Linux 지원(또는 웹 기반)
- 빠른 실행 속도와 안정성
- 직관적인 UX/UI
- Sigil, Calibre 등 주요 eBook 툴과의 호환성

---

## 5. 제약사항(Constraints)

- ePub 3.0 이상만 지원
- Sigil에서 정상적으로 열리고 편집 가능해야 함
- 오픈소스 라이브러리 사용 시 라이선스 준수

---

## 6. 사용자 시나리오(User Scenarios)

- **시나리오 1:** 사용자가 새 eBook 프로젝트를 생성하고, 텍스트와 이미지를 추가한 뒤 ePub 파일로 내보낸다.
- **시나리오 2:** 기존 ePub 파일을 불러와 목차와 스타일을 수정한다.

---

## 7. 일정 및 마일스톤(Timeline & Milestones)

- 요구사항 정의: 2024.05.20 ~ 2024.05.27
- 프로토타입 개발: 2024.05.28 ~ 2024.06.10
- 1차 테스트 및 피드백: 2024.06.11 ~ 2024.06.17
- 정식 배포: 2024.06.30

---

## 8. 참고 자료(References)

- [ePub 3.0 표준 문서](https://www.w3.org/publishing/epub3/epub-overview.html)
- [Sigil 공식 사이트](https://sigil-ebook.com/)
- [Calibre 공식 사이트](https://calibre-ebook.com/)
