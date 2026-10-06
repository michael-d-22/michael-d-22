### 💻 Stack

<p align="left">
  <!-- Backend & Core -->
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logoColor=white" alt="REST API" />
  <br>
  <!-- Frontend, Desktop & Testing -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest" />
  <br>
  <!-- Tools & Workflow -->
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Claude_Code-D97706?style=for-the-badge&logoColor=white" alt="Claude Code" />
</p>

---

### 🚀 Progetti Principali

#### 🏓 [Gestione Tornei & Classifica Elo Tennistavolo](https://github.com/michael-d-22/tennistavolo-amatori)
*App desktop per Windows in uso operativo reale per la gestione delle classifiche interne di un circolo sportivo.*
- **Architettura a dominio isolato:** Core puro in TypeScript disaccoppiato da UI e runtime di sistema, ricalcolo deterministico cronologico del rating Elo e modello di sincronizzazione dati offline-first.
- **Affidabilità & Testing:** Suite completa di 57 unit test con Vitest e test end-to-end automatizzati su flussi utente e persistenza.
- **Workflow Agentic:** Sviluppata con supporto di Claude Code supervisionando architettura, vincoli formali, code review e test suite.
- **Stack:** `Electron` · `React` · `TypeScript` · `Vitest` · `Claude Code`

#### ⚙️ [Gestionale Prenotazione Sessioni di Allenamento](https://github.com/michael-d-22/gestionale-tennistavolo)
*Applicazione web concepita per digitalizzare la registrazione degli atleti e la gestione delle fasce orarie in palestra.*
- **Architettura Enterprise:** Struttura a livelli (Controller, Service, Repository) con DTO e validazione rigorosa dei vincoli di business (gestione sovrapposizioni, capienza massima sessioni, duplicati).
- **Persistenza & API:** Modellazione relazionale su MySQL, Spring Data JPA / Hibernate ed esposizione di endpoint RESTful.
- **Stack:** `Java` · `Spring Boot` · `Spring Data JPA` · `MySQL` · `REST API` · `Claude Code`

