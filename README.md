![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=250&section=header&text=JinYunSe&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Android%20%26amp%3B%20Game%20Developer&descSize=22&descAlignY=55&descColor=a5c8ff)

<div align="center">

<h2>네 번의 수상, Android·게임·AI 개발을 경험한 개발자 진윤세입니다.</h2>

**Android 앱 개발 · Unity 멀티플레이 · 게임 서버 설계 · 실시간 AI 파이프라인 · Electron 데스크탑**

좋은 코드로 좋은 경험을 만드는 것이 개발의 본질이라 생각합니다.<br>
모바일, 게임, 그리고 실시간 AI 번역 서비스까지 서로 다른 도메인에서의 도전을 통해 그 답을 찾아왔습니다.

[![Email](https://img.shields.io/badge/dbstp1234%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:dbstp1234@naver.com)
[![Blog](https://img.shields.io/badge/Tech%20Blog-FF5722?style=flat-square&logo=tistory&logoColor=white)](https://kagan-draca.tistory.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%EC%9C%A4%EC%84%B8-%EC%A7%84-35ab10383/)

</div>

<h2>🚀 Tech Stack 🚀</h2>

<h3>💬 Language</h3>

[![My Skills](https://skillicons.dev/icons?i=c,cpp,cs,java,kotlin,js,ts,py)](https://skillicons.dev)

<h3>📱 Android</h3>

[![My Skills](https://skillicons.dev/icons?i=androidstudio,flutter)](https://skillicons.dev)
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jetpackcompose/jetpackcompose-original.svg" height="50" alt="Jetpack Compose"/>

<h3>🎮 Game</h3>

[![My Skills](https://skillicons.dev/icons?i=unity)](https://skillicons.dev)

<h3>💻 Backend</h3>

[![My Skills](https://skillicons.dev/icons?i=nodejs,spring,mysql,redis)](https://skillicons.dev)

<h3>🌐 Web / Desktop</h3>

[![My Skills](https://skillicons.dev/icons?i=html,css,react,electron)](https://skillicons.dev)

<h3>🏗️ Infra</h3>

<img src="assets/ec2.png" height="50" alt="AWS EC2"/>&nbsp;&nbsp;<img src="assets/rds.png" height="50" alt="AWS RDS"/>&nbsp;&nbsp;<img src="assets/s3.png" height="50" alt="AWS S3"/>

<h3>⚙️ Tools</h3>

[![My Skills](https://skillicons.dev/icons?i=git,github,gitlab,notion,figma)](https://skillicons.dev)
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg" height="50" alt="Jira"/>

<h2>📊 GitHub Stats & Most Used Languages</h2>

<img src="https://github-readme-stats-sigma-five.vercel.app/api?username=JinYunSe&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true" width="49%" alt="GitHub Stats" /><img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=JinYunSe&layout=compact&theme=tokyonight&hide_border=true" width="49%" alt="Top Langs" />

<h2>🧩 BOJ / Solved.ac</h2>

<a href="https://solved.ac/wlsdbstp1234"><img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=wlsdbstp1234" width="49%" alt="Solved.ac Profile" /></a>
<a href="https://solved.ac/wlsdbstp1234"><img src="http://mazandi.herokuapp.com/api?handle=wlsdbstp1234&theme=warm" width="49%" alt="mazandi profile" /></a>

[![Algorithm](https://img.shields.io/badge/Algorithm%20Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JinYunSe/Algorithm)

<br>

<h2>💻 Projects 💻</h2>

<details>
<summary><b>1. Skill-Gacha — 🥈 내일배움캠프 Node 6기 최종 프로젝트 우수상 (16팀 중 2등) | 다양한 스킬을 전략적으로 조합하는 턴제 MORPG 게임</b></summary>
<br>

> **2024.11.13 ~ 2024.12.23** · 5명 · FullStack

#### 담당 역할

Node.js TCP 게임 서버 개발 및 Unity 클라이언트 개발. 서버-클라이언트 통신 설계, 게임 로직 구현, Protobuf 패킷 처리

#### 프로젝트를 통해 배운 점

| 배운 점 | 구체적 내용 |
|:---|:---|
| **TCP 소켓 + Protobuf 통신** | Node.js TCP 서버와 Unity 클라이언트 간 Protobuf 직렬화/역직렬화로 바이너리 패킷 통신 구현 |
| **상태 머신 기반 게임 플로우** | GameState 추상 클래스 기반으로 던전·PVP·레이드 등 복잡한 게임 흐름을 상태 전이로 관리 |
| **Bull Queue 매칭 처리** | Redis 기반 Bull Queue로 PVP/레이드 매칭의 원자성 확보, 동시성 문제 해결 |
| **Redis 캐싱 전략** | MySQL 쿼리 결과를 Redis에 캐싱하여 DB 부하 감소 |
| **트러블슈팅 경험** | Singleton 이중 생성(경로 대소문자 이슈), Bull Queue 소켓 유실, async-lock 데드락 등 실제 서버 문제 해결 |

#### 사용 기술

| 영역 | 기술 |
|:---|:---|
| **Server** | `Node.js`, `ES Modules`, `TCP Socket` |
| **Serialization** | `Protocol Buffers (protobufjs)` |
| **Database** | `MySQL2`, `Redis` |
| **Queue** | `Bull` |
| **Client** | `Unity`, `C#` |
| **Logging** | `Winston`, `winston-daily-rotate-file` |
| **Validation** | `Zod` |
| **Infra** | `AWS`, `Docker`, `GitHub Actions`, `Prometheus`, `Grafana` |

**[GitHub Repository](https://github.com/Skill-Gacha/Skill-Gacha-Server)**

</details>

<br>

<details>
<summary><b>2. Closetory — 🏆 SSAFY 공통 프로젝트 우수상 (12팀 중 1등) | 옷장 정리부터 AI 코디 추천까지 스마트하게</b></summary>
<br>

> **2026.01.06 ~ 2026.02.10** · 6명 · Android FrontEnd

#### 담당 역할

Android 앱 전체 프론트엔드 단독 개발. 옷장 CRUD·상세조회, 카메라·갤러리 연동, On-Device AI(배경 제거·누끼 따기), 옷 보정, AI 코디 추천, 남의 옷 가져오기·커뮤니티, JWT 자동 갱신, 통계 차트까지 클라이언트 전 기능 구현

#### 프로젝트를 통해 배운 점

| 배운 점 | 구체적 내용 |
|:---|:---|
| **On-Device AI 배경 제거** | ML Kit·MediaPipe 기반으로 옷 사진에서 배경을 기기 내에서 직접 제거(누끼)하고, 필요 시 서버 AI와 병행 처리하는 구조 설계 |
| **카메라·갤러리 연동** | ActivityResultLauncher와 ContentResolver로 카메라 촬영·갤러리 선택을 통합 처리, 권한 분기 및 이미지 보정 흐름 구현 |
| **JWT 토큰 자동 갱신** | OkHttp Authenticator + Interceptor 조합으로 액세스 토큰 만료 시 리프레시 토큰으로 자동 재발급, 사용자 경험 단절 없이 처리 |
| **AI 코디 추천 연동** | 옷 상세 페이지에서 서버 AI가 추천한 코디를 실시간으로 받아 UI에 반영, 남의 옷 가져오기·북마크 기능과 연계 |
| **MVVM + Repository 패턴** | ViewModel, LiveData, Repository를 분리해 관심사를 명확히 나누고, Kotlin Coroutines로 API 호출·이미지 처리 비동기 작업 구조화 |

#### 사용 기술

| 영역 | 기술 |
|:---|:---|
| **Language** | `Kotlin` |
| **Architecture** | `MVVM`, `Repository Pattern` |
| **Jetpack** | `ViewModel`, `LiveData`, `Navigation Component`, `Room`, `ViewBinding` |
| **Network** | `Retrofit2`, `OkHttp`, `Gson` |
| **Async** | `Kotlin Coroutines` |
| **Image** | `Glide`, `PhotoView`, `ExifInterface` |
| **AI/ML** | `ML Kit`, `MediaPipe`, `TensorFlow Lite` |
| **UI** | `Material Design 3`, `Lottie`, `MPAndroidChart`, `FlexBox` |

**[GitHub Repository](https://github.com/JinYunSe/Closetory)**

</details>

<br>

<details>
<summary><b>3. SsafyPlayTime — SSAFY 특화 프로젝트 | 친구들과 웃으며 즐기는 물리 기반 멀티플레이 파티 게임</b></summary>
<br>

> **2026.02.16 ~ 2026.03.30** · 6명 · Unity Client

#### 담당 역할

Unity 클라이언트 개발. Active Ragdoll 기반 물리 캐릭터 시스템, Photon Fusion 네트워크 동기화, 고스트 아이템 투척 시스템, 게임 종료·랭킹 시스템, 관전 카메라, 네트워크 성능 최적화 담당

#### 프로젝트를 통해 배운 점

| 배운 점 | 구체적 내용 |
|:---|:---|
| **Photon Fusion 실시간 네트워크 동기화** | Host 모드에서 캐릭터 물리 상태(관절 회전, 위치)를 NetworkArray로 동기화하며 실시간 멀티플레이 구조 이해 |
| **래그돌 물리 & 상태 머신 설계** | PuppetMaster 기반 Active Ragdoll에 PhysicalPhase 상태 전이를 적용, 자연스러운 캐릭터 물리 반응 구현 |
| **호스트 마이그레이션** | 방장 이탈 시 세션·캐릭터 선택·준비 상태를 새 호스트에 무손실 이관하는 시스템 구현 |
| **게임 종료·랭킹 시스템** | GameEndPanel 씬 전환·랭킹 동기화·탈주 처리 등 게임 종료 흐름 전반 구현, 호스트 이탈 edge case 대응 |
| **고스트 아이템 투척·관전 카메라** | GhostCube 투척 타겟 정확도·쿨타임·중복 방지 구현, 사망 후 타원 공전 관전 카메라 제작 |
| **네트워크 성능 최적화** | Camera.main 프레임 캐시, PlayerAOIUpdater 10Hz 제한, 거리 기반 Physics LOD, FindObjects 반복 호출 제거로 프레임 드랍 해소 |

#### 사용 기술

| 영역 | 기술 |
|:---|:---|
| **Engine** | `Unity 2022.3 LTS`, `C#`, `URP` |
| **Network** | `Photon Fusion 2`, `Photon Realtime` |
| **Physics** | `PuppetMaster`, `Active Ragdoll`, `ConfigurableJoint` |
| **Animation** | `Cinemachine`, `DOTween`, `Procedural IK` |
| **Input** | `Unity Input System` |
| **Data** | `CSV 기반 게임 데이터 테이블` |

**[GitHub Repository](https://github.com/JinYunSe/SsafyPlayTime)**

</details>

<br>

<details>
<summary><b>4. BunMin — 🏆 SSAFY 자율 프로젝트 기업 연계 우수상 (11팀 중 1등) · 🥉 전국 프로젝트 전시회 3등 (117팀 중 3등) | 대학교 강의 실시간 번역 서비스</b></summary>
<br>

> **2026.04.06 ~ 2026.06.03** · 6명 · Electron · Backend · AI

#### 담당 역할

웹 기반 서비스를 Electron 데스크탑 앱으로 전환하고, WebAudio API를 활용한 강사 원본 음성과 영어 TTS의 실시간 동기화 시스템 개발 담당. ASR/TTS 스트리밍 파이프라인 최적화, VAD 교체, AI 모델 통합 및 정량 평가 시스템 구축. WebRTC 재연결·로컬 TURN 서버 등 네트워크 안정성 전반을 책임

#### 프로젝트를 통해 배운 점

| 배운 점 | 구체적 내용 |
|:---|:---|
| **Electron 데스크탑 앱 마이그레이션** | 웹 앱을 Electron으로 전환하며 CORS isolation, 마이크 가드, NSIS 설치파일 빌드 자동화 등 데스크탑 앱 특유의 환경 설정과 배포 구조를 직접 설계 |
| **WebAudio API 오디오 동기화** | DelayNode 기반으로 강사 원본 음성과 영어 TTS 두 트랙을 독립적으로 싱크, 적응형 딜레이 조정으로 수강생 측 wall-clock 오차 최소화 |
| **ASR/TTS 스트리밍 최적화** | Silero VAD를 에너지 기반 RMS VAD로 교체하고 force-split 구간을 3s→1.5s로 단축해 번역 응답 지연을 실질적으로 개선 |
| **AI 모델 통합 및 평가** | piper-tts-web TTS 모델과 VLM(Qwen3-VL) 자동 양자화 통합, 모델 성능을 정량 측정하는 평가 시스템 직접 구축 |
| **WebRTC 네트워크 안정화** | 강사-수강생 간 연결 끊김 자동 재연결 처리 및 로컬 TURN 서버 구축으로 다양한 NAT 환경에서도 안정적인 실시간 통신 보장 |

#### 사용 기술

| 영역 | 기술 |
|:---|:---|
| **Language** | `JavaScript`, `TypeScript` |
| **Framework** | `Electron`, `React` |
| **Audio** | `WebAudio API`, `AudioWorklet`, `DelayNode` |
| **ASR** | `faster-whisper` (Whisper large-v3-turbo, CTranslate2 int8 양자화) |
| **NMT** | `NLLB-200 distilled 600M` (한국어→영어 신경망 번역) |
| **TTS** | `piper-tts-web` |
| **OCR** | `Surya OCR` (슬라이드 텍스트 추출) |
| **VLM** | `Qwen3-VL` (슬라이드 이미지 이해·번역) |
| **VAD** | 에너지 기반 RMS VAD |
| **Sync** | `실시간 오디오·슬라이드 3중 동기화` |
| **Tools** | `Git`, `GitLab`, `Jira`, `Notion` |

**[GitHub Repository](https://github.com/JinYunSe/BunMin)**

</details>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=150&section=footer)
