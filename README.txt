엘리베이터포럼 안드로이드 프로젝트

앱 정보
- 앱 이름: 엘리베이터포럼
- 시작 URL: http://sellmatch.co.kr/
- 패키지명: com.webview.ElevatorForum

중요
1) 이 프로젝트는 APK 빌드용 전체 소스입니다.
2) FCM 푸시를 쓰려면 app/google-services.json 이 꼭 필요합니다.
3) 서버의 /data/push/*.json 은 관리자 발송용 비공개키이고,
   안드로이드 앱에 넣는 google-services.json 과는 다른 파일입니다.

가장 쉬운 온라인 빌드 방법
1. GitHub에 새 저장소 생성
2. 이 압축을 풀어서 전부 업로드
3. Firebase에서 받은 google-services.json 을 app 폴더에 넣기
4. GitHub -> Actions -> Build Android APK 실행
5. 완료 후 Artifacts 에서 app-debug.apk 다운로드

주의
- 현재 이 대화 환경에는 Android SDK/Gradle 빌드 도구가 없어서 실제 APK 파일까지는 직접 생성하지 못했습니다.
- 대신 바로 올리면 온라인으로 APK가 만들어지도록 GitHub Actions 파일까지 넣어두었습니다.
