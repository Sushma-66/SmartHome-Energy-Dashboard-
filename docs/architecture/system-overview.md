# 📈 System Overview

High-level system components:

```mermaid
graph TD
A[User Dashboard] --> B[Backend API]
B --> C[Smart Device Cloud Service]

---

## 🔄 `docs/architecture/data-flow-diagram.md`

```markdown
# 🔄 Data Flow Diagram (DFD)

```mermaid
flowchart TD
User --> UI --> API --> Database
API --> SmartDeviceAPI
