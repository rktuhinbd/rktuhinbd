<!-- ============================================================
     MD. REJAUL KARIM — GitHub Profile README
     ============================================================ -->

<h2 align="center">Md. Rejaul Karim</h2>
<h4 align="center">
  Mobile Systems Architect · Native Android · Hardware Integration · Edge ML
</h4>

<p align="center">
  <a href="https://linkedin.com/in/rktuhinbd"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:rejaul.karim.pro@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://rktuhinbd.github.io/resume/"><img src="https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=githubpages&logoColor=white"/></a>
  <a href="https://medium.com/@rktuhinbd"><img src="https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white"/></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=rktuhinbd&style=flat-square"/>
</p>

---

> **Building Android systems that operate at the hardware boundary — from ESC/POS peripheral orchestration and real-time KDS pipelines to on-device ML inference and 100K+ MAU production platforms — with zero tolerance for architectural drift.**

---

## ⚙️ Core Specializations

| Domain | Capabilities |
|---|---|
| **Architectural Paradigms** | Clean Architecture · MVVM · SOLID · Repository Pattern · Modularization · Offline-First Design |
| **Reactive UI & Modern Stack** | Jetpack Compose · StateFlow · SharedFlow · Material 3 · Compose Design Systems · XML→Compose Migration |
| **Hardware & Edge Integration** | ESC/POS Command Protocol · Bluetooth / USB / Network Thermal Printers · Sunmi Devices · Barcode Scanning · KDS Real-Time Routing |
| **On-Device ML & AI** | ML Kit (Face Detection · OCR · NID Verification) · TFLite Inference · Reusable `.aar` ML SDKs · LLM Integration (OpenAI · Gemini · Claude) |
| **Concurrency & Data** | Coroutines · Flow · Room · DataStore · Paging 3 · WorkManager · Offline Sync |
| **Delivery & Reliability** | GitHub Actions · Firebase Crashlytics · Firebase App Distribution · Fastlane · ProGuard/R8 · Play Console |

---

## 📊 Production Impact

> `98.87%` crash-free rate *(up from 91%)* · `+25%` KYC account creation across 3 banking apps · `+23%` student retention · `100K+` MAU EdTech platform · `360K+` users on booking system at `19%` conversion · `60%` reduction in design debt via Compose design system

---

## 🏗️ Featured Systems

### 1 · Universal Peripheral Communication Library — VALT ePOS/KDS

| | |
|---|---|
| **Challenge** | Single Android codebase must drive receipt printers and kitchen ticket printers across three distinct transports (Bluetooth, USB, Network) on commercial Sunmi hardware, with zero print loss in high-throughput restaurant environments |
| **Architecture** | Transport-agnostic abstraction layer over ESC/POS command generation · Strategy pattern per transport type · Coroutine-based job queue with retry and fallback routing · Offline-first Room buffer for order sync resilience |
| **Impact** | Deterministic print delivery across all transport types in production restaurant deployments; KDS ticket latency kept sub-second for kitchen operational throughput |

---

### 2 · ML Kit KYC SDK — Millennium Information Solution (3 Banking Apps)

| | |
|---|---|
| **Challenge** | Three separate banking apps (Social Islami Bank, Union Bank, Al-Arafah Islami Bank) each require biometric facial verification and NID document scanning — without tripling the ML integration surface area |
| **Architecture** | Encapsulated ML Kit face detection + OCR + document verification pipeline into a distributable `.aar` SDK · Gradle product flavors for per-bank variant configuration from a single source tree · Deterministic KYC state machine with audit-friendly event logging |
| **Impact** | `+25%` average account creation uplift across all three apps; eliminated redundant ML integration work across banking clients; reusable SDK pattern adopted as internal standard |

---

### 3 · Jetpack Compose Ecosystem Migration — 10 Minute School (100K+ MAU)

| | |
|---|---|
| **Challenge** | Monolithic Java/XML codebase serving 100K+ active users with 91% crash-free rate; XML layout debt blocking feature velocity; Java interop overhead degrading null-safety guarantees |
| **Architecture** | Phased Java→Kotlin migration preserving test coverage at each increment · Screen-by-screen XML→Compose migration gated on component parity · Compose design system with 30+ production components as single source of truth · Crashlytics + LeakCanary integration at every release gate |
| **Impact** | Crash-free rate: `91% → 98.87%` · `20%` new feature throughput increase · `60%` design debt reduction · Established UI guidelines adopted org-wide |

---

## 🧰 Technical Inventory

**Core Android**
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Architecture & DI**
![Hilt](https://img.shields.io/badge/Hilt-2196F3?style=flat-square&logo=google&logoColor=white)
![Room](https://img.shields.io/badge/Room-4479A1?style=flat-square&logo=sqlite&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Networking**
![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=flat-square&logo=square&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white)
![OkHttp](https://img.shields.io/badge/OkHttp-3DDC84?style=flat-square&logo=square&logoColor=white)

**ML / AI**
![TFLite](https://img.shields.io/badge/TFLite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ML Kit](https://img.shields.io/badge/ML_Kit-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Cross-Platform**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**CI/CD & Monitoring**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black)

---

## 🔁 Engineering Workflow

Every system — from architecture design to production release — follows the same discipline:

```
UNDERSTAND  →  Decompose requirements. Identify hardware constraints, data contracts,
                failure modes, and state boundaries before writing a line of code.

PLAN        →  Define the module graph, state machine, and interface contracts.
                Confirm tradeoffs (offline-first vs sync complexity, .aar coupling vs
                flexibility) in writing before implementation begins.

EXECUTE     →  Incremental, reviewable delivery. Gate each increment on test parity.
                Instrument before shipping: Crashlytics, analytics, memory profiling.
```

---

## 📌 Connect

| | |
|---|---|
| **LinkedIn** | [linkedin.com/in/rktuhinbd](https://linkedin.com/in/rktuhinbd) |
| **Portfolio** | [rktuhinbd.github.io/resume](https://rktuhinbd.github.io/resume/) |
| **Email** | rejaul.karim.pro@gmail.com |
| **Medium** | [@rktuhinbd](https://medium.com/@rktuhinbd) |

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rktuhinbd&theme=dark&hide_border=true" alt="streak"/>
</p>
