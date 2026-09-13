# 🎡 롯데월드 매직 밴드 - NFC 웹사이트

함께하는 순간을 스마트하게 연결할 롯데월드 매직 밴드의 웹사이트입니다.

## 🚀 Vercel 배포 가이드

### Step 1️⃣: GitHub 저장소 생성

1. **GitHub 접속** → https://github.com/new
2. **저장소 이름 입력**: `lotte-magic-band`
3. **Public 선택** (누구나 접근 가능하게)
4. **Create repository** 클릭

### Step 2️⃣: 파일 업로드

#### 방법 A: 웹으로 업로드 (가장 간단)

1. GitHub 저장소 페이지에서 **"Add file"** → **"Upload files"** 클릭
2. 아래 파일들을 드래그앤드롭 또는 선택:
   - `index.html`
   - `vercel.json`
   - `README.md`
3. **"Commit changes"** 클릭

#### 방법 B: Git 명령어로 업로드

```bash
# Git 설치 확인 (Windows/Mac/Linux)
git --version

# 저장소 클론
git clone https://github.com/[YOUR_USERNAME]/lotte-magic-band.git
cd lotte-magic-band

# 파일 추가
git add .

# 커밋
git commit -m "Initial commit: Add Lotte World Magic Band website"

# Push
git push origin main
```

### Step 3️⃣: Vercel에 배포

1. **Vercel 접속** → https://vercel.com/signup
2. **GitHub로 로그인** (또는 이메일로 가입)
3. **"Import Project"** 또는 **"New Project"** 클릭
4. **GitHub에서 저장소 검색** → `lotte-magic-band` 선택
5. **Import** 클릭
6. 설정 그대로 두고 **"Deploy"** 클릭

### Step 4️⃣: 배포 완료! 🎉

Vercel이 자동으로 배포를 시작합니다. 약 1-2분 후:
- ✅ **배포 완료** 메시지 표시
- 📍 **배포된 URL** 표시 예: `https://lotte-magic-band-[random].vercel.app`

---

## 📱 NFC 태그 설정 방법

배포 후 NFC 태그에 아래 주소를 인코딩하세요:

```
https://lotte-magic-band-[random].vercel.app
```

### NFC 태그 인코딩 방법

**Android:**
- NFC Tools 앱 다운로드 → "Write" → URL 입력 → 태그에 태그

**iOS:**
- Shortcuts 앱 → "NFC 스캔" 설정 → URL 추가

---

## 🎯 주요 기능

- 🗺️ **실시간 위치 추적**: 어드벤처 맵에서 일행의 위치 확인
- 📍 **안심 위치 서비스**: 거리 초과 시 자동 알림
- 💡 **LED 라이트 제어**: 터치로 켜고 끌 수 있는 LED 애니메이션
- 🎮 **시뮬레이션**: 방향키로 위치 변화 테스트

---

## 📊 프로젝트 정보

- **2026 롯데월드 상품 디자인 공모전 제출작**
- **테마**: YOU & I 함께하는 순간, 롯데월드
- **가격**: 약 24,000원 (개별) / 44,900원 (세트)

---

## 🔧 문제 해결

### 배포가 안 될 때
1. **GitHub 연결 확인**: Vercel 대시보드 → Settings → Git Integration
2. **파일 확인**: index.html, vercel.json이 저장소 최상위에 있는지 확인
3. **로그 확인**: Vercel 대시보드에서 배포 로그 확인

### URL이 잘못됨
- Vercel 대시보드에서 **"Domains"** 메뉴에서 정확한 URL 확인

---

## 📞 지원

문제가 있으면:
1. **Vercel 상태 확인**: https://vercel.com/status
2. **GitHub 저장소 권한 확인**
3. **브라우저 캐시 지우기** (Ctrl+Shift+Delete)

---

**🎊 배포 성공! 이제 NFC 태그로 연결할 수 있습니다!**
