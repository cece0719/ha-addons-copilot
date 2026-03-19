# Development Rules

이 파일은 ha-addons-copilot 프로젝트 개발 시 따라야 할 규칙을 정의합니다.

## Rule 1: Version Update on Code Changes

코드 변경이 있을 때마다 해당 애드온의 `config.yaml` 파일에서 버전을 하나 올린다.

**규칙:**
- 코드 수정/추가 발생 시 `config.yaml`의 `version` 필드를 하나 증가시킨다
- 예: `1.0.0` → `1.0.1` (패치 버전 증가)
- 예: `1.0.1` → `1.1.0` (마이너 버전 증가, 주요 기능 추가 시)
- 예: `1.1.0` → `2.0.0` (메이저 버전 증가, 큰 변화 시)

**실행 시점:**
- 모든 코드 변경 후
- config.yaml 파일이 변경되는 경우는 제외

---


