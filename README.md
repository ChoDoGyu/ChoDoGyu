# 조도규 | Unity 게임 클라이언트 개발자

Unity와 C#으로 게임 클라이언트를 개발합니다. Android 2D 생존 게임 **LastArena**를 기획하고 1인 개발해 Google Play에 출시했습니다. **UnityRPG**에서는 3D 전투부터 보스·퀘스트·장비·저장까지 하나의 플레이 흐름으로 구현했습니다.

## 주요 프로젝트

| 프로젝트 | 구현 내용 | 바로 보기 |
| --- | --- | --- |
| **LastArena** · Android 2D 생존 게임 | 드래그 이동, 자동 조준, 발사체 풀링, 결과 점수 집계 | [Google Play](https://play.google.com/store/apps/details?id=com.CHOCompany.LastArena) · [게임플레이](https://youtu.be/OM-EqR9C4nw) · [기술 문서](https://zinc-lipstick-51c.notion.site/LastArena-310d3addd2cb80fa87d5dc37f3455617) · [코드 샘플](https://github.com/ChoDoGyu/LastArena-Portfolio) |
| **UnityRPG** · 3D 액션 RPG 버티컬 슬라이스 | 플레이어 전투, 적 AI와 보스 패턴, 퀘스트, 장비, JSON 저장·이어하기 | [소스 코드](https://github.com/ChoDoGyu/UnityRPG) · [게임플레이](https://youtu.be/m8P98AnVkJM) |
| **Sudology** · 2D 스도쿠 | 유일 해답을 확인하는 퍼즐 생성, 입력 Undo/Redo, 진행 상태 저장 | [WebGL 데모](https://sudology-demo.netlify.app/) · [소스 코드](https://github.com/ChoDoGyu/Sudology) |

## Unity 패키지와 Editor Tool

**CDG Unity Modular Framework**는 Unity 프로젝트에서 재사용할 수 있는 UPM 패키지 10개입니다. Core, EditorTools, Pooling, Data, Save, UI, Audio, Scene, Map Generation, Quest를 개발했습니다. [패키지 목록과 기술 문서](https://zinc-lipstick-51c.notion.site/CDG-Unity-Modular-Framework-365d3addd2cb80cf9d1cc29c6433ee7a)

- **EditorTools** — 씬과 프리팹에서 Missing Script와 깨진 직렬화 참조를 검사합니다. 검사 결과에서 문제 위치로 이동할 수 있으며, 검사 규칙과 씬 보호를 확인하는 EditMode 테스트를 작성했습니다. [EditorTools 코드](https://github.com/ChoDoGyu/ChoDogyuEditorTools)
- **Data** — CSV·JSON 가져오기에서 데이터 검증, 미리보기, 변경 비교, 적용을 분리했습니다. 미리보기 이후 데이터가 바뀌면 적용을 중단하는 경로를 자동화 테스트로 다룹니다. [Data 코드](https://github.com/ChoDoGyu/ChoDogyuData)

[GitHub](https://github.com/ChoDoGyu) · [Notion 포트폴리오](https://zinc-lipstick-51c.notion.site/Unity-Game-Developer-1fcd3addd2cb80e68ca0f3df2522b1b9)
