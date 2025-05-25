# 단어장 시각화 도구

생성 날짜: 2025-05-25 11:46:51

## 파일 구성
- index.html: 메인 HTML 파일
- styles.css: 스타일시트
- script.js: JavaScript 기능 (수정된 버전)
- stats_data.json: 통계 데이터
- text_data.json: 지문 및 단어 데이터

## 사용 방법
1. 모든 파일이 같은 폴더에 있는지 확인하세요.
2. 웹 서버를 사용하여 index.html을 열어주세요.
   - Python: `python -m http.server 8000`
   - Node.js: `npx http-server`
   - 또는 다른 로컬 웹 서버 사용

## 주의사항
- 브라우저에서 직접 index.html 파일을 열면 CORS 오류가 발생할 수 있습니다.
- 반드시 웹 서버를 통해 접근하세요.

## 기능
- 지문별 단어 하이라이팅
- 고급 필터링 (지문, 단어 유형, 품사별)
- 메타데이터 검색 (교재명, 교재ID, 상품ID, 지문ID)
- 통계 차트 및 대시보드
- PDF, Excel, CSV 내보내기
- 다크 모드 지원
- 페이지네이션
