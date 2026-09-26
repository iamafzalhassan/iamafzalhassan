# Afzal Hassan

**Mobile Software Engineer**\
Android · Flutter · Kotlin Multiplatform\
Colombo, Sri Lanka\
Open to **remote** roles

[![Email](https://img.shields.io/badge/Email-imakevirtual%40gmail.com-0F172A?style=flat-square&logo=gmail&logoColor=white)](mailto:imakevirtual@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-iamafzalhassan-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/iamafzalhassan)

I build mobile apps that stay correct, fast and easy to change long after launch.

For 5+ years at **Arimac** I've built production apps for enterprise clients in **telecom, fintech, aviation and government**, including **SriLankan Airlines, Ooredoo, Batelco and PayLater**. My work sits where product meets platform: modular architecture, performance, offline-first data, and the CI/CD and automated testing that let teams deliver with confidence. I also lead design reviews and mentor junior and mid-level engineers.

---

### Featured work

| Project | What it is | Engineering highlights |
|---|---|---|
| **[glance](https://github.com/iamafzalhassan/glance)**<br/><sub>Flutter · Riverpod · Kotlin · ESP32-S3</sub> | Custom digital dashboard for a Yamaha scooter: the bike's own speed, fuel and lamp signals next to Google Maps navigation on an Android tablet | Hand-written **binary protocol with CRC16**, sequence and spike rejection, and byte-exact test vectors ready for the ESP32 firmware · every reading carries its own freshness timer, so a stale value is never shown as live · rider-safety locks above 5 km/h · **Android device-owner kiosk** with light-sensor brightness and a heat guard · Places and Routes API navigation with automatic rerouting · a browser Studio that injects every signal fault without hardware · pub workspace with pure-Dart protocol and telemetry packages, unit and golden tests |
| **[salli](https://github.com/iamafzalhassan/salli)**<br/><sub>Flutter · BLoC · Platform channels</sub> | Payments and wallet app for Sri Lanka in the style of Google Pay, on simulated payment rails | Every request **signed with a hardware-bound ECDSA P-256 key** from the Android Keystore or iOS Secure Enclave, through custom platform channels · biometric approvals signed by a second key that re-enrolment invalidates · PIN stretched with PBKDF2 on the device and never sent · idempotent payments on a **double-entry ledger** with tier limits and risk-based step-up · EMVCo LANKAQR encoder and parser · SPKI certificate pinning and runtime threat detection · English, Sinhala and Tamil · 400+ tests, including every API area against a signature-verifying mock server |
| **[Evenly](https://github.com/iamafzalhassan/Evenly)**<br/><sub>Kotlin Multiplatform · Compose Multiplatform · Supabase</sub> | Shared expense tracker for Android and iOS from a single codebase | Offline-first sync engine with **sequence-based pulls** (immune to clock skew), per-row last-writer-wins and tombstone deletes · Postgres **row-level security** · exact integer currency conversion and largest-remainder splits · settles any group in **at most n − 1 payments** · native biometric lock on both platforms · unit tests for splits, settle-up and currency conversion, run in CI on the JVM and iOS simulator |
| **[biller](https://github.com/iamafzalhassan/biller)**<br/><sub>Flutter · Riverpod · SQLite</sub> | Offline point-of-sale billing app running at a live wholesale counter | Pixel-aligned multi-page A5 PDF receipts · custom **ESC/POS** Bluetooth thermal printing · offline device activation with **Ed25519** signatures · salted, iterated SHA-256 PIN with constant-time compare · crash-safe draft recovery · unit tests for PIN hashing and invoice totals |
| **[Debitter](https://github.com/iamafzalhassan/Debitter)**<br/><sub>Kotlin · Jetpack Compose · MVVM</sub> | Native Android app replacing a manual Word workflow for a customs clearing business | **Custom PDF layout engine** on `Canvas` with no third-party library · decimal-aligned tabular figures and automatic scale-to-fit onto a single A4 page · `BigDecimal` money with one formatter shared by UI and PDF · non-destructive SQLite migrations · JUnit tests for money formatting and note totals |
| **[rawg](https://github.com/iamafzalhassan/rawg)**<br/><sub>Flutter · BLoC · Supabase</sub> | Game discovery app built on the RAWG API | Clean Architecture with use cases and typed results · **Hive cache of game details with 24-hour TTL** as a network fallback · debounced search with paginated loading that drops stale responses · Supabase authentication with route protection · OneSignal push · English and Sinhala localization · unit tests for the offline cache |

<sub>More: **[muwaqqit](https://github.com/iamafzalhassan/muwaqqit)** (offline prayer-times board for masjid displays: astronomical calculation, live Azan and Iqamah countdowns, layouts from tablet to TV) · **[mmf](https://github.com/iamafzalhassan/mmf)** (Flutter web household registration form: Clean Architecture, BLoC, conditional validated fields, unit-tested submission rules)</sub>

---

### Experience

**Software Engineer, Mobile** · Arimac · *2023 – Present*
<sub>SriLankan Airlines · Ooredoo Algeria · Batelco · PayLater</sub>
- Architected modular apps with Clean Architecture and MVVM so feature teams could build and ship independently on large enterprise codebases
- Found and fixed performance bottlenecks through memory profiling, response caching and a concurrency-safe networking layer
- Automated build and test pipelines on Bitrise, Codemagic and GitHub Actions, with Shorebird OTA updates, for faster and lower-risk delivery
- Led design reviews, set team code standards, and mentored junior and mid-level engineers
- Worked with distributed product, design, QA and backend teams to scope features and deliver them on client roadmaps

**Associate Software Engineer, Mobile** · Arimac · *2021 – 2023*
<sub>Ooredoo Maldives · Road Development Authority · Dilmah Tea · Mabroc · Softlogic One</sub>
- Delivered multiple production apps for telecom, government, retail and tea-industry clients
- Integrated REST APIs with structured error handling and retry logic so core flows stay reliable on unstable mobile networks
- Wrote automated tests for critical user flows and set up CI/CD pipelines that shortened delivery turnaround

---

### Technical skills

| Area | Stack |
|---|---|
| **Languages** | Dart · Java · Kotlin |
| **Frameworks** | Flutter · Jetpack Compose · Kotlin Multiplatform |
| **Architecture** | Clean Architecture · Modularization · MVI · MVVM · Unidirectional data flow |
| **State & Async** | BLoC · Coroutines & Flow · Provider · Riverpod · StateFlow |
| **Data** | Dio · Hive · Ktor · Offline-first sync · Room · SQLite |
| **Security** | Android Keystore · Biometrics · Certificate pinning · Encrypted storage · Request signing |
| **Backend & Cloud** | AWS · Firebase · GCP · Supabase |
| **Testing & CI/CD** | Automated testing · Bitrise · Codemagic · GitHub Actions · Shorebird OTA |
| **Tools** | Android Studio · Claude Code · Cursor · Figma · Git · Jira |

---

### Education

**BSc (Hons) Software Engineering** · Birmingham City University · *2016 – 2020*

---

**Currently open to remote Mobile Engineer roles.** The fastest way to reach me is [email](mailto:imakevirtual@gmail.com).
