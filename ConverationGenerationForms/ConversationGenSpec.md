# ✅ Greenteam Test Admin Module Specification

## 🎯 Purpose

Simulate complex, multi-person, multi-meeting conversations for various team types to test and validate the performance of Greenteam’s AI agents. This module enables rich testing by generating realistic task backlogs, persona dynamics, and team meeting cadences.

---

## 🧭 1. Team Types & Meeting Cadences

| **Team Type**    | **Key Meeting Types**                                                   | **Cadence**              |
|------------------|-------------------------------------------------------------------------|--------------------------|
| **Engineering**  | Sprint Planning, Daily Standup, Review/Demo, Retrospective, Grooming    | Weekly, Bi-weekly        |
| **Marketing**    | Campaign Planning, Content Sync, Brand Check-ins, Analytics Review      | Weekly, Monthly          |
| **C-Level Execs**| Board Prep, Strategy Sync, Budget Review, Cross-functional Check-ins    | Monthly, Quarterly       |
| **Product**      | Feature Prioritization, Stakeholder Syncs, Feedback Loop Review         | Weekly, Bi-weekly        |
| **Sales**        | Pipeline Review, Account Strategy, Forecast Meeting                     | Weekly, Bi-weekly        |
| **Operations**   | Resource Planning, Policy Update, Compliance Check                      | Monthly, Ad hoc          |

---

## 🧱 2. Meeting Simulation Modules (Selectable)

### 🌀 Sprint Cycle (Engineering/Product Teams)
- [ ] Sprint Planning  
- [x] Daily Standups  
- [ ] Mid-Sprint Check-In  
- [ ] Sprint Review / Demo  
- [x] Retrospective  
- [ ] Backlog Grooming  

### 🎯 Marketing Team Cadence
- [ ] Campaign Kickoff  
- [ ] Weekly Content Sync  
- [ ] Analytics Review  
- [x] Channel Performance Review  
- [ ] Quarterly Strategy Planning  
- [x] Product-Market Fit Alignment  

### 🧠 C-Level / Executive Team Cadence
- [ ] Board Meeting Prep  
- [ ] Quarterly OKR Review  
- [ ] Executive Leadership Sync  
- [ ] Strategic Planning Session  
- [ ] Crisis / PR Management Review  
- [ ] Budget / Funding Review  
- [ ] Cross-department Initiative Check-Ins  

---

## 🧩 3. Persona Engine (Lego-style)

### 🔧 Modular Persona Components
- **Roles:** Tech Lead, Dev, QA, PM, Exec, Ops, Sales  
- **Behavior Styles:** Constructive, Passive, Disruptive, Overconfident  
- **Communication Styles:** Diplomatic, Aggressive, Long-winded, Minimalist  

### 🧍‍♂️ Archetype Personas
- [ ] "The Ghost" – never speaks  
- [ ] "Frustrated Genius" – explodes in meeting #5  
- [ ] "The Optimist" – always says things are great  
- [ ] **"Over-inflated Ego"** – dominates discussions, derails topics  
- [ ] "Middle Manager Jargon Machine" – talks, says nothing  
- [ ] "New Joiner" – naive but occasionally insightful  

---

## 📦 4. Backlog & Task Engine

- [ ] Generate multi-epic backlogs with stories & subtasks  
- [ ] Tasks have varying status: `In Progress`, `Blocked`, `Done`, `In Review`  
- [ ] Link tasks to meeting discussions via ticket IDs  
- [ ] Enable backlog slicing by sprint/week/timeline  
- [ ] Task progression reflected in meetings chronologically  

---

## 💬 5. Conversation Generator Engine

- [ ] Generate dialogue based on task updates and personas  
- [ ] Include:
  - Task movement discussions  
  - Blockers and escalation  
  - Personality conflicts  
  - Passive/aggressive dynamics  
  - Meetings that go off-topic  

- [ ] Vary meeting tone:
  - Productive  
  - Tense  
  - Off-track  
  - Circular  

---

## 🧠 6. Management Meeting Simulation

- [ ] Simulate management-level and C-level discussions  
- [ ] Include:
  - Strategy debates  
  - Political undercurrents  
  - Ego-driven derailments  
  - Budget and OKR reviews  
  - Mismatched departmental goals  

---

## ⚙️ 7. Configuration Interface (Sim Control Panel)

- [ ] Select team type  
- [ ] Choose meeting type  
- [ ] Define or auto-generate persona mix  
- [ ] Select sprint/backlog slice  
- [ ] Set meeting tone  
- [ ] Toggle persona flags:
  - Include Ego  
  - Include Silent Ghost  
  - Force Conflict  
  - Add Escalation  

---

## 📈 8. Output & Evaluation

- [ ] Generate structured meeting transcripts  
- [ ] Tag speaker metadata: role, behavior type, engagement level  
- [ ] Track:
  - Task references  
  - Emotional tone changes  
  - Speaker participation quality  
  - Conflict and resolution markers  

- [ ] Enable evaluation of:
  - Agent recognition of dynamics  
  - Persona detection accuracy  
  - Insight extraction (who’s effective, what’s stuck)

---

## 🧪 9. Sample Use Cases

- Simulate Sprint Planning with a frustrated dev and passive PM  
- Marketing campaign kickoff where ego clashes stall progress  
- C-level budget meeting with long-winded exec and no clear outcome  

---

## 📍 Status: IN PROGRESS

This module is critical to validating the full value of Greenteam’s conversation intelligence layer. It will serve as a foundation for all testing, benchmarking, and demo scenarios.

