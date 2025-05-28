# Standard User Journey: GreenTeam
## Business Performance Monitoring Application

This document presents a standard user journey showing the typical flow an Administrator would follow when using the business performance monitoring application for daily operational tasks.

## User Persona
**Administrator/Manager** who needs to monitor business unit performance, track project progress, and manage team communication quality on a daily basis.

##  Context

**Usage Context:** Daily monitoring of business operations, weekly team performance reviews, and ad-hoc project management tasks requiring immediate attention to communication quality and productivity metrics.

## User Journey Flow

### 1. **Entry Point: Business Units Overview**
**Goal:** Get daily overview of business performance  
**User arrives at:** Main application landing page  
**Actions:** Reviews business unit rectangles, checks performance scores (red/orange/yellow/light blue/green indicators)  
**Decision point:** Identifies underperforming unit or specific area needing attention  

### 2. **Navigate to Personal Dashboard**
**Goal:** Access personalized control center  
**Entry:** Clicks user icon in top-right corner  
**Actions:** Reviews welcome message, checks notification counter (red alerts/total alerts), monitors real-time meeting scores  
**Key insight:** Identifies pinned high-risk projects requiring immediate attention  

### 3. **Drill Down to Project Detail**
**Goal:** Investigate specific underperforming project  
**Entry:** Clicks on pinned high-risk project from dashboard  
**Actions:** Reviews project objective, client info, expected outcomes, checks deadline status  
**Decision point:** Determines whether to focus on Team, Tasks, or Meetings  

### 4. **Team Performance Review**
**Goal:** Assess team member performance and communication  
**Entry:** Clicks "Team" button from Project Detail  
**Actions:** Reviews team member cards, checks last 3 productivity/communication evaluations, expands cards for detailed performance history  
**Key activities:** Identifies team members needing support, reviews communication nudges  

### 5. **Task Status Check**
**Goal:** Monitor project progress and deadlines  
**Entry:** Returns to Project Detail, clicks "Tasks" button  
**Actions:** Filters tasks by status (To Do/In Progress/Done), reviews assignments and deadlines, expands cards for task details  
**Assessment:** Evaluates project timeline and potential bottlenecks  

### 6. **Meeting Analysis**
**Goal:** Review communication quality and meeting effectiveness  
**Entry:** Clicks "Meetings" button from Project Detail  
**Actions:** Reviews recent meetings, checks meeting analysis scores, accesses recordings and recommendations  
**Insights:** Identifies communication patterns affecting project performance  

### 7. **System Configuration (As Needed)**
**Goal:** Optimize AI evaluation settings  
**Entry:** Returns to Dashboard, clicks Settings button  
**Actions:** Accesses Meeting Analysis Settings, adjusts transcription parameters, reviews AI Workers performance  
**Outcome:** Fine-tunes system for better performance monitoring  

### 8. **Action Implementation**
**Goal:** Address identified issues  
**Entry:** Returns to relevant project screens  
**Actions:** 
- Pins critical tasks to dashboard
- Schedules team member check-ins
- Reviews meeting recommendations
- Updates project priorities  

### 9. **Monitoring Loop**
**Goal:** Continuous performance tracking  
**Entry:** Returns to Personal Dashboard  
**Actions:** Monitors real-time meeting communication scores, checks for new notifications, reviews updated performance metrics  
**Outcome:** Maintains ongoing awareness of business unit health  

## Key Journey Characteristics

**Daily Workflow Pattern:**
1. **Morning Check:** Business Units Overview → Personal Dashboard → Notifications review
2. **Deep Dive:** Project Detail → Team/Tasks/Meetings analysis
3. **Action Phase:** Issue identification and intervention planning
4. **Continuous Monitoring:** Dashboard monitoring throughout day

**Decision Points:**
- Which business unit needs immediate attention?
- Is the issue team-related, task-related, or communication-related?
- Do AI evaluation settings need adjustment?
- Which items should be pinned for ongoing monitoring?

**Success Metrics:**
- Projects moved from red/orange to green performance scores
- Improved team communication evaluations
- Reduced number of high-risk pinned projects
- Proactive issue identification through real-time monitoring

**Pain Points:**
- Information overload across multiple performance metrics
- Context switching between different project areas
- Dependency on AI evaluation accuracy
- Approval bottlenecks for system configuration changes

# User Journey Based on Wireframe Breakdown

This document presents a screen-by-screen User Journey derived from the provided wireframe breakdown. It aims to give a comprehensive view of the user's experience through the application, focusing on an Administrator's workflow for monitoring business performance and managing projects.

