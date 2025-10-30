# QA 자동화 + CI/CD 통합 시스템 🚀
 
> **PR 올리면 자동 테스트 → 실패 시 Slack 알림**

## 기술 스택
| 기술 | 사용 예시 |
|------|----------|
| Selenium | 로그인, 회원가입 자동화 |
| Postman | 50개 API 테스트 |
| SQL | DB 데이터 검증 |
| GitHub Actions | CI/CD 자동 실행 |
| Jira | 버그 5개 등록 (스크린샷 포함) |
| Git | 브랜치 전략 + 커밋 로그 |

## 자동화 데모 (30초)
![demo](demo.gif)

## CI/CD 배지 (실시간 증명!)
[![CI](https://github.com/your-id/QA-Automation-Pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/your-id/QA-Automation-Pipeline/actions)

## 실행 방법
```bash
git clone https://github.com/your-id/QA-Automation-Pipeline
pip install -r requirements.txt
pytest tests/ -v
