<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 에어라이더 (AirRider)

에어모빌로 하늘을 나는 PC 온라인 레이싱 게임

> **경고: Lab Track 참가 승인을 받은 창작자만 이용할 수 있습니다.** 승인받지 않은 사내 제작, 학습, 연구, 개인 공부, 상업 등 목적과 관계없이 모든 이용을 제한합니다.

> 이용 조건은 저장소 루트의 [LICENSE](LICENSE) 와 [NOTICE](NOTICE) 를 따릅니다. 뷰어: [이 게임을 뷰어로 보기](https://nexon-replay.github.io/Boomhill/#/g/airrider). 세계관과 다른 게임은 [허브](https://nexon-replay.github.io/Boomhill/)에 있습니다.

## 폴더

| 폴더 | 내용 |
|---|---|
| `2d/` | 2D 그림: 묶음마다 폴더 하나, 그림은 PNG(여러 프레임이면 스프라이트 시트)와 아틀라스 JSON |
| `3d/` | 3D 미리보기 모델: 분류마다 폴더 하나. `<id>.glb` 모델, `<id>.webp` 썸네일, `<id>.json` 부가 정보 |
| `3d/_shared/` | 여러 모델이 나눠 쓰는 텍스처, 표정 그림, 조립 파츠(이름은 원래 이름_짧은 해시) |
| `2d/manifest.json`, `3d/manifest.json` | 파일마다 크기와 SHA-256 |

## 2D 그림

| 묶음 | 제목 | 그림 | 프레임 |
|---|---|---:|---:|
| `010_gui` | HUD, 게이지, 결과창 | 519 | 519 |
| `020_stage` | 화면(로비, 방, 상점, 튜토리얼) | 722 | 722 |
| `030_dialog` | 대화 상자 | 360 | 360 |
| `040_character` | 캐릭터 텍스처 | 491 | 491 |
| `050_airmobile` | 에어모빌 텍스처 | 254 | 254 |
| `060_item` | 아이템 | 168 | 168 |
| `070_effect` | 효과 | 135 | 135 |
| `080_myroom` | 마이룸 | 47 | 47 |
| `090_card` | 수집 카드, 상점, 로딩 | 582 | 582 |
| `100_etc` | 기타 | 147 | 147 |
| | 합계 | 3,425 | 3,425 |

## 3D 미리보기 모델

브라우저에서 바로 보는 미리보기입니다(압축 GLB, 텍스처 긴 변 512px, 캐릭터는 기본 동작만). 게임 제작, 편집에는 아래 원본 zip 을 쓰세요.

| 폴더 | 분류 | 모델 |
|---|---|---:|
| `3d/010_airmobile/` | 에어모빌 | 27 |
| `3d/020_character/` | 캐릭터 | 27 |
| `3d/030_track/` | 트랙 | 28 |
| `3d/040_boss/` | 보스 | 3 |
| `3d/050_model/` | 부품, 기타 모델 | 643 |
| | 합계 | 728 |

## 3D 원본 zip

압축하지 않은 GLB, 원래 해상도 PNG 텍스처, 전체 동작을 분류마다 묶었습니다. 저장소의 Releases 에서 받습니다.

| 분류 | 파일 | 크기 | 모델 |
|---|---|---:|---:|
| 에어모빌 | [airrider-3d-airmobile.zip](https://github.com/NEXON-REPLAY/Boomhill-AirRider/releases/download/3d-originals-v1/airrider-3d-airmobile.zip) | 3.6MB | 27 |
| 보스 | [airrider-3d-boss.zip](https://github.com/NEXON-REPLAY/Boomhill-AirRider/releases/download/3d-originals-v1/airrider-3d-boss.zip) | 1.2MB | 3 |
| 캐릭터 | [airrider-3d-character.zip](https://github.com/NEXON-REPLAY/Boomhill-AirRider/releases/download/3d-originals-v1/airrider-3d-character.zip) | 8.2MB | 27 |
| 부품, 기타 모델 | [airrider-3d-model.zip](https://github.com/NEXON-REPLAY/Boomhill-AirRider/releases/download/3d-originals-v1/airrider-3d-model.zip) | 119.0MB | 643 |
| 트랙 | [airrider-3d-track.zip](https://github.com/NEXON-REPLAY/Boomhill-AirRider/releases/download/3d-originals-v1/airrider-3d-track.zip) | 168.4MB | 28 |

형식은 [허브 저장소의 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md), 쓰는 법은 [자료 안내](https://nexon-replay.github.io/Boomhill/guide.html)에 있습니다.
