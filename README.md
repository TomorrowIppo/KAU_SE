# 🚀 Resilience Drone-P2P: 재난 대비 드론 메쉬 네트워크

본 리포지토리는 재난 상황에서 중앙 서버 없이 드론 간 P2P 통신을 통해 임시 망을 구축하는 시스템의 개발 과정을 담고 있습니다.

---

## 📂 Repository Structure (리포지토리 구조)
교수님 지침에 따라 `main` 브랜치를 기준으로 다음과 같이 구성되어 있습니다.

```text
.
├── README.md                 # 프로젝트 메인 설명 및 과제 위치 명시
├── doc/                      # 과제 관련 문서 (품질/프로젝트 정의서)
│   ├── project_definition.md # 재난 대비 P2P 드론 네트워크 정의서
│   └── quality_definition.md # 신뢰성 및 가용성 중심 품질 정의서
└── src/                      # 소스 코드 및 관련 파일
    ├── build_guide.md        # Python 3.13.3 기반 빌드 가이드
    └── main.py               # 드론 노드 인터페이스 설계 (Python)
