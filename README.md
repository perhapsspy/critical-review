# Critical Review

[English](README.en.md)

코드·기획·설계와 관련 산출물이 원래 목적을 충족하는지, 충분한지와 과한지를 간결하게 검토하는 에이전트 스킬입니다. 근거와 반례로 판단하고 지적 자체도 반증합니다. 유의미한 문제가 없으면 그렇게 보고합니다.

## 사용

Project Legibility 플러그인의 공통 스킬 snapshot으로 Codex와 Claude Code에 제공합니다. 플러그인 설치 경로는 [Project Legibility](https://github.com/perhapsspy/project-legibility#readme)에서 확인합니다. 로컬 개발본의 설치 검증은 게시와 구분합니다.

```text
$critical-review 이 코드와 설계가 원래 요구를 충족하는지, 빠진 것과 불필요한 것이 있는지 봐줘. 수정하지 마.
```

검토·재검토·자기 제안의 반증과 요청된 최종 점검에 사용합니다. 일반 구현·요약·문장 교정에 자동 참여하지 않습니다. 리뷰만 요청하면 진단으로 끝내며, 이미 승인된 수정은 재검증까지 마칩니다.

## 정본

- 배포 계약: [SKILL.md](skills/critical-review/SKILL.md)
- 한국어 본문: [SKILL.ko.md](skills/critical-review/SKILL.ko.md)
- 플러그인 구성·배포: [Project Legibility](https://github.com/perhapsspy/project-legibility)

이 저장소가 의미·선택 조건·실행 방식의 정본입니다. 플러그인은 이 저장소의 commit에서 생성한 snapshot을 소유합니다.

## 라이선스

[MIT](LICENSE)
