# RacingCoach Voice Studio

Qwen3-TTS 목소리로 한국어 레이싱 무전 음성팩을 만들고, 직접 들어보며 개선하는 Windows 프로그램입니다.

**[Voice Studio 0.2.0 앱 업데이트 패치](https://github.com/elsalvadoruk-hue/racingcoach-voice-studio-releases/releases/tag/v0.2.0)**

기존 **0.1.16 통합 배포판 사용자용**입니다. 앱만 교체하므로 기존 2GB 설치 ZIP이나 Qwen 생성 도구를 다시 받을 필요가 없습니다.

1. 제작기를 정상 종료하고, 0.2.0 릴리스의 앱 패치 ZIP을 받습니다.
2. ZIP을 **기존 설치 폴더 밖**에 풉니다.
3. **Update.bat**를 누르고 기존 **Start.bat가 있는 VoiceStudio 폴더**를 선택합니다.
4. 완료 안내 후 기존 폴더의 **Start.bat**로 실행합니다.

기존 `data`의 프로젝트·녹음·모델·생성 음성·검수와 생성 환경을 보존합니다. 이전 앱은 `app-backups`에 남기며 실패 시 복구합니다. 패치만으로 생성·학습을 자동 시작하지 않습니다. 실행 중이거나 다른 버전이면 적용하지 않고 이유를 알려줍니다.

0.2.0은 선택적인 RVC 음색 변환, 받은 RVC 모델 다운로드와 WAV 비교, 내 녹음의 분할·직접 검수·학습·이어하기, 단계별 다음 버튼·오류 해결 안내와 진행 수량/예상 시간을 제공합니다. RVC는 기본 OFF이며 처음 사용할 때 별도 변환·학습 도구를 앱에서 준비합니다. 기존 Qwen 환경은 재사용합니다.

## 처음 설치하는 경우

먼저 **[0.1.16 통합 배포판](https://github.com/elsalvadoruk-hue/racingcoach-voice-studio-releases/releases/tag/v0.1.16)**의 ZIP 전체를 풀고 **VoiceStudio/Start.bat**로 초기 준비를 마친 뒤 정상 종료하고 0.2.0 패치를 적용하세요. 기존 통합 배포 파일은 변경하지 않았습니다. 0.2.0 패치만으로 새 설치 환경 전체가 제공되지는 않습니다.

Windows x64와 NVIDIA CUDA GPU·호환 드라이버가 필요합니다. 기본 생성 도구·모델에 약 15GB 이상과 작업 음성을 저장할 추가 공간이 필요하며, RVC 전용 도구는 별도로 수 GB 이상을 사용합니다. 모델은 앱에서 선택해 다운로드합니다. Python·PyTorch 경로를 직접 입력하거나 명령어를 실행하지 않습니다. 실제 새 PC/다른 GPU의 설치 성공이나 모델별 음질을 보장하지 않습니다.

50개 시험·직접 검수·ChatGPT 개선·재생성을 반복한 뒤 만족하면 전체 제작과 역할별 팩 내보내기로 진행합니다. 자동 검사 통과는 청취 승인이 아닙니다. 이 저장소는 배포 파일과 안내용이며 모델·개인 프로젝트·완성 음성팩은 포함하지 않습니다.

## 한국어 매뉴얼

**[0.2.0 개선판 스크린샷 매뉴얼 · 개정 2](https://github.com/elsalvadoruk-hue/racingcoach-voice-studio-releases/releases/tag/manual-v0.2.0-1)**에서 최신 HTML 또는 ZIP을 받으세요. 기존 릴리스 첨부파일을 교체했습니다. **38개 장·번호 화면 50장**으로 공개 16.5MB 패치 설치, 다음 단계 이동, 진행률·남은 시간·완료 예상, 파일 선택 대기, 원인별 해결·재시도를 안내합니다. HTML은 브라우저에서 오프라인 검색·인쇄할 수 있습니다. [저장소 원본 문서](index.html)도 제공합니다. 34장의 따라하기 체크·메모를 TXT로 저장하며 테스트할 수 있습니다.

매뉴얼 화면은 개인 자료가 없는 예제입니다. 최신 0.2.0 설명 화면 18장과 0.1.16 공통 참고 화면 32장을 구분했습니다. 데이터셋 CPU 분할·ZIP·잘못된 WAV 오류는 실제 응답이며, GPU 학습 상태·HF 목록·진행 수량/예상 시간·파일 선택 대기는 모의 예시로 표시했습니다. 실제 모델 품질의 검증 자료가 아닙니다. [0.1.16 매뉴얼](https://github.com/elsalvadoruk-hue/racingcoach-voice-studio-releases/releases/tag/manual-v0.1.16-1)은 이전 버전 기록으로 유지합니다.
