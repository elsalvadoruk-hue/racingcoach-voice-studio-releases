# RacingCoach Voice Studio

원하는 Qwen3-TTS 목소리로 한국어 레이싱 무전 음성팩을 만들고, 들어보며 개선하는 Windows 프로그램입니다.

**[Voice Studio 0.1.16 다운로드](https://github.com/elsalvadoruk-hue/racingcoach-voice-studio-releases/releases/tag/v0.1.16)**

1. 릴리스의 **RacingCoach-Voice-Studio-0.1.16-win-nvidia-x64.zip**을 받습니다.
2. ZIP 전체를 풉니다.
3. **VoiceStudio 폴더의 Start.bat**을 누릅니다. 처음에는 포함된 음성 도구를 풀며 몇 분 걸릴 수 있습니다.
4. 열린 화면에서 대본과 목소리 모델을 선택하세요.

Python·PyTorch·Qwen 실행 도구·C++ 런타임은 포함돼 있습니다. 목소리 모델은 앱에서 골라 다운로드합니다. Windows x64와 NVIDIA CUDA 그래픽 카드·호환 드라이버가 필요합니다. 도구에 약 10GB와 모델·생성 음성을 저장할 추가 공간을 확보하세요.

50개 표본 생성과 검수·ChatGPT 수정·재생성을 반복한 뒤 전체 제작과 역할별 커스텀팩 내보내기로 이어갑니다. 작업은 `data` 폴더에 저장됩니다.

초기 공개판이며 Windows/RTX 5090에서 검증했습니다. 실제 새 PC·다른 GPU의 결과와 구분합니다. 이 저장소에는 배포 파일과 사용 안내만 올립니다. 음성 모델·완성 음성팩·개인 작업 파일은 배포에 포함하지 않습니다.

## 한국어 사용 매뉴얼

**[스크린샷 포함 매뉴얼 다운로드](https://github.com/elsalvadoruk-hue/racingcoach-voice-studio-releases/releases/tag/manual-v0.1.16-1)**

매뉴얼 릴리스에서 `RacingCoach-Voice-Studio-0.1.16-manual-ko.html`을 받아 브라우저로 여세요. 앱 설치 파일과 별도로 제공하는 문서입니다.

28개 장과 화면 33장으로 첫 실행, 제작 역할 선택, 대본·숫자 범위, 모델·화자, 50개 시험과 검수, ChatGPT 개선, 전체 제작, 팩 저장과 프로젝트 관리를 안내합니다. 스포터·경기 안내·전략·연료·코치 중 원하는 역할만 제작하는 방법도 포함합니다.

그림의 빨간 번호를 설명과 맞춰 보고, 그림을 눌러 확대할 수 있습니다. 이미지가 HTML 안에 포함되어 파일 하나로 오프라인 열람·검색·인쇄·PDF 저장이 가능합니다. 저장소의 원본 문서는 [index.html](index.html)입니다. GitHub 파일 화면에서는 HTML 소스가 표시되므로 내려받아 여세요.

설명 화면은 개인 자료가 없는 예제 프로젝트입니다. 모델·GPU 상태는 모의이며 검수·팩 저장에는 무음 예제를 사용했습니다. 실제 합성 성능이나 음질의 검증 자료는 아닙니다.
