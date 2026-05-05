# Thierry Teisseire — Full Stack Developer CV

**GitHub:** [@thierryteisseire](https://github.com/thierryteisseire) | **Location:** France  
**Email:** t.teisseire@gmail.com

---

## 👨‍💼 Professional Summary

Full-stack developer with expertise in TypeScript, CLI development, backend APIs, frontend integration, and automation. Proven track record of building production-grade applications spanning enterprise-level lead management systems, AI agent frameworks, and integration platforms. Strong focus on developer experience, security, and operational excellence.

---

## 🛠 Technical Skills

### Languages & Frameworks
- **Frontend:** TypeScript, React, HTML/CSS, Chrome Extensions (Manifest V3)
- **Backend:** Node.js, TypeScript, REST APIs, OAuth/Cognito
- **CLI Tools:** Commander.js, Inquirer, Table formatting, Interactive TUIs
- **Automation:** Python, Bash scripting
- **Databases:** DynamoDB, SQL

### Key Technologies
- **Authentication:** AWS Cognito, OAuth 2.0, JWT, Google OAuth
- **Integrations:** Salesforce, HubSpot, Unipile, Google Reviews
- **Cloud:** AWS (Lambda, DynamoDB, S3, Cognito)
- **DevOps:** npm distribution, binary packaging (pkg/esbuild), GitHub Actions
- **Architecture:** API-first design, event-driven systems, microservices

### Tools & Practices
- Git & GitHub version control
- npm ecosystem and package publishing
- CI/CD pipeline management
- Security hardening (authentication, authorization, data validation)
- Cross-platform development (macOS, Windows, Linux)

---

## 💼 Major Projects (Last 24 Months)

### LeadGenius CLI v2.0+ — Enterprise Lead Management Platform
**Repository:** `leadgenius-cli` | **Status:** Active Production  
**Commits:** 100+ in last 24 months | **npm Package:** [leadgenius-cli](https://www.npmjs.com/package/leadgenius-cli)

**Achievements:**
- **Complete CLI rewrite:** Rebuilt entire system from Python to TypeScript for better performance and maintainability
- **100+ commands:** Implemented 20 command groups covering full API surface (leads, tasks, FSD, companies, users, org, cognito, epsimo, tables, generate, campaigns, clients, shares, webhooks, maintenance, pipeline, account-analysis, admin)
- **Interactive TUI mode:** Built menu-driven interface with dropdown pickers, real-time navigation, and auto-authentication
- **Smart lead search:** Case-insensitive matching with auto-detection of email/name/URL patterns
- **CSV import pipeline:** Implemented auto-header mapping with dialect detection and batch processing
- **Session persistence:** Credential caching to `~/.leadgenius-cli/session.json` with automatic reload
- **EpsimoAI integration:** Direct Cognito→EpsimoAI token exchange flow with session caching
- **Chrome Extension:** Manifest V3 extension with Google OAuth, email sign-in, and API testing UI
- **Cross-platform binaries:** Generated standalone executables for macOS (Intel/ARM), Windows, and Linux
- **npm distribution:** Published to npmjs.com, 2.0.15 version with 100K+ weekly potential reach
- **Advanced formatting:** Table rendering with nested arrays, progress bars, colored statuses, truncated columns
- **Security hardening:** Server-side Cognito admin checks, cross-tenant user enumeration prevention, strict authorization

**Key Features Shipped:**
- Interactive client picker dropdowns
- Case-insensitive smart search with multiple name variants
- Persistent session management
- Nested table rendering (sub-tables for complex objects)
- Batch deduplication and merge workflows
- Soft-delete, restore, and purge operations
- CSV and JSON import with strictMode and deduplication
- Admin backup/restore with Point-In-Time Recovery (PITR)
- Lead ownership validation and orphan detection
- Account-based analysis and territory intelligence

**Tech Stack:** TypeScript, Node.js, Commander.js, Inquirer, cli-table3, esbuild, pkg, AWS Cognito, REST APIs

---

### LeadGenius HubSpot Integration
**Repository:** `leadgenius-hubspot` | **Status:** Active  
**Commits:** 5+ integration commits

**Achievements:**
- Built comprehensive HubSpot sync connector for bi-directional lead synchronization
- Created detailed SKILL.md documentation for AI agent registry integration
- Implemented API mapping pipeline with field transformation
- Added package.json metadata for skills.sh discovery
- Documented integration workflows for enterprise deployments

**Tech Stack:** TypeScript, Node.js, HubSpot API, LeadGenius API

---

### Epsimo AI Agent Framework
**Repository:** `epsimo-backend`, `epsimo-frontend`, `epsimo-cli` | **Status:** Active  
**Commits:** 15+ across multiple repos

**Achievements:**
- **Backend services:** Built scalable Node.js backend with REST API endpoints
- **Frontend UI:** Developed interactive React-based dashboard
- **CLI tools:** Created command-line interface for agent management
- **Agent architecture:** Designed skill-based agent framework for extensible AI workflows
- **Documentation:** Comprehensive SKILL.md files for registry integration

**Tech Stack:** TypeScript, Node.js, React, REST APIs, AWS services

---

### NemoClaw — Advanced Lead Data System
**Repository:** `NemoClaw` | **Status:** Maintained

**Achievements:**
- Built robust lead data pipeline with enrichment capabilities
- Implemented caching and optimization strategies
- Created detailed technical documentation

---

### Unipile Automation — Multi-Channel Communication
**Repository:** `unipile-automation` | **Status:** Active  
**Commits:** Integration and automation commits

**Achievements:**
- Automated workflows for multi-channel communication platforms
- Created integration scripts for seamless data flow
- Implemented error handling and retry logic

---

### Salesforce LeadGenius Integration
**Repository:** `salesforce-leadgenius` | **Status:** Active

**Achievements:**
- Built Salesforce connector for lead synchronization
- Implemented OAuth flow for secure authentication
- Created custom objects and field mappings
- Documented integration workflows

---

### Skills & Portfolio Projects
**Repository:** `skills` | **Status:** Active

**Achievements:**
- Comprehensive skills documentation
- Portfolio showcasing various integration patterns
- Reference implementations for common use cases

---

## 🎯 Key Contributions & Achievements (24 Months)

### Security & Compliance
- ✅ Implemented Cognito admin-only verification checks to prevent unauthorized access
- ✅ Added cross-tenant user enumeration prevention
- ✅ Secured authentication flows with server-side enforcement
- ✅ Resolved audit findings with proper credential declarations and env var management

### Performance & Reliability
- ✅ Fixed ESM→CJS build pipeline issues with esbuild
- ✅ Optimized table formatting for large datasets (1000+ rows)
- ✅ Implemented batch operations with deduplication and integrity checks
- ✅ Added idempotent operations with X-Idempotency-Key support

### Developer Experience
- ✅ Created interactive TUI for discoverability and ease of use
- ✅ Implemented smart auto-detection for search and import workflows
- ✅ Built session persistence to reduce credential entry friction
- ✅ Designed intuitive CLI with 100+ commands across 20 command groups
- ✅ Created comprehensive documentation (README, SKILL.md, API references)

### Feature Delivery
- ✅ v1.1.0: Consolidated CLI with admin/maintenance/pipeline/campaigns/generate/clients groups
- ✅ v1.2.0: Added soft-delete, restore, purge, and import integrity features
- ✅ v2.0.2: Complete rewrite with TUI, Chrome Extension, npm distribution

### Integration & Partnerships
- ✅ Salesforce lead sync connector
- ✅ HubSpot bi-directional synchronization
- ✅ Google Reviews integration
- ✅ Unipile multi-channel automation
- ✅ EpsimoAI token exchange and credit management

---

## 📊 GitHub Activity Summary (Last 24 Months)

- **Total Commits:** 271+ tracked commits
- **Active Repositories:** 30+ projects maintained
- **Core Development:** `leadgenius-cli` (100+ commits, primary focus)
- **Integration Projects:** 5+ enterprise integrations
- **Skill Registry:** Multiple SKILL.md files created for agent frameworks
- **Code Distribution:** npm package published and maintained

### Recent Milestones (May 2026)
- Completed comprehensive SKILL.md documentation for AI agent skill registry
- Finalized CLI rewrite with all 20 command groups and 100+ commands
- Deployed Chrome Extension OAuth and email sign-in flows
- Published npm package distribution with cross-platform binaries

---

## 🎓 Expertise Areas

| Area | Proficiency | Examples |
|------|-------------|----------|
| Full Stack CLI Development | Expert | LeadGenius CLI (20 groups, 100+ commands) |
| REST API Design & Integration | Expert | 5+ enterprise API integrations |
| TypeScript/Node.js | Advanced | Backend services, CLI tools, automation |
| Authentication & Security | Advanced | Cognito, OAuth 2.0, JWT, authorization patterns |
| React Frontend Development | Intermediate | UI dashboards, extensions, interactive interfaces |
| DevOps & Distribution | Intermediate | npm publishing, binary packaging, CI/CD |
| Database & Data Pipeline | Intermediate | DynamoDB, SQL, ETL workflows, batch processing |
| Enterprise Integration | Expert | Salesforce, HubSpot, Google, Unipile |

---

## 💡 Notable Technical Decisions

1. **TypeScript over Python:** Improved type safety, performance, and npm ecosystem access
2. **Interactive TUI:** Enhanced discoverability and reduced cognitive load for complex CLI
3. **Session Persistence:** Eliminated repetitive credential entry, improved UX
4. **CSV Auto-Detection:** Automatic dialect detection and header mapping reduces friction
5. **Manifest V3 Extension:** Future-proofed Chrome Extension following latest standards
6. **Cross-Platform Binaries:** Enabled distribution without Node.js dependency
7. **Soft-Delete Architecture:** Non-destructive operations with data recovery capabilities

---

## 📈 Growth & Learning

- Mastered TypeScript ecosystem for production-grade CLI applications
- Advanced expertise in AWS Cognito authentication flows
- Experienced with AI agent frameworks and skill registry patterns
- Developed strong practices in security-first development
- Learned binary packaging and cross-platform distribution
- Demonstrated ability to lead large feature initiatives through completion

---

## 🏆 What Stands Out

✨ **Production-Grade Quality:** All projects follow best practices with comprehensive error handling, security considerations, and documentation

✨ **User-Centric Design:** Focus on developer experience evident in CLI design, smart defaults, and interactive interfaces

✨ **Enterprise Reliability:** Proven ability to build systems handling sensitive business data with proper security and audit trails

✨ **Full Ownership:** End-to-end responsibility from API design through CLI implementation to distribution

✨ **High Velocity:** Delivered v2.0.2 complete rewrite with all features while maintaining production stability

---

## 📝 Additional Notes

- Active open-source contributor (public repositories available for review)
- Strong documentation practices (comprehensive README, SKILL.md, API docs)
- Experienced with enterprise software requirements and security audits
- Comfortable with async remote work and self-motivated development
- Quick learner with ability to master new technologies and frameworks

---

**Last Updated:** May 5, 2026  
**Generated from:** 24 months of GitHub activity (May 2024 - May 2026)
