# UrlCut for macOS

[![Latest Release](https://img.shields.io/github/v/release/kklyoon/UrlCutmacOS?label=Latest%20Version&color=blue)](https://github.com/kklyoon/UrlCutmacOS/releases/latest)
[![macOS](https://img.shields.io/badge/Platform-macOS-lightgrey.svg)](https://github.com/kklyoon/UrlCutmacOS)

UrlCut macOS 공식 배포 및 OTA(Sparkle) 피드 저장소입니다.

---

## 📥 다운로드 (Download)

- **최신 릴리즈 다운로드**: [UrlCut.dmg (v1.0.26)](https://github.com/kklyoon/UrlCutmacOS/releases/download/v1.0.26/UrlCut.dmg)
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

## 📝 최신 변경 사항 (v1.0.26)

- macOS DMG 패키지 GitHub 배포 자동화 스크립트 추가
- Sparkle OTA 피드 기본 주소를 UrlCutmacOS 저장소로 변경
- 기기간 폴더 순서 동기화 누락 및 감지 스트림 수정
- Provider 생명주기 안정성을 위한 ref.mounted 방어 코드 추가
- 폴더 순서 변경 화면 구현 및 설정 화면 연동
- 피어 동기화 및 백업에 폴더 순서 동기화 지원
- 폴더 순서 저장 및 타임스탬프 기반 병합 로직 추가

