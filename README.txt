SQLD 홈 화면 앱(PWA) 올리는 법 — GitHub Pages 기준

1) github.com 가입/로그인 → 오른쪽 위 + → New repository
   이름: sqld (Public 선택) → Create repository
2) "uploading an existing file" 클릭 → 이 폴더 안의 파일을 전부 끌어다 놓기
   (index.html, manifest.webmanifest, sw.js, icons 폴더)
   → Commit changes
3) Settings → Pages → Branch: main / (root) → Save
4) 1~2분 뒤 주소가 생김: https://<아이디>.github.io/sqld/

폰에 설치
- 아이폰(사파리): 주소 열기 → 공유 버튼 → "홈 화면에 추가"
- 안드로이드(크롬): 주소 열기 → ⋮ 메뉴 → "앱 설치" 또는 "홈 화면에 추가"

내용을 고쳤을 때
- index.html 교체 후, sw.js 맨 위 VERSION 값을 'sqld-v2'처럼 올려서 함께 업로드
- 앱을 한 번 껐다 켜면 새 버전 반영

참고
- 즐겨찾기·다크모드 설정은 그 폰에만 저장됩니다.
- 첫 실행 때 인터넷이 필요하고, 그 뒤로는 오프라인에서도 열립니다.
