<h1 align="center">mysk423</h1>
<p align="center"><b>Backend / Server Developer</b><br />요청을 받는 쪽을 먼저 생각합니다</p>

---

## 🧩 무엇을 만드는가

서버를 가운데 두고, 필요한 쪽을 붙입니다.

```mermaid
flowchart LR
    ESP["🔌 ESP32 · Raspberry Pi"] -- MQTT --> API
    GAME["🎮 Unity · Unreal"] -- REST / WebSocket --> API
    WEB["🌐 Vue · Flutter"] -- REST --> API
    API["⚙️ API Server<br/>Go · Spring · FastAPI"] --> DB[("🗄️ MySQL · Redis")]
    API --> LOG["📊 수집 · 모니터링"]

    classDef edge  fill:#161b22,stroke:#30363d,stroke-width:1px,color:#8b949e
    classDef core  fill:#1f6feb,stroke:#58a6ff,stroke-width:2px,color:#ffffff
    classDef store fill:#238636,stroke:#3fb950,stroke-width:2px,color:#ffffff
    class ESP,GAME,WEB,LOG edge
    class API core
    class DB store
```

---

## 🛠️ 기술 스택

```mermaid
flowchart TD
    ROOT(("mysk423"))

    ROOT --> BE["⚙️ Backend"]
    ROOT --> IOT["🔌 IoT"]
    ROOT --> CLI["🖥️ Client"]

    BE --> BE1["Python · Go"]
    BE --> BE2["Spring · Java"]
    BE --> BE3["MySQL · MariaDB · Redis"]
    BE --> BE4["Docker · Linux"]

    IOT --> IOT1["Raspberry Pi"]
    IOT --> IOT2["ESP32 · Arduino"]

    CLI --> CLI1["Unity · Unreal"]
    CLI --> CLI2["C# · C++"]
    CLI --> CLI3["Vue · TypeScript"]
    CLI --> CLI4["Flutter · Dart"]

    classDef root fill:#8957e5,stroke:#bc8cff,stroke-width:2px,color:#ffffff
    classDef hub  fill:#1f6feb,stroke:#58a6ff,stroke-width:2px,color:#ffffff
    classDef leaf fill:#161b22,stroke:#30363d,stroke-width:1px,color:#c9d1d9
    class ROOT root
    class BE,IOT,CLI hub
    class BE1,BE2,BE3,BE4,IOT1,IOT2,CLI1,CLI2,CLI3,CLI4 leaf
```

---

## 🙋‍♂️ About

| | |
|:--|:--|
| **Role** | Backend / Server Developer |
| **Focus** | API 설계 · 데이터 모델링 · 배포 운영 |
| **Also** | 게임 클라이언트 · 모바일 · 웹 · IoT 하드웨어 |
| **Now** | `실시간 통신` `분산 처리` `AI 도구 활용` |
| **Mail** | mysk423@naver.com |

---

## 📦 프로젝트

| | 프로젝트 | 설명 | 스택 |
|:--:|:--|:--|:--|
| 🔌 | **project-a** | 한 줄 설명을 여기에 | `Go` `MySQL` `ESP32` |
| 🎮 | **project-b** | 한 줄 설명을 여기에 | `Unity` `C#` |
| 🌐 | **project-c** | 한 줄 설명을 여기에 | `Vue` `Spring` |

---

<div align="center">

<a href="mailto:mysk423@naver.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=maildotru&logoColor=white" /></a>
<a href="https://github.com/mysk423"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
<img src="https://komarev.com/ghpvc/?username=mysk423&style=flat-square&color=58a6ff&label=visitors" />

</div>
