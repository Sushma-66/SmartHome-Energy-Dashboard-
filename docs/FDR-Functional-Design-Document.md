# ⚙️ Functional Design Document (FDR)

## 1. Purpose
This document defines the **functional specifications** and workflow of the SmartHome Energy Dashboard system.

## 2. System Components
| Module | Description |
|---------|-------------|
| User Authentication | Login, registration, role-based access |
| Device Management | Connect, view, and control smart devices |
| Energy Monitoring | Real-time usage analytics |
| Reports | Daily/Monthly summaries of power consumption |

## 3. Functional Requirements

### FR-01: User Login
**Description:** User can log in with email and password.  
**Trigger:** User opens dashboard.  
**Output:** Redirected to home screen.  
**Acceptance Criteria:**
- Valid credentials → login success
- Invalid credentials → error message

### FR-02: View Energy Usage
**Description:** Show current and historical energy consumption.  
**Acceptance Criteria:**
- Display daily/weekly graphs
- Fetch live data from API

### FR-03: Device Control
**Description:** Allow users to switch devices on/off remotely.  
**Acceptance Criteria:**
- Command reflected on dashboard within 3 seconds

## 4. Non-Functional Requirements
| Category | Requirement |
|-----------|--------------|
| Performance | Dashboard loads under 2 seconds |
| Security | Data encrypted in transit (HTTPS) |
| Availability | 99.9% uptime |
| Scalability | Support 10,000 devices concurrently |
