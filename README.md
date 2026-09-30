# ATAD 릴리즈 노트

프로젝트별 변경 사항을 매주 수요일에 Markdown으로 기록합니다. 한 파일에는 해당 주의 릴리즈 내용을 담습니다.

## 폴더 구조

```text
ATAD_RELEASE_NOTES/
├── README.md
├── template.md
├── ODIIN/
├── MSP/
└── ASGARRD/
```

릴리즈 노트 파일은 `[프로젝트명]/YYYYMM/YYYY-MM-DD.md` 경로에 저장합니다.

## 작성 방법

1. [template.md](./template.md)를 복사해 해당 프로젝트의 월별 폴더에 `YYYY-MM-DD.md`로 저장합니다.
2. 프로젝트명과 날짜를 바꾸고, 해당 주에 실제로 반영된 내용만 적습니다.
3. `feature`, `change`, `fixed`, `deprecated`, `removed` 중 필요한 태그만 남깁니다. 같은 태그에 변경 사항이 여러 개면 제목과 내용을 이어서 추가합니다.
4. 각 항목은 제목과 사용자에게 미치는 영향을 적습니다. `deprecated`에는 지원 종료 예정일과 대체 방법을, `removed`에는 제거 내용과 대체 방법을 적습니다.

아직 확정되지 않은 변경 사항이나 가상 예시는 실제 릴리즈 노트에 넣지 않습니다.
