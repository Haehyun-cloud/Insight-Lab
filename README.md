# InsightLab

InsightLab은 과학 논문을 원문 근거와 분석 경계를
추적하면서 번역·구조화·비판적 해석·학습 문서화를 지원하는 연구 학습
workflow입니다.

## Purpose

과학 논문을 공부할 때는 본문의 순서대로 읽는 것만으로 연구 질문,
실험 설계, 결과 사이의 관계와 해석 한계를 한 번에 파악하기 어렵습니다.
InsightLab은 역할이 구분된 분석 단계와 validation을 결합하여
다음을 돕는 것을 목표로 합니다.

- 원문과 번역의 범위를 빠짐없이 대응시킵니다.
- 실험 방법, 관찰 결과와 연구자의 해석을 구분합니다.
- 내부 실험 근거와 외부 문헌 맥락을 서로 다른 경로에서 다룹니다.
- 주장, Figure/Table, source locator와 downstream 문서 사이의 provenance를
  보존합니다.
- 자동 검증과 사람이 판단해야 할 과학적·편집적 검토를 구분합니다.
- 실패한 단계만 안전하게 재개하고 이미 검증된 결과의 불필요한 재실행을
  줄입니다.

## Outputs

| Output | Description |
|---|---|
| Translation Note (TN) | 논문의 구성과 정보 순서를 보존하는 전체 번역본 |
| Learning Note (LN) | 연구 질문, 설계, 방법, 결과, 문헌 맥락과 비판적 경계를 통합한 학습 노트 |
| Human Refined Learning Note (HRLN) | 검증된 사용자 학습 요청을 별도 revision으로 반영한 Learning Note |
| Concept Note (CN) | 논문에서 선택된 핵심 개념을 재사용 가능한 설명으로 정리한 노트 |
| Scientific Report (RP) | 검토된 학습 내용과 원문 사실을 통합한 최종 전문 학습 문서 |

## Documentation

- [Workflow and Agent Roles](WORKFLOW.md)
- [Example Scientific Report](reports/Parkin%20overexpression%20protects%20from%20ageing-related%20loss%20of%20muscle%20mass%20and%20strength.md)

## Public Scope

이 저장소는 InsightLab의 목적, workflow와 선별된 예시 산출물을 소개하는
showcase입니다. 다음 자료는 포함하지 않습니다.

- production source code와 provider adapter
- system prompt와 canonical schema 전문
- 원문 PDF, supplementary files와 원본 Figure/Table
- API key, 인증정보와 로컬 환경 설정
- 개인 Vault, 원시 provider response, rejected artifact와 checkpoint
- 내부 canonical JSON, audit database와 논문별 작업 기록

Report는 학습 workflow의 출력 형태를 보여주기 위한 문서이며 원 논문
자체를 대체하지 않습니다. 연구 내용의 확인과 인용에는 Report에 표시된 DOI
및 정식 출판 기록을 사용해야 합니다.

## Status

InsightLab은 현재 반복 검증 중인 개인 연구 학습 프로젝트입니다. 이 공개
저장소는 실행 가능한 배포판이나 hosted service가 아니라 설계와 결과 형식을
설명하기 위한 제한된 공개 자료입니다.
