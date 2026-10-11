# 주식왕 다운로드

[주식왕 소개·다운로드 페이지](https://skim72.github.io/stockking-downloads/) · [APK와 변경 내역](https://github.com/SKIM72/stockking-downloads/releases)

주식왕은 가상 자산으로 시세·주문·기업 투자·은행·시즌 순위를 즐기는 Android 주식 게임입니다. 실제 주식 주문이나 현금 투자를 제공하지 않습니다.

## 테스트 APK

`v1.0.0-preview.1`은 개선된 UI와 Ubuntu HTTPS 서버 연결을 확인하는 ARM64 테스트 버전입니다. Android 7.0 이상이 필요합니다. JS 번들을 포함하므로 Metro를 실행하지 않아도 됩니다.

APK는 기존 개발 키로 서명했으며 정식 배포용이 아닙니다. 기존 앱과 서명 키가 다르면 업데이트 설치가 제한됩니다. APK 설치 후 기존 계정으로 로그인하거나 회원가입과 메일 인증을 진행하세요. 다운로드 파일 검증에는 Release에 첨부한 `SHA256SUMS`를 사용합니다.

2026-10-11 시세 저장·DB 연결 복구 수정본을 Ubuntu 서버에 적용했고, 약 6.3초 간격의 시세 갱신과 외부 HTTPS 응답을 확인했습니다. 정식 서명과 Android 실기기 설치·거래 검증은 아직 진행 예정입니다.

이 저장소에는 공개 소개 페이지와 APK만 배포합니다. 서버 키·DB 설정·Android 정식 서명 키는 포함하지 않습니다. 테스트 버전은 prerelease로 게시하며, 정식 APK 자동 업데이트 채널과 구분합니다.
