# VISOUP · 클래스 시연용 웹사이트

## 가장 빠른 공개 배포 (추천)

1. GitHub에서 **Public** 리포지토리 `visoup` 생성
2. 첨부된 **`index.html` 하나만** `Add file → Upload files`로 업로드하고 `Commit changes`
3. `Settings → Pages → Deploy from a branch → main / (root) → Save`
4. GitHub Pages가 `Visit site`를 보여주면 그 주소를 구글 독스에 붙여 넣으세요.

**중요:** ZIP 파일을 압축해제하지 않은 채 그대로 업로드하면 웹사이트로 실행되지 않습니다. 여러 파일 대신 `index.html` 한 파일 업로드를 권합니다.

## 동작 기능

- 브랜드 VISOUP 홈과 무드보드 검색 인터페이스
- 한국어/영어 문장 입력 → 규칙 기반 영어 키워드 추천/수정
- Openverse·Wikimedia Commons 공개 API 이미지 검색
- 라이선스/제작자/원본 출처 확인, 페이지네이션
- Pinterest·Behance에서 관련 키워드 검색 링크
- 수업 시연용 자체 제작 샘플 보드 24점 (**실제 검색 결과가 아님**)
- My Mix 이미지 보드·HTML 내보내기 (브라우저 저장), 검색 링크 공유
- 모바일/데스크톱 레이아웃

## 한계

- **생성형 AI 미연동**: 추천은 사전 규칙 기반입니다. 서버와 AI API가 있으면 추가할 수 있습니다.
- **Pinterest/Behance 직접 이미지 검색 미연동**: 사이트 내부 이미지를 허가 없이 긁어오지 않으며 외부 검색 링크로 연결합니다.
- **외부 이미지 API는 네트워크·서비스 제한에 영향받습니다**: 실제 공개 환경에서 확인해야 합니다.
- **샘플 보드**는 기능 시연용 VISOUP 제작 이미지이며 사용자의 검색어와 관련된 실제 검색 결과로 제공하지 않습니다.
- **My Mix**는 각 사용자가 접속한 브라우저에만 저장됩니다. 클라우드 계정 저장은 없습니다.
- **공유 링크**는 실제 GitHub Pages 배포 후에 타인에게 열립니다. `localhost`나 컴퓨터 내부 파일 링크는 타인이 접속할 수 없습니다.

## 개발/로컬 테스트

ZIP을 풀고 폴더에서 `python3 -m http.server 8000` 실행 → `http://localhost:8000`

`PRD.md`는 과제 지침에 맞춘 10개 항목의 제품 요구사항 문서입니다.
