# ScenePlus ai

ScenePlus ai 설치 파일과 업데이트를 배포하는 저장소입니다.
개발 프로젝트나 서명 개인키를 올리는 저장소가 아닙니다.

## 다운로드 — 2.8.30

사용하는 운영체제의 설치 파일 **하나만** 받으세요.

| 운영체제 | 설치 파일 | 크기 |
| --- | --- | ---: |
| Windows x64 | [Windows 설치 파일 다운로드](https://github.com/siyuns/sceneplus-ai-releases/releases/download/v2.8.30/ScenePlusAI-2.8.30-windows-x64.exe) | 약 354MB |
| Apple Silicon Mac | [Mac 설치 파일 다운로드](https://github.com/siyuns/sceneplus-ai-releases/releases/download/v2.8.30/ScenePlusAI-2.8.30-mac-arm64.pkg) | 약 343MB |

[전체 릴리즈·사용안내·체크섬 보기](https://github.com/siyuns/sceneplus-ai-releases/releases/latest)

Mac 빌드의 최소 macOS 버전은 26.0입니다.
현재 설치 파일에는 Windows 코드서명·macOS Developer ID 서명·공증이 없습니다.

## 다운로드 횟수

![Windows 다운로드 횟수](https://img.shields.io/github/downloads/siyuns/sceneplus-ai-releases/v2.8.30/ScenePlusAI-2.8.30-windows-x64.exe?label=Windows%20downloads)
![Mac 다운로드 횟수](https://img.shields.io/github/downloads/siyuns/sceneplus-ai-releases/v2.8.30/ScenePlusAI-2.8.30-mac-arm64.pkg?label=Mac%20downloads)

설치 파일별 **다운로드 횟수**이며, 중복을 제외한 사람 수나 설치 완료 수는 아닙니다.
배지 표시는 집계 반영에 시간이 걸릴 수 있습니다.
프로그램에 별도의 사용자 추적 기능을 추가한 것은 아닙니다.

## 처음 설치하기

### Windows

1. EXE를 실행해 설치합니다.
2. 처음 설치하는 경우에만 **Fresh install**을 선택합니다.
3. 시작 메뉴의 **Open extension folder**로 확장 폴더를 확인합니다.

### Mac

1. PKG를 설치한 뒤 응용 프로그램의 **ScenePlus ai**를 엽니다.
2. 엔진 설치를 진행하고, 처음 설치하는 경우에만 **Fresh install**을 선택합니다.
3. 앱의 **Open extension folder**로 확장 폴더를 확인합니다.

서명되지 않은 PKG가 차단되면 파일 출처를 확인한 뒤 시스템 설정 →
개인정보 보호 및 보안에서 해당 파일의 **그래도 열기**로 진행합니다.

### Chrome 확장 연결

1. `chrome://extensions`에서 개발자 모드를 켭니다.
2. **압축해제된 확장 프로그램 로드**로 위에서 확인한 확장 폴더를 등록합니다.
3. 확장 설정에서 엔진과 확장 버전이 2.8.30으로 연결되는지 확인합니다.

## 기존 보호판 업데이트

- 제작·렌더링·AI 작업이 없을 때 새 설치 파일을 실행합니다.
- 기존 프로그램·확장 경로를 유지하고 **Fresh install은 체크하지 않습니다.**
- Chrome에서 기존 확장 카드의 새로고침을 누릅니다. 삭제·재등록하지 않습니다.
- 열려 있는 TubeWorker·Flow·Grok 탭도 새로고침합니다.

지원 범위는 신규 설치와 보호판 **2.8.29 이상에서의 업데이트**입니다.
기존 2.8.28에서 보호판으로 처음 전환하는 용도는 아닙니다.
오류가 나면 사용자 데이터·설치 기록을 지우지 말고 오류 문구를 전달하세요.

## 참고

- 설치와 엔진 시작 자체에는 AI CLI가 필수가 아닙니다.
- AI 기능을 선택할 때 해당 CLI의 별도 설치·로그인이 필요합니다.
- 내부 업데이트 서명·무결성 검사, 작업 중 업데이트 차단,
  데이터 보존·실패 복구, 기존 엔진·확장 연결 보안을 유지합니다.
- 자세한 확인 범위와 파일 해시는 릴리즈 안내 및 첨부 파일을 참고하세요.

## AutoPlus에서 ScenePlus ai까지

ScenePlus ai는 자막과 음성으로 영상 한 편을 만드는 개인용 AutoPlus 앱에서 시작했습니다.
이후 TubeWorker에서 필요한 장면만 만들고 넣는 도구로 방향을 바꾸고,
이미지·영상 생성과 모션그래픽을 조합하는 지금의 형태로 발전했습니다.
다른 사용자도 활용할 수 있도록 Google Flow 이미지 생성을 추가하고,
Windows·Mac 설치 및 업데이트 절차를 갖췄습니다.

앱 개발부터 이번 배포까지의 경과 기간은 약 **38일**입니다.
로컬 개발 로그의 잠정 집계는 **캐시 포함 약 29.69억 토큰**,
**캐시 제외 입력·출력 약 7,504만 토큰**입니다.
기간에는 대기·휴식이, 토큰에는 실패와 재작업이 포함되므로 실제 노동시간이나 지출액을 뜻하지 않습니다.

[개발 이야기와 단계별 시간·토큰 집계 읽기](docs/DEVELOPMENT-STORY-KO.md)
