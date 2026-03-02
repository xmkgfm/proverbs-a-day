# proverbs-a-day

한국어로 매일 잠언 본문을 보내는 OpenClaw 스킬입니다.

## 포함 파일

- `SKILL.md` - 스킬 정의 파일
- `proverbs-a-day.skill` - 배포용 패키지 파일

## 기본 동작

- 매일 **06:00** (로컬 시간) 발송
- 날짜의 일(day) 숫자 `N`을 잠언 `N`장에 매핑 (1-31)
- 각 절을 `1절`, `2절` 형식으로 표기한 전체 본문 출력

## 설치 방법

`proverbs-a-day.skill` 파일을 OpenClaw 스킬에 가져오면 됩니다.

---

OpenClaw skill for sending the daily Proverbs chapter in Korean.

## Included

- `SKILL.md` - skill definition
- `proverbs-a-day.skill` - packaged distributable file

## Default behavior

- Sends at **06:00** (local time)
- Uses day-of-month mapping: day `N` -> Proverbs chapter `N` (1-31)
- Outputs full chapter with verse markers (`1절`, `2절`, ...)

## Install

Import `proverbs-a-day.skill` into your OpenClaw skills.
