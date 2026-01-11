# KPPMCH Pregnancy Care
**Maternal Care and Automation Platform**

An advanced healthcare automation platform engineered for Kamphaeng Phet Municipality Community Hospital (KPPMCH). This system integrates modern web technologies with automated communication protocols to enhance maternal health monitoring and patient engagement.

---

### Project Specification
| Category | Detail |
| :--- | :--- |
| **Project Name** | KPPMCH Pregnancy Care |
| **Organization** | Kamphaeng Phet Municipality Community Hospital (KPPMCH) |
| **Developer** | Ratchanon Noknoy, B.Sc. (Software Engineering) |
| **Institution** | Mae Fah Luang University |
| **Primary Framework** | Next.js 14+ (App Router Architecture) |
| **Messaging API** | LINE Messaging API |
| **Database Solution** | Google Sheets API / Apps Script |

---

### System Architecture & Design Patterns

The platform implements **Clean Architecture** principles to ensure the healthcare logic remains decoupled from external delivery mechanisms:

#### 1. Presentation & Interaction Layer
* **Next.js Server Components:** Optimized for high-speed delivery of patient tracking interfaces while maintaining sensitive data security.
* **LINE Messaging API Integration:** Acts as the primary automated notification layer, delivering personalized maternal care alerts directly to patients' mobile devices.
* **CSS Modules Architecture:** Implements local-scoped styling to ensure UI consistency and modularity across the maternal tracking dashboard.

#### 2. Automation & Logic Layer
* **Serverless Automation:** Utilizes Next.js API Routes to trigger scheduled notifications and process maternal health milestones.
* **Event-Driven Workflow:** Systems are designed to respond to patient data updates, triggering real-time clinical alerts via the LINE ecosystem.

#### 3. Data Infrastructure (Cloud-Based)
* **Asynchronous Data Layer:** Interfaces with Google Cloud services to provide a cost-effective and highly accessible data storage solution for clinical staff.
* **Service Account Security:** Ensures that all interactions with the backend data store are authenticated and encrypted.

---

### Technical Infrastructure
| Component | Technology | Description |
| :--- | :--- | :--- |
| **Core Engine** | Next.js | Hybrid rendering for optimal performance and patient data protection. |
| **Automation** | LINE Messaging API | Automated notification and maternal care tracking protocol. |
| **Styling Strategy** | CSS Modules | Scoped and maintainable CSS for complex healthcare interfaces. |
| **Cloud Integration** | Google Apps Script | Middleware for handling clinical data operations. |
| **Deployment** | Vercel | Production-grade hosting with managed SSL and high availability. |

---

### Core Functional Modules
* **Automated Clinical Alerts:** Intelligent scheduling system that sends pregnancy milestone reminders via LINE.
* **Maternal Progress Tracking:** A dedicated patient-side interface for monitoring health data and appointment history.
* **Clinical Workflow Optimization:** Streamlined data collection tools designed for hospital healthcare providers.
* **Validated Security Layer:** Multi-tier validation to ensure the privacy and integrity of sensitive maternal information.

---

### System Implementation
| Step | Action | Command |
| :--- | :--- | :--- |
| 1 | Clone Repository | `git clone https://github.com/Ratchanon2318/kppmch-pregnancy-care.git` |
| 2 | Install Dependencies | `npm install` |
| 3 | Configure Variables | `cp .env.example .env.local` |
| 4 | Execute Development | `npm run dev` |

---

### Academic & Professional Context
* **Software Engineering Expertise:** Developed with a focus on high-reliability healthcare systems, applying principles from the Software Engineering program at **Mae Fah Luang University**.
* **Impact:** Designed to bridge the gap between clinical data and patient accessibility through automation.

---

### License
This project is licensed under the **MIT License**.
Copyright (c) 2026 Ratchanon Noknoy. All rights reserved.

---

### Contact Information
* **Software Engineer:** Ratchanon Noknoy
* **LinkedIn:** [linkedin.com/in/ratchanon-noknoy](https://www.linkedin.com/in/ratchanon-noknoy/)
* **Portfolio:** [ratchanonnoknoy.vercel.app](https://ratchanonnoknoy.vercel.app/)
