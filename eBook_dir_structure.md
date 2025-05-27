# eBook 디렉터리 구조

아래는 실제 프로젝트의 디렉터리 및 파일 구조입니다.

```
.
│   eBook_dir_structure.md
│   PRD.md
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
    │
    └───Video
```

## 각 폴더 및 파일 설명

- **OEBPS/**: ePub의 주요 컨텐츠가 위치하는 루트 폴더
- **Text/**: 본문 및 목차(nav.xhtml) 등 텍스트 파일 저장
- **Styles/**: CSS 등 스타일 파일 저장
- **Images/**: 이미지 파일 저장
- **Fonts/**: 폰트 파일 저장
- **Audio/**: 오디오 파일 저장
- **Video/**: 비디오 파일 저장
- **Misc/**: 기타 스크립트(js 등) 저장
- **content.opf**: ePub 메타데이터 및 manifest 파일
- **eBook_dir_structure.md, PRD.md**: 프로젝트 문서 파일
