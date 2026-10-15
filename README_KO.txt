별빛 모험 - Android APK 프로젝트

이 프로젝트는 간단한 오프라인 1인용 RPG HTML 게임을 Android 앱(WebView)으로 감싼 것입니다.
이 압축 파일 자체는 APK가 아닙니다. GitHub Actions에서 APK를 빌드할 수 있도록 구성되어 있습니다.

APK 빌드 방법
1. GitHub에 로그인하고 새 저장소(repository)를 만듭니다.
2. 이 ZIP의 압축을 풉니다.
3. 압축을 푼 폴더 안의 파일과 폴더를 저장소 최상위에 업로드합니다. .github 폴더도 포함해야 합니다.
4. GitHub 저장소의 Actions 탭을 엽니다.
5. "Build Android APK" 워크플로를 선택하고 Run workflow를 누릅니다.
6. 작업이 성공하면 해당 실행 화면 아래 Artifacts의 "ByeolbitSolo-APK"를 눌러 다운로드합니다.
7. 내려받은 ZIP을 풀고 app-debug.apk를 Android 휴대폰에서 실행합니다.

참고
- 인터넷 권한을 요청하지 않으며 게임 화면은 앱 내부 파일에서 열립니다.
- 현재 버전은 간단한 프로토타입이며, 게임 진행 저장은 아직 별도 구현되지 않았습니다.
