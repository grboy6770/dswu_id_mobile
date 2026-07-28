# DSID 제61회 졸업전시 · 모바일 초대장

**사이는 공간이 아니다 — THE IN-BETWEEN IS NOT A VOID**
덕성여자대학교 실내디자인전공(DSID) 제61회 졸업전시 모바일 초대장.

- 📅 **2026. 10. 29 (목) – 11. 04 (수)**
- 📍 **Space Sophora Gallery** (서울 중구 덕수궁길 114, B1)
- 📷 Instagram [@dsid_2026](https://instagram.com/dsid_2026)

단일 파일(`index.html`)로 동작하는 정적 웹 페이지입니다. **탭하면 문이 열리는 인트로 애니메이션**,
스크롤 리빌, 네이버/구글 지도 길찾기, 캘린더 일정 추가(.ics), 링크 공유 기능이 포함되어 있습니다.

**SNS 공유 썸네일**(`og-thumbnail.png`)과 **favicon**(`favicon.svg` 외)이 포함되어 있어,
카카오톡·인스타·페이스북 등에 링크를 붙이면 미리보기 이미지가 표시됩니다.

---

## 📱 모바일 웹주소 (배포 후)

```
https://grboy6770.github.io/dswu_id_mobile/
```

## 배포 방법 — Pages 한 번만 켜주면 됩니다

> Pages 최초 활성화(사이트 생성)는 **저장소 소유자만** 할 수 있습니다.
> (Actions 워크플로우 토큰에는 이 권한이 없어 자동으로는 못 켭니다.)

### 방법 A — 브랜치에서 바로 배포 (권장, 가장 간단)
1. `Settings → Pages → Build and deployment → Source`를 **Deploy from a branch**로 선택.
2. Branch: `claude/mobile-web-address-bm0zg1`, 폴더 `/(root)` → **Save**.
3. 1~2분 뒤 위 주소로 접속. (워크플로우 불필요)

### 방법 B — GitHub Actions로 배포
1. `Settings → Pages → Source`를 **GitHub Actions**로 켠다. (여기서 Pages가 최초 생성됨)
2. `Actions` 탭 → **Deploy to GitHub Pages** → **Run workflow**로 수동 실행.
3. 실행이 성공하면 위 주소로 접속.

## 내용 수정
초대장 문구·날짜·장소·인스타그램·지도 링크는 모두 `index.html` 안에 있습니다.
파일을 수정해 커밋/푸시하면 자동으로 다시 배포됩니다.
