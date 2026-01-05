# SunRise
무.려. AI를 활용해서 제작된 해돋이용 패브릭 모드

이 모드는 [각별님의 RealTime 플러그인](https://github.com/noonmaru/realtime)을 패브릭(Fabric) 환경에 맞춰 포팅하고, 몇 가지 새로운 기능을 추가하여 제작되었습니다.
### 실행 환경

* Java 21
* 패브릭 1.21.11

### 적용법

1. [Releases](https://github.com/1COWOO/SunRise/releases) 페이지에서 파일을 다운로드합니다. (파일명에 `-sources`가 없는 것을 받으세요.)
2. 서버 실행 후 서버의 `config/sunrise/realtime.json`를 수정합니다.

-**한국 표준시:** `"timezone": -9` (UTC+9 적용)

### ✨모드의 기능
1. 폭죽을 왼손들기 할 시 **"Happy New Year"** 문구와 함께 화려한 폭죽이 터집니다.
2. 현재 시각과 다음 일출/일몰까지의 남은 시간을 실시간으로 계산하여 표시합니다.

### 🛠️수정하고 싶은 분들이 참고해야 할 점
1. **언어:** 코틀린이 아닌 순수 **Java**로 작성되었습니다.
2. **코드 품질:** 첫 개발이라 주석이 부족하고 구조가 투박할 수 있습니다. (너그러운 양해 부탁드립니다.)

### 📦빌드 방법
```bash
git clone https://github.com/1COWOO/SunRise
cd SunRise
./gradlew build
# 생성된 파일은 build/libs 폴더에서 확인 가능합니다.
```
### ⚠️주의점 
유튜브 같은 플랫폼에서 사용할시 이 깃허브 링크 혹은 [유튜브 채널](https://youtube.com/@KOWOO코우)을 영상 설명창에 써주세요.

### 📜라이센스

이 프로젝트는 [GNU General Public License v3.0(GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.html) 라이센스 하에 배포됩니다. 이 라이센스는 다음과 같은 권리를 허용합니다:

- 이 소프트웨어의 사용, 복사, 수정, 배포 및 판매
- 소스 코드에 대한 접근
- 수정한 버전을 동일한 라이센스로 배포

단, 다음 조건을 만족해야 합니다:
- 라이센스 및 저작권 고지를 유지
- 소스 코드의 변경 사항을 명시
- 동일한 GPL-3.0 라이센스로 배포
- 파생 저작물에 대한 소스 코드 공개

자세한 내용은 LICENSE 파일을 참조하세요.
