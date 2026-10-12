# UrlCut for macOS

[![Latest Release](https://img.shields.io/github/v/release/kklyoon/UrlCutmacOS?label=Latest%20Version&color=blue)](https://github.com/kklyoon/UrlCutmacOS/releases/latest)
[![macOS](https://img.shields.io/badge/Platform-macOS-lightgrey.svg)](https://github.com/kklyoon/UrlCutmacOS)

UrlCut macOS 공식 배포 및 OTA(Sparkle) 피드 저장소입니다.

---

## 📥 다운로드 (Download)

- **최신 릴리즈 다운로드**: [UrlCut.dmg (v1.0.32)](https://github.com/kklyoon/UrlCutmacOS/releases/download/v1.0.32/UrlCut.dmg)
- **전체 릴리즈 목록**: [GitHub Releases](https://github.com/kklyoon/UrlCutmacOS/releases)

---

## 🚀 설치 방법

1. 위의 **[UrlCut.dmg]** 링크를 클릭하여 다운로드합니다.
2. 다운로드된 `UrlCut.dmg` 파일을 더블 클릭하여 엽니다.
3. `UrlCut.app` 아이콘을 **Applications (응용 프로그램)** 폴더로 드래그 앤 드롭합니다.
4. Launchpad 또는 응용 프로그램 폴더에서 UrlCut을 실행합니다.

> **참고 (미인증 앱 경고 발생 시)**:
> 개발자 서명이 없는 경우, 터미널에서 다음 명령어를 실행하여 격리 속성을 해제할 수 있습니다:
> ```bash
> xattr -cr /Applications/UrlCut.app
> ```

---

## 🔄 자동 업데이트 (OTA Feed)

UrlCut macOS 앱은 **Sparkle** 프레임워크 기반 OTA 자동 업데이트를 지원합니다.
- **Sparkle Appcast Feed URL**: `https://raw.githubusercontent.com/kklyoon/UrlCutmacOS/main/appcast.xml`

---

## 📝 최신 변경 사항 (v1.0.32)

- 링크 카드 썸네일 로드 실패 시 자동 재조회 및 유튜브 hqdefault 폴백 연동
- 만료 및 누락된 썸네일 자동 복원 및 재조회(refreshThumbnail) 기능 구현
- 웹페이지 메타데이터 추출기 강화 및 인스타그램/스레드/유튜브 썸네일 개선
- LinkRepository의 updateLink에 썸네일(imageUrl) 갱신 파라미터 추가
- 링크 카드에 X 및 Threads 미디어 다운로드 버튼 연동 및 다국어 지원
- X(트위터) 및 Threads 사진/동영상 다운로드 서비스와 플랫폼 감지 기능 구현
- Android 및 iOS 병렬 릴리즈 빌드 및 실행 스크립트와 에이전트 스킬 추가

