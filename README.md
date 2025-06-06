# 🎮 MPHP

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.5.4-blue.svg)](https://www.unrealengine.com/)
[![Platform](https://img.shields.io/badge/Platform-PC-green.svg)]()
[![License](https://img.shields.io/badge/License-Portfolio-yellow.svg)](LICENSE)
[![Development Status](https://img.shields.io/badge/Status-In%20Development-orange.svg)]()

> (프로젝트 개요)

![MPHP 로고](https://via.placeholder.com/너비x높이/배경색/텍스트색?text=MPHP+Logo)

## 📋 목차

- [프로젝트 소개](#-프로젝트-소개)
- [주요 기능](#-주요-기능)
- [시스템 요구사항](#-시스템-요구사항)
- [설치 방법](#-설치-방법)
- [사용법](#-사용법)
- [개발 환경 설정](#️-개발-환경-설정)
- [팀 정보](#-팀-정보)
- [라이선스](#-라이선스)

## 🎯 프로젝트 소개

### 개요
- **장르**: 로그라이트 액션 경영 시뮬레이션
- **플랫폼**: PC (Windows)
- **개발 엔진**: Unreal Engine 5.5.4
- **개발 기간**: 2025년 06월 ~ 
- **타겟 연령**: 미정

### 미디어
- **스크린샷**: 개발 완료 후 추가 예정
- **데모 영상**: 플레이 가능한 빌드 완성 후 제작 예정
- **개발 로그**: [GitHub Issues](https://github.com/fut71/Project_MPHP/issues)에서 확인 가능

### 게임 스토리
(간단한 게임 스토리)

### 개발 목표
- 🎮 직관적이고 재미있는 게임플레이 제공

## ✨ 주요 기능

### 🎮 게임플레이
- **캐릭터 시스템**: (개발 예정)
- **전투 시스템**: (개발 예정)
- **경영 시스템**: (개발 예정)
- **로그라이트 요소**: (개발 예정)

### 🎯 기술적 특징
- **AI 시스템**: (개발 예정)
- **물리 엔진**: (개발 예정)
- **렌더링**: (개발 예정)
- **네트워킹**: (개발 예정)

### 🎨 아트 스타일
- **비주얼**: (결정 예정)
- **컬러 팔레트**: (결정 예정)
- **UI/UX**: (결정 예정)

## 💻 시스템 요구사항

### 최소 사양
- **OS**: Windows 10 64-bit
- **프로세서**: Intel i5-8400 / AMD Ryzen 5 2600
- **메모리**: 8 GB RAM
- **그래픽**: NVIDIA GTX 1060 / AMD RX 580
- **저장공간**: 20 GB

### 권장 사양
- **OS**: Windows 11 64-bit
- **프로세서**: Intel i7-10700K / AMD Ryzen 7 3700X
- **메모리**: 16 GB RAM
- **그래픽**: NVIDIA RTX 3070 / AMD RX 6700 XT
- **저장공간**: 20 GB (SSD 권장)

### 개발 환경
- **언리얼 엔진**: 5.5.4 이상
- **Visual Studio**: 2022
- **Git LFS**: 대용량 파일 관리 필수
- **메모리**: 32 GB 권장 (에디터 사용 시)

## 🚀 설치 방법

### 플레이어용 (릴리즈 버전)
아직 릴리즈된 버전이 없습니다. 개발 완료 후 배포 예정입니다.

### 개발자용 (소스 빌드)

#### 사전 준비
```bash
# Git LFS 설치 확인
git lfs version

# LFS가 없다면 설치
git lfs install
```

#### 프로젝트 클론
```bash
# 저장소 클론 (시간이 오래 걸릴 수 있음)
git clone https://github.com/fut71/Project_MPHP.git
cd Project_MPHP

# LFS 파일 다운로드
git lfs pull
```

#### 빌드 방법
1. `MPHP.uproject` 파일 우클릭
2. "Generate Visual Studio project files" 선택
3. `MPHP.sln` 파일을 Visual Studio로 열기
4. `Development Editor` 구성으로 빌드
5. 언리얼 에디터에서 프로젝트 열기

## 🎮 사용법

### 개발 현황
- **현재 상태**: 프로젝트 초기 설정 완료 (v0.1.0)
- **다음 목표**: 기본 캐릭터 시스템 구현
- **예상 플레이 가능 시기**: 미정

### 개발 진행도
- [x] 📋 프로젝트 초기 설정 (2025.06.07 완료)
- [ ] 📋 캐릭터 시스템
- [ ] 📋 기본 UI 시스템
- [ ] 📋 경영 시스템
- [ ] 📋 전투 시스템
- [ ] 📋 로그라이트 시스템
- [ ] 📋 사운드 시스템
- [ ] 📋 최적화 및 폴리싱

## 🛠️ 개발 환경 설정

### 브랜치 전략
```
main                 # 안정적인 릴리즈 버전
├── develop         # 개발 통합 브랜치
│   ├── feature/player-movement
│   ├── feature/combat-system
│   └── feature/ui-inventory
├── release/v1.0    # 릴리즈 준비
└── hotfix/bug-fix  # 긴급 버그 수정
```

### 코딩 컨벤션
- **C++ 스타일**: [언리얼 엔진 코딩 표준](https://docs.unrealengine.com/5.3/en-US/epic-cplusplus-coding-standard-for-unreal-engine/) 준수
- **블루프린트**: 명확한 노드 정리 및 주석 작성
- **에셋 네이밍**: `BP_Player`, `M_Stone`, `T_Grass` 등 접두사 사용

### 커밋 메시지 규칙
```
feat: 새로운 기능 추가
fix: 버그 수정
docs: 문서 수정
style: 코드 포맷팅
refactor: 코드 리팩토링
perf: 성능 최적화
test: 테스트 추가
chore: 빌드, 설정 변경

예시:
feat: Add player inventory system with drag&drop
fix: Resolve character animation stuttering issue
perf: Optimize rendering for low-end devices
```

### 이슈 관리
- 🐛 **Bug Report**: 버그 발견 시 상세한 재현 단계 작성
- ✨ **Feature Request**: 새 기능 제안 시 명확한 요구사항 명시
- 📝 **Documentation**: 문서 개선 필요 시
- 🔧 **Refactor**: 코드 개선 필요 시

## 🤝 기여 방법

### 기여 절차
1. 이 저장소를 Fork
2. 새로운 feature 브랜치 생성 (`git checkout -b feature/amazing-feature`)
3. 변경사항 커밋 (`git commit -m 'feat: Add amazing feature'`)
4. 브랜치에 Push (`git push origin feature/amazing-feature`)
5. Pull Request 생성

### 기여 가이드라인
- 코드 작성 전 관련 이슈가 있는지 확인
- 새로운 기능 추가 시 테스트 코드 작성
- Pull Request 시 변경사항에 대한 명확한 설명 제공
- 리뷰어의 피드백에 적극적으로 응답

### 개발 환경 테스트
```bash
# 프로젝트 컴파일 테스트
# Unreal Editor에서 Compile 버튼 클릭

# 패키징 테스트 (릴리즈 전)
# File > Package Project > Windows (64-bit)
```

## 📱 스크린샷 & 영상

### 게임플레이
![게임플레이 1](https://via.placeholder.com/너비x높이/배경색/텍스트색?text=표시할텍스트)
![게임플레이 2](https://via.placeholder.com/너비x높이/배경색/텍스트색?text=표시할텍스트)

### UI/UX
![메인 메뉴](https://via.placeholder.com/너비x높이/배경색/텍스트색?text=표시할텍스트)
![인벤토리](https://via.placeholder.com/너비x높이/배경색/텍스트색?text=표시할텍스트)

### 데모 영상
[![게임 데모 영상](https://img.youtube.com/vi/영상코드/0.jpg)](https://www.youtube.com/watch?v=영상코드)

## 📊 개발 진행도

- [ ] 📋 기본 프로젝트 설정
- [ ] 📋 캐릭터 시스템
- [ ] 📋 기본 UI 시스템
- [ ] 📋 경영 시스템
- [ ] 📋 전투 시스템
- [ ] 📋 로그라이트 시스템
- [ ] 📋 사운드 시스템
- [ ] 📋 최적화 및 폴리싱

## 👥 팀 정보

### 개발팀
- **🎯 팀장**: [이름](https://github.com/fut71)
- **💻 프로그래머**: (팀원 추가 예정)
- **🎨 아티스트**: (팀원 추가 예정)
- **🎮 게임 디자이너**: (팀원 추가 예정)

## 📚 참고 자료

### 공식 문서
- [언리얼 엔진 5 문서](https://docs.unrealengine.com/5.5/)
- [언리얼 엔진 C++ 가이드](https://docs.unrealengine.com/5.5/en-US/unreal-engine-cpp-quick-start/)
- [블루프린트 가이드](https://docs.unrealengine.com/5.5/en-US/blueprints-visual-scripting-in-unreal-engine/)

### 외부 리소스
- [언리얼 엔진 커뮤니티](https://forums.unrealengine.com/)
- [언리얼 엔진 YouTube](https://www.youtube.com/c/UnrealEngine)
- [게임 개발 참고서적](https://www.amazon.com/s?k=unreal+engine+game+development)

## 🐛 알려진 이슈

### 현재 버그
- 현재 존재하는 이슈 없음

### 해결된 이슈
- 해결된 이슈 없음

## 📈 성능 벤치마크

| 설정 | GTX 1060 | RTX 3070 | RTX 4080 |
|------|----------|----------|----------|
| Low | NULL | NULL | NULL |
| Medium | NULL | NULL | NULL |
| High | NULL | NULL | NULL |
| Ultra | N/A | NULL | NULL |

## 🔄 업데이트 로그

### v0.1.0 (2025-06-07)
- 🎉 프로젝트 초기 설정
- 📁 Git 저장소 생성
- 📋 README 및 문서 작성
- 🔧 언리얼 엔진 프로젝트 초기화

## 📄 라이선스

**이 프로젝트는 학습 및 포트폴리오 목적으로 제작되었습니다.**

### 소스코드
- 프로그래밍 기법과 구현 방법은 학습 목적으로 공개
- MIT 라이선스 적용 (참고 및 학습 자유)

### 게임 콘텐츠
- 캐릭터, 스토리, 아트워크, 사운드 등은 **팀 소유**
- 상업적 사용 및 재배포 금지
- All Rights Reserved

### 언리얼 엔진
본 프로젝트는 Epic Games의 언리얼 엔진을 사용하며, [언리얼 엔진 EULA](https://www.unrealengine.com/en-US/eula/unreal)를 준수합니다.

### 상업적 사용
- 현재는 비상업적 목적
- 향후 상업화 시 별도 협의 필요

## ⚠️ 중요 공지

이 프로젝트는 **학습 및 포트폴리오 목적**으로 개발 중인 프로젝트입니다.

- 🎓 **학습 목적**: 언리얼 엔진과 게임 개발 기술 학습
- 💼 **포트폴리오**: 개발 능력 및 프로젝트 관리 경험 축적
- 🚫 **상업적 사용**: 현재 금지
- 🔄 **향후 계획**: 성공적으로 완성 시 상업화 검토 예정

**문의사항**: doyo9607@gmail.com

---

**📞 문의사항이나 버그 신고는 [Issues](https://github.com/fut71/Project_MPHP/issues) 페이지를 이용해주세요!**

⭐ **이 프로젝트가 도움이 되었다면 Star를 눌러주세요!** ⭐
