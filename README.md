# ONE CART

Windows x64 · v0.2.1-photon-dev · 온라인 협동 개발 빌드

[Windows 게임 다운로드](https://github.com/atozuser0224/one-cart/releases/download/v0.2.1-photon-dev/ONE-CART-v0.2.1-photon-dev-Windows-x64.zip) · [수정 내역](RELEASE_NOTES.md)

35초 후 연결 종료 문제를 수정한 버전입니다. 이 저장소는 실행 파일과 사용 안내를 제공하는 배포 저장소입니다.

## 실행

**Alt+Enter 또는 F11**로 전체화면과 창 모드를 전환할 수 있습니다. 친구와 모두 같은 최신 버전을 사용하세요. 처음 화면에서는 하단의 **온라인 방으로 계속** 버튼을 누릅니다.

ZIP 전체를 풀고 `OneCart.exe`를 실행하세요. 실행 파일, `OneCart_Data`, DLL 및 하위 폴더를 함께 유지해야 합니다. Windows x64와 인터넷 연결이 필요합니다.

한 명이 온라인 메뉴에서 방을 만들고, 친구가 같은 버전에서 8자리 방 코드로 참가합니다. 최소 2명이 준비하면 호스트가 게임을 시작할 수 있습니다. 플레이어의 Photon 계정, 서비스 키 입력, Steam 설치는 필요하지 않습니다. 싱글 플레이와 LAN 전용 모드는 없습니다.

## 개발 상태

2~4인 연결 구조입니다. 같은 PC의 두 프로세스를 이용한 Photon Cloud 2인 방 생성·참가·준비·스테이지 진입과 상품·카트 상태 동기화를 확인했습니다.

서로 다른 PC, 4인, 실제 마이크, 재접속, 지연·패킷 손실, 전체 게임 진행과 장기 플레이는 아직 검증하지 않았습니다. 아트와 밸런스도 개발 중입니다.

## 배포 및 문의

- 릴리즈: https://github.com/atozuser0224/one-cart/releases/tag/v0.2.1-photon-dev
- 문제 제보: https://github.com/atozuser0224/one-cart/issues

문제를 제보할 때 버전, 발생 단계, 호스트/참가자 여부를 적어 주세요. 비밀번호나 인증 토큰은 올리지 마세요.

제3자 고지는 `THIRD_PARTY_NOTICES.md`, 관련 라이선스 전문은 `Licenses/`에서 확인할 수 있습니다.
