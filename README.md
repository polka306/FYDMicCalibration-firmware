# FYD Mic Calibration Tool — 펌웨어 (Firmware)

FPGA 보드(**Arty S7-25 / xc7s25csga324**)용 **펌웨어 이미지(`.mcs`)** 배포 저장소입니다.
앱 인스톨러와 독립적으로 펌웨어 버전을 관리합니다.

## 다운로드

👉 **[Releases](../../releases)** 에서 보드에 맞는 펌웨어를 받으세요.

- 최신: `FYD_Caltool_ARTYS725_v1_5_2604071058.mcs` (tag `fw-v1.5`)

## 적용 방법

1. FYD Mic Calibration Tool 설치 (인스톨러: **[FYDMicCalibration-dist](https://github.com/polka306/FYDMicCalibration-dist)**)
2. `.mcs` 파일을 설치 폴더의 `firmware\` 에 복사
3. 앱에서 **Setting → Firmware Update** → 파일 선택 → 기록 (Flash)

> 참고: SRAM(`.bit`) 임시 다운로드와 달리 `.mcs`는 SPI Flash에 영구 기록됩니다.
> 보드 USB 드라이버는 최초 1회 Zadig으로 인터페이스 0을 WinUSB로 설정해야 할 수 있습니다.
