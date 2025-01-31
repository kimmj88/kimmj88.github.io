2024.10 ~ present

### Development period

- 2024.10 ~ present

### Project Description

Software Lifecycle Management(SLM) 솔루션은 ASPICE 프로젝트를 수행하는 개발팀이 프로젝트 관리 및 산출물 관리를 효율적으로 수행할 수 있도록 개발된 시스템입니다. NestJS 기반의 백엔드, Vuetify 기반의 프론트엔드, PostgreSQL 데이터베이스를 활용하여 구축되었으며, 인증 방식으로 Azure Entra ID(OAuth)를 연동하여 안전한 로그인 및 사용자 관리를 지원합니다.

### Developer Skill

- Frontend: Vue.js + Vuetify
- Backend: NestJS (Node.js 기반)
- Database: PostgreSQL
- Authentication: Azure Entra ID (OAuth)
- Deployment: Docker 컨테이너 기반 MSA 아키텍처
- Storage : OneDrive

### Main Feature

- OAuth 기반의 인증 시스템

  - Azure Entra ID(OAuth 2.0)와 연동하여 안전한 사용자 인증 제공
  - JWT 기반의 인증 및 권한 관리

- 프로젝트 및 산출물 관리

  - ASPICE 프로젝트 수행 시 요구되는 프로젝트 생성 및 관리 기능
  - 프로젝트별 산출물을 체계적으로 보관하고 접근 권한을 설정

- 소프트웨어 라이프사이클 단계별 트래킹

  - 프로젝트 계획, 개발, 검증, 배포 단계별 진행 상황을 가시적으로 제공
  - 프로세스 준수를 위한 이력 관리

- MSA 아키텍처 기반 확장성 확보

  - Docker를 활용한 마이크로서비스 아키텍처(MSA) 도입
  - 인증 서버(NestJS)와 데이터 서버를 분리하여 확장성 및 유지보수성 향상

- PostgreSQL 기반의 데이터 관리

  - 관계형 데이터베이스인 PostgreSQL을 활용하여 데이터 무결성 및 성능 최적화
  - 프로젝트별 데이터 스키마 설계 및 최적화

### Project Preview

- Login Page
  <div class="gallery">
    <a href="/assets/images/slm/slm_login.png" data-fancybox="gallery" data-caption="Elegant Paper Swan">
      <img src="/assets/images/slm/slm_login.png" alt="Origami Swan">
    </a>
    <a href="/assets/images/slm/slm_login_ms.png" data-fancybox="gallery" data-caption="Elegant Paper Swan">
      <img src="/assets/images/slm/slm_login_ms.png" alt="Origami Swan">
    </a>
  </div>

- Project List Page
  <div class="gallery">
    <a href="/assets/images/slm/slm_projects.png" data-fancybox="gallery" data-caption="Elegant Paper Swan">
      <img src="/assets/images/slm/slm_projects.png" alt="Origami Swan">
    </a>
  </div>

- Dashboard Page
  <div class="gallery">
    <a href="/assets/images/slm/slm_dashboard.png" data-fancybox="gallery" data-caption="Elegant Paper Swan">
      <img src="/assets/images/slm/slm_dashboard.png" alt="Origami Swan">
    </a>
  </div>

- Artifact List Page
  <div class="gallery">
    <a href="/assets/images/slm/slm_artifacts.png" data-fancybox="gallery" data-caption="Elegant Paper Swan">
      <img src="/assets/images/slm/slm_artifacts.png" alt="Origami Swan">
    </a>
  </div>

### Reference

- [Test Docker 배포환경설정](https://www.notion.so/CI-CD-with-MacOS-6557cee1ae0e4bc4adce24b45720548c)

### Source Repository
