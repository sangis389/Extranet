# OHMYHOTEL&CO · Extranet 고도화 프로토타입

OHMYHOTEL.biz Extranet 재구축(Master v2.3) — **PRD v1.0** 기반 클릭 가능한 프로토타입.

## 🔗 라이브 데모
배포 후: **https://sangis389.github.io/Extranet/**

## 구성
| 경로 | 설명 |
|------|------|
| `index.html` | 배포 진입점 (프로토타입 단일 파일) |
| `prototypes/extranet/bundle.html` | 동일 프로토타입 원본 |
| `docs/specs/extranet/` | 기능 기획서(ko/en) · UI DSL |
| `.github/workflows/deploy.yml` | GitHub Pages 자동 배포 |

## 구현 범위 (PRD Phase-1)
- 디자인 시스템: Orange #FF6000 + Green #009538, 4그룹 내비게이션, 스테이지 배지(1ST/NEW/EXT)
- 핵심 화면: Today · Performance · Property Health · Opportunity Center · Calendar · Channel Matrix · Discount Stack Simulator · Demand Forecast
- ELLIS Trader 권한 모델(Self/Approval/Admin) · 1-Click Apply

## 자동 배포
`main` 브랜치에 push하면 GitHub Actions가 GitHub Pages로 자동 배포합니다.