| Screen # & Name | Goal | Actions | Response | Exit Criteria | Risks & Wins |
|-----------------|------|---------|----------|---------------|--------------|
| 1. Business Units Overview | Get high-level view of all business units' performance and revenue | View rectangles showing unit performance, click on user icon for dashboard, or click on specific business unit | Displays business units with revenue/headcount data and color-coded performance scores | User clicks on a business unit or navigates to personal dashboard | **Win:** Visual overview makes performance gaps immediately apparent; **Risk:** Information overload with multiple metrics |
| 2. Client Overview | View all clients associated with selected business unit | Browse client list, click on specific client | Shows list of clients for the selected business unit | User selects a client to view their tasks | **Risk:** NO INFORMATION GIVEN about client prioritization or filtering |
| 3. Client Task Overview | Review and manage tasks for selected client | Hover or right-click on tasks to pin them to personal dashboard | Displays task list with pinning functionality | User pins desired tasks or navigates elsewhere | **Win:** Quick pinning functionality for important tasks; **Risk:** No task filtering or sorting options mentioned |
| 4. Personal Dashboard | Monitor real-time performance and manage pinned items | View welcome message, check notifications, monitor online meetings, review pinned projects, access settings | Displays real-time meeting scores, notifications counter, productivity metrics, and pinned high-risk projects | User navigates to specific project details or settings | **Win:** Centralized command center with real-time data; **Risk:** Potential information overload with moving elements |
| 5. Project Detail | Get comprehensive overview of selected project | Click on Team, Tasks, or Meetings buttons to access respective sections | Shows project objective, client info, expected outcomes, and navigation options with counts | User selects one of the three main sections (Team/Tasks/Meetings) | **Win:** Clear project overview with easy navigation; **Risk:** NO INFORMATION GIVEN about project status updates |
| 6. Team Screen | Manage team members and review their performance | View team member cards, expand for details, add/remove members, access communication tools | Displays team member information with performance scores and communication trends | User completes team management tasks or navigates back | **Win:** Comprehensive team member insights with performance tracking; **Risk:** Removing team members may require confirmation workflow |
| 7. Project Tasks | Track and filter project tasks by status | Use task filters (All/To Do/In Progress/Done), expand task cards for details | Shows filtered task list with member assignments and deadlines | User completes task review or returns to project overview | **Win:** Clear task filtering and status tracking; **Risk:** NO INFORMATION GIVEN about task editing capabilities |
| 8. Meetings | Review meeting history and prepare for upcoming meetings | Filter meetings, expand cards, take readiness tests, access recordings and analysis | Displays meeting information with analysis, recordings, and recommendations | User completes meeting review or accesses external calendar | **Win:** Comprehensive meeting analysis and preparation tools; **Risk:** Readiness test may be time-consuming |
| 9. Meeting Analysis Settings | Configure AI evaluation parameters and system behavior | Adjust transcription settings, generate recommendations, ensure compliance settings | Updates meeting evaluation system configuration | User saves settings and navigates to other admin sections | **Win:** Customizable AI evaluation system; **Risk:** Complex settings may require training |
| 10. Projects | Manage all organizational projects | Browse project list (10 per page), create new projects | Shows paginated project list with creation options | User creates new project or selects existing project for editing | **Risk:** Limited to 10 projects per page may require excessive pagination |
| 11. AI Workers | Manage analytics agents and their behavior | Edit agent logic, add new agents, review existing agents | Displays agent list with editing capabilities | User completes agent management or navigates to chat functionality | **Win:** Customizable AI analytics; **Risk:** Editing AI logic requires technical expertise |
| 12. AI Worker Chat | Interact with AI agent for meeting analysis | Chat with agent, upload meeting transcripts | Provides communication evaluations and responses with knowledge panel | User receives satisfactory analysis or uploads additional transcripts | **Win:** Direct AI interaction for custom analysis; **Risk:** Chat interface may not provide immediate results |
| 13. Data | Access internal evaluation instructions and knowledge | Browse instruction lists, navigate to specific data categories | Shows list of internal meeting evaluation instructions | User navigates to Instructions or Knowledge sections | **Risk:** View-only access may limit immediate problem resolution |
| 14. Instructions | Review and modify meeting evaluation criteria | Review instruction list, request approval for edits | Shows evaluation instructions with approval workflow for changes | User completes instruction review or submits edit requests | **Risk:** Approval requirement from HR and PM heads may slow updates |
| 15. Knowledge | Manage knowledge sources for AI evaluation | View existing knowledge sources, add new items | Displays knowledge list with add functionality | User adds new knowledge items or returns to data overview | **Win:** Expandable knowledge base for better AI performance |
| 16. Organization Settings | Configure organizational parameters | Adjust organizational configuration settings | Updates system-wide organizational settings | User saves configuration changes | **Risk:** NO INFORMATION GIVEN about what specific settings are configurable |
| 17. Add AI Worker | Create new analytics agent | Input agent details and instructions | Creates new AI worker with specified parameters | User successfully creates agent or cancels creation | **Risk:** NO INFORMATION GIVEN about required fields or validation rules |
| 18. Meeting Reports Analytics | Analyze meeting performance and trends | NO INFORMATION GIVEN | NO INFORMATION GIVEN | NO INFORMATION GIVEN | **Risk:** Critical analytics screen lacks detailed specification |

