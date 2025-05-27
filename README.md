# Sigil 호환 ePub 3.0 eBook 프로젝트

이 프로젝트는 Sigil에서 편집 및 열람이 가능한 ePub 3.0 이상 전자책을 제작하기 위한 예시 프로젝트입니다.

## 프로젝트 구조

```
.
│   README.md
│   PRD.md
│   eBook_dir_structure.md
│
└───OEBPS
    │   content.opf
    │
    ├───Audio
    ├───Fonts
    ├───Images
    ├───Misc
    │       script1.js
    │
    ├───Styles
    │       sgc-nav.css
    │       style1.css
    │
    ├───Text
    │       nav.xhtml
    │       page1.xhtml
    │       page2.xhtml
    │
    └───Video
```

## 주요 파일 설명

- **PRD.md**: 제품 요구 사항 정의서
- **eBook_dir_structure.md**: 디렉터리 및 파일 구조 설명
- **OEBPS/Text/page1.xhtml**: 알고리즘의 기초 챕터
- **OEBPS/Text/page2.xhtml**: 프로그래밍의 기초 챕터
- **OEBPS/Text/nav.xhtml**: 목차 파일
- **OEBPS/Styles/style1.css**: 스타일 파일
- **OEBPS/Styles/sgc-nav.css**: 목차 스타일 파일
- **OEBPS/Misc/script1.js**: 자바스크립트 파일
- **OEBPS/content.opf**: ePub 메타데이터 및 manifest 파일

## 사용 방법

1. Sigil에서 프로젝트를 열어 편집합니다.
2. 필요한 경우 스타일과 스크립트를 수정합니다.
3. ePub 파일로 내보내기 합니다.

## 참고 자료

- [ePub 3.0 표준 문서](https://www.w3.org/publishing/epub3/epub-overview.html)
- [Sigil 공식 사이트](https://sigil-ebook.com/)
- [Calibre 공식 사이트](https://calibre-ebook.com/)
# kes
