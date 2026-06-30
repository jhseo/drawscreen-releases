# DrawScreen

맥 화면 위에 바로 그림·글자·도형을 그리는 메뉴바 주석 앱입니다.
편집 모드에 들어가면 현재 화면 위에 투명 캔버스가 떠서, 보이는 화면 그대로 위에 그릴 수 있어요. (Epic Pen 스타일)

## 다운로드

👉 **[최신 버전 받기 (DMG)](https://github.com/jhseo/drawscreen-releases/releases/latest)**

## 설치 & 처음 열기

아직 Apple 공증(notarization) 전 베타라, 처음 열 때 macOS가 *"신원을 확인할 수 없습니다 / 확인되지 않은 개발자"* 로 막습니다. **한 번만** 아래처럼 허용하면 됩니다.

1. DMG를 열어 **DrawScreen.app** 을 **응용 프로그램(Applications)** 폴더로 드래그
2. `DrawScreen` 을 더블클릭 → 경고가 뜨면 **취소**
3. **시스템 설정 → 개인정보 보호 및 보안** 열기
4. 아래로 스크롤 → *"'DrawScreen'이(가) 차단되었습니다…"* 옆 **"그래도 열기"** 클릭
5. 암호 / Touch ID 확인 → 다시 열면 실행됩니다 (이후엔 경고 없음)

> 터미널이 편하면 한 줄로도 됩니다:
> ```bash
> sudo xattr -dr com.apple.quarantine /Applications/DrawScreen.app
> ```

## 사용법

- **편집 모드 켜기/끄기**: `⌘⇧D` 또는 메뉴바의 연필 아이콘
- 도구: 펜 · 선/화살표 · 도형(사각형·둥근사각형·원·별·삼각형) · 텍스트 · 지우개
- **선택 도구**로 이동 · 크기조정 · 회전
- 색상, 선 굵기/스타일(실선·파선·점선) 변경
- `ESC` 또는 ✕ 로 편집 종료

## 요구 사항

- macOS 13 (Ventura) 이상

---

마음에 드셨다면 ☕ [후원하기](https://ko-fi.com/jhseo)
