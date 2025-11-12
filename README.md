# 👋 Welcome to my GitHub

I ship end‑to‑end systems: federated/distributed ML, multimodal modeling, rule‑based reasoning, full‑stack apps, mobile features, desktop tools, and clean data layers. Below is what I’ve built and delivered across my projects.

![GitHub stats](https://github-readme-stats-milos-projects-463f2574.vercel.app/api?username=milosmat&show_icons=true&count_private=true)


---

## 🔥 Featured / Trending Projects

### 🏀 NBA Champion 2026 Prediction (Federated & Distributed ML)

What I built:

- A custom asyncio actor system with three orchestration modes: provider, P2P, and gossip.
- Federated training with FedAvg and FedProx (μ regularization on clients).
- Convergence controls (epsilon + patience), continuous async streaming, and round barriers.
- CRDT replication (PN‑Counter, LWW‑Map) to track rounds/state in a decentralized way.
- gRPC transport alongside TCP; generated protobuf stubs.
- Playoff bracket simulation (QF → SF → F) and champion extraction.
- End‑to‑end persistence of metrics and models to SQLite; reproducible benchmarking.

➡️ [NBA_champion_2026_prediction](https://github.com/milosmat/NBA_champion_2026_prediction)

---

### 🏘️ Real Estate Price Assessment (Multimodal Regression)

What I built:

- Hybrid modeling: XGBoost on tabular features + ResNet18/50 for image regression.
- Fusion strategies: simple averaging, voting ensemble, and stacking meta‑learner.
- Target scaling with proper inverse transforms; residual diagnostics and calibration exports.
- Batch image feature extraction, checkpoint resume, and fusion reports in JSON/CSV.

➡️ [real_estate_price_assessment](https://github.com/milosmat/real_estate_price_assessment)

---

### 🧪 SBZ Drools Demo (Rule / Knowledge Systems)

What I built:

- Java 8 project with Drools 7.73 (KIE API, compiler, MVEL) packaged via Maven Shade.
- Runnable knowledge base demo with a clean entrypoint (KIE sessions, rules on classpath).
- PostgreSQL schema and Gson serialization for data interchange.

➡️ [sbz](https://github.com/milosmat/sbz)

---

### 🍫 Chocolate Factory (Full‑Stack Operations)

What I built:

- Backend: Node.js (Express) with JWT auth, validation (express‑validator), CSV import, image upload (Multer), and Firestore/Mongo‑friendly domain modeling.
- Domain: products, inventory batches (production/expiry), orders (status transitions), and totals.
- Geospatial UI: OpenLayers map for warehouses/stores with markers and overlays.
- Frontend: Vue app with dashboards, grids, modals, and a typed API client.

➡️ [chocolate-factory](https://github.com/milosmat/chocolate-factory)

---

### 🎮 e2-ma-tim40-2025 (Mobile Application – Java)

What I built:

- Authentication and profile lifecycle with Firestore persistence (coins, stats, mission state).
- Task system with category management and deterministic color synthesis (collision‑safe).
- Leveling curve, equipment stat bounds, and deterministic boss combat (templates + tie‑breakers).
- Special mission chains: multi‑step prerequisites, non‑repeatable rewards, coin economy updates.

➡️ [e2-ma-tim40-2025](https://github.com/milosmat/e2-ma-tim40-2025)

---

### 🖥️ Studentska Služba (WPF)

What I built:

- WPF shell (XAML) with localized resource dictionaries and style templates.
- Centralized MessageBox manager (consistent titles/buttons/icons) and localization helper.
- Converter library (visibility, equality, formatting) to keep bindings clean.
- CLI companion for headless tasks and smoke checks.

➡️ [oisisi](https://github.com/milosmat/oisisi)

---

### 🗄️ Baze2 Projekt (JDBC / Relational)

What I built:

- Plain JDBC DAOs with prepared statements and explicit column mapping.
- Transaction‑scoped service layer for multi‑table operations (commit/rollback safety).
- DDL/DML scripts for schema + seed data, pagination patterns, and index‑aware queries.

➡️ [baze2_projekat](https://github.com/milosmat/baze2_projekat)

---

### 🧭 PSW Explorer Platform (Backend – ASP.NET Core)

What I built:

- Modular C# backend with domain slices (Tours, Checkpoints, Encounters, Stakeholders, Blog, Payments, Games).
- Startup composition: JWT auth, CORS, Swagger, module registration, and data seeding (tourist profiles).
- TourCheckpoint service + DTOs, repository wiring, and integration tests for controllers.
- Progression flows (XP/level gating), encounter endpoints, and startup seed orchestration.

➡️ [psw-be-ra-2024-group-8-mirror](https://github.com/milosmat/psw-be-ra-2024-group-8-mirror)

---

### 🌐 PSW Explorer Platform (Frontend – Angular)

What I built:

- Angular/TypeScript SPA with tours playback, routing, secrets discovery UX, and checkpoint progression.
- Encounter modals, authoring interfaces, challenge/review flows, and level‑gated actions.
- State synchronization with TourCheckpoint improvements from the backend integration.

➡️ [psw-fe-ra-2024-group-8-mirror](https://github.com/milosmat/psw-fe-ra-2024-group-8-mirror)

---

For more projects check this link https://github.com/milosmat?tab=repositories !
Thanks for stopping by!
