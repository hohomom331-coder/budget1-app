# 우리집 가계부 📒

매달 고정 지출을 쉽게 정리하는 가계부 앱입니다.  
GitHub Pages로 배포해서 핸드폰 홈 화면에 아이콘으로 추가할 수 있어요.

---

## 🚀 GitHub Pages 배포 방법

### 1단계 — 저장소 만들기
1. [github.com](https://github.com) 로그인
2. 우측 상단 `+` → **New repository**
3. Repository name: `budget-app` (원하는 이름)
4. **Public** 선택
5. **Create repository** 클릭

### 2단계 — 파일 올리기
1. 새 저장소 페이지에서 **uploading an existing file** 클릭
2. 이 폴더 안의 모든 파일을 드래그해서 업로드
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `.github/workflows/deploy.yml`
3. **Commit changes** 클릭

### 3단계 — GitHub Pages 활성화
1. 저장소 → **Settings** 탭
2. 왼쪽 메뉴 **Pages** 클릭
3. Source: **GitHub Actions** 선택
4. 잠시 기다리면 주소가 생성됩니다  
   예: `https://사용자명.github.io/budget-app`

---

## 📱 홈 화면에 추가하기

### 아이폰 (Safari)
1. Safari에서 위 주소 접속
2. 하단 공유 버튼(□↑) 탭
3. **홈 화면에 추가** 탭
4. **추가** 탭

### 안드로이드 (Chrome)
1. Chrome에서 위 주소 접속
2. 주소창 오른쪽 `⋮` 메뉴
3. **홈 화면에 추가** 탭

---

## 💡 기능

- 매달 **목요일 횟수**를 자동 계산해서 용돈 자동 산출
- 통신요금, 보험/연금 고정 금액 자동 표시
- 교육비, 치료비, 부모님 행사비 등 매달 변동비 입력
- **저장** 누르면 핸드폰에 저장 (앱 껐다 켜도 유지)
- 연간 월별 지출 요약 표시
- **오프라인에서도 사용 가능**
