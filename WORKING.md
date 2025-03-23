# COMPIXS(intro)

Develop a pixel-art, RPG Maker-inspired business simulation game using Unity. The game will feature backend AI integration with LLaMA for dynamic NPC behavior.

---

## SCOPE

### 1) How a Real Business Company Looks According to Domains, Their Responsibilities, and Key Simulation Metrics (e.g., Revenue, etc.)

---

### COMPANIES

#### 1) Basic Outline of a Company

- **Board of Directors**  
  - The board consists of investors and, in this case, includes the user.
- **Top Management (C-Suite / Executive Leadership)**  
  - **CEO (Chief Executive Officer):** Overall performance checker.
  - **COO (Chief Operating Officer):** Oversees day-to-day operations.
  - **CFO (Chief Financial Officer):** Manages finances, budgeting, and financial planning.
  - **CTO (Chief Technology Officer):** Drives tech strategy and product innovation.
  - **CMO (Chief Marketing Officer):** Leads marketing and branding.
  - **CHRO (Chief Human Resources Officer):** Oversees human resources.
  - **CSO (Chief Strategy Officer):** Focuses on long-term strategy.

- **Senior Management / Executive**  
  - **Vice Presidents (VPs), Senior VPs (SVPs), and Executive VPs (EVPs):**  
    - Oversee major business units; assigned according to company requirements.
  
- **Middle Management**  
  - **Directors / General Managers / Department Heads:**  
    - Responsible for translating strategic directives into operational plans and overseeing multiple teams or specific functions.
  
- **Lower Management**  
  - **Managers / Supervisors / Team Leads:**  
    - Directly supervise the day-to-day work of individual contributors.
  
- **Frontline Employees**  
  - **Individual Contributors (ICs):**  
    - Execute tasks, produce products, provide services, or deliver customer support.
  - **Support Staff:**  
    - May include administrative personnel, technicians, or other essential roles.

---

### 2) Types of Companies

1. **Product-Based Companies**  
   - **Definition:** Focus on developing, manufacturing, and selling physical or digital products.  
   - **Examples:** Apple (hardware & software), Microsoft (software & hardware).

2. **Service-Based Companies**  
   - **Definition:** Deliver value by providing professional services rather than tangible products.  
   - **Examples:** Consulting firms, law firms, banks, hospitals.

3. **Hybrid Companies**  
   - **Definition:** Combine both products and services to create value (e.g., selling a product with an accompanying service or subscription).  
   - **Examples:** Tesla (selling cars plus software updates/service), Adobe (software with ongoing cloud services).

4. **Platform or Marketplace Companies**  
   - **Definition:** Create a platform that connects two or more distinct user groups (such as buyers and sellers) and often facilitate transactions between them.  
   - **Examples:** Amazon, Airbnb, Uber.

5. **Franchise Models**  
   - **Definition:** Expand by licensing their business model and brand to independent operators.  
   - **Examples:** McDonald’s, Subway.

6. **Nonprofit / Social Enterprises**  
   - **Definition:** Focus on achieving a social, environmental, or community mission rather than maximizing profit.  
   - **Examples:** Charity organizations, social enterprises like TOMS.

---

### THOUGHT

I have come to understand the number of roles and workers present in a company. I’ve concluded that according to the company type and product type, we can define a public company structure that handles the organization effectively. Therefore, first determine the type of company you are going to work on.

---

#### PRODUCT-BASED COMPANY

If the company is product-based—focused on developing, manufacturing, and selling physical or digital products—then consider the following structure:

---

#### ROLES

##### **BOARD OF DIRECTORS**  
- **Role:**  
  - The user (main investor) acts as one main long-term visionary.
  
##### **CEO**  
- **Responsibilities:**  
  1. Overall strategy maker.  
  2. Vision creator—oversees the vision from above.  
  3. Creates strategies based on the vision.  
  4. For each strategy, secures funding, gains user approvals, and allocates resources to the C-suite.  
  5. Builds or reassigns teams based on whether the strategy is an in-task refinement or a new task.  
  6. Leads team-building by meeting with CTO, CFO (and possibly CMO/COO) to share the strategic vision and desired organizational structure.

##### **CTO, CFO, etc.**  
- **CTO/CFO Roles:**  
  - **CTO:** Analyzes technology and product innovation needs; works with senior tech leads to assemble the technical team.  
  - **CFO:** Analyzes financial needs (budgeting, pricing strategy, funding requirements); determines senior finance leads needed (e.g., accounting manager, financial planning lead, cost-control supervisor) and proposes a financial team structure.

##### **Senior Leads Assemble Teams**  
- **Process:**  
  - The CTO holds sessions with senior tech leads, who then form their own small teams focused on design, engineering, and user testing.  
  - The CFO meets with senior finance leads to assemble a lean financial unit to manage funding, cost control, and pricing strategies.  
  - The CEO, through regular strategic meetings, reviews progress, makes adjustments, and ensures all teams work in tandem to launch the jackfruit product successfully.

##### **OVERALL ROLES**  
1. **Board of Directors:** (User and NPCs as long-term visionaries)  
2. **CEO:** Sees the vision, decides strategies, and communicates to directors.  
3. **C-Suite (CFO, CTO, etc.):** Work under the CEO, help build teams according to the strategy, and report back to the CEO if adjustments are needed.  
4. **Senior Management:** Executes team building and functional strategies.  
5. **Middle Management:** Translates strategy into operational plans.  
6. **Lower Management & Support Staff:** Execute day-to-day tasks.

---

#### Every Company Common Baseline

**Executive Sponsor / C-Suite Leadership**  
- **CEO:**  
  - **Role:** Sets the vision and overall direction, ensuring the new product aligns with strategic goals.  
  - **Task:** Oversee the project, communicate key decisions to the board, and support the team with resources and guidance.
  
- **Chief Product Officer (CPO) or Chief Technology Officer (CTO):**  
  - **Role:** Acts as the executive sponsor for product creation.  
  - **Task:** Define product strategy, prioritize features, and coordinate with all functional areas.

- **Product Manager:**  
  - **Role:** Leads the new product initiative on a day-to-day basis.  
  - **Tasks:** Gather customer insights, develop a product roadmap, coordinate team functions, and serve as the main contact for the project.

- **R&D / Innovation Lead:**  
  - **Role:** Drives research, development, and innovation for the new product.  
  - **Tasks:** Explore new materials/technologies (e.g., unique processing techniques for jackfruit-based products), prototype, and test concepts.

- **Design & User Experience (UX) Lead:**  
  - **Role:** Oversees product design and user experience.  
  - **Tasks:** Create appealing product designs and ensure usability and aesthetics through collaboration with R&D and engineering.

- **Engineering/Manufacturing Lead:**  
  - **Role:** Manages technical production aspects.  
  - **Tasks:** Translate design and technical requirements into a manufacturable product, set up production processes, and monitor quality and scalability.

- **Marketing & Sales Lead:**  
  - **Role:** Develops the go-to-market strategy.  
  - **Tasks:** Define target audiences, craft messaging, and plan/execute marketing campaigns and distribution strategies.

- **Supporting Functions (Lean or Outsourced Initially):**  
  - **Financial Planning & Analysis (FPA):** Builds financial models for pricing, cost management, and budgeting.  
  - **Legal & Compliance:** Ensures regulatory and IP requirements are met.  
  - **Customer Support/Feedback Coordinator:** Gathers early user feedback and manages customer support, influencing product iterations.

---

## FINALISATION 2

### **Board of Directors (Top-Level)**

- **User as the Main Investor & Board Member:**  
  - **Role:**  
    - Inputs the product name (e.g., “Jackfruit Delight”).  
    - Acts as the biggest investor and sets the initial high-level vision and strategy.
  - **In-Game Impact:**  
    - Provides initial capital and strategic direction.  
    - Can trigger new initiatives with additional investments.

- **NPC Board Directors (Long-Term Visionaries):**  
  - **Role:**  
    - Serve as co-visionaries, contributing ideas for product enhancements, expansion, or budget allocation.  
    - If the user doesn’t provide additional input, they generate ideas and set budgets automatically.
  - **In-Game Impact:**  
    - Determine long-term strategy and adjust budgets, influencing growth and innovation.

### **Process Flow Example**

1. **Product Initiation:**  
   - The user enters the product name, activating the board setup and recognizing the user as the lead board member.

2. **Budget & Vision Setting:**  
   - The game assigns a starting budget based on the product category.  
   - NPC board directors review the user’s input:  
     - **If additional input is provided:** NPCs adjust the budget and roadmap accordingly.  
     - **If no additional input is provided:** NPCs generate their own ideas and set a revised budget.

3. **Decision-Making & Feedback Loop:**  
   - The CEO (NPC) receives the board’s directives and works with the executive team (CTO, CFO, etc.) to implement the product strategy.  
   - As simulation metrics (e.g., daily revenue, balance sheets) are updated, the board reviews performance and adjusts strategy (e.g., reinvest in R&D or launch new marketing campaigns).

### **Why This Structure?**

- **User Empowerment:** The user, as the main investor, sets the initial direction and feels directly involved in high-level decisions.
- **Dynamic Vision:** NPC board directors provide long-term strategy and innovation, ensuring the game evolves even without additional user input.
- **Balanced Decision Flow:** Mimics real public companies where the board guides strategy while the executive team handles operations, with simulation metrics influencing future decisions.

---

## FINALISATION 3

### **Game Time and Scheduling**

1. **Time Conversion:**  
   - Define 1 game day = 1 real hour using Unity’s `Time.deltaTime` and a custom clock system.

2. **Daily Cycles:**  
   - Divide the day into phases:  
     - **Morning:** Strategy Meetings  
     - **Afternoon:** Operations  
     - **Evening:** Review and Reflection  
   - Schedule NPC dialogues and decisions to occur in phases, not all at once.

### **User Input and Initialization**

1. **User Input:**  
   - At game start, the player enters the product name (e.g., “Jackfruit Delight”).  
   - This input becomes the company’s identity and triggers instantiation of Board of Directors NPCs (with the user as the main investor).

2. **Initialization of NPC Roles:**  
   - The game creates the organizational hierarchy (Board, CEO, C-Suite, etc.) using pre-defined templates for a product-based company.  
   - Each NPC is assigned responsibilities (e.g., CTO leads tech discussions, CFO focuses on budgeting).

### **NPC Interaction & Dialogue System**

1. **Dialogue Trees & AI Integration:**  
   - Use dialogue trees or AI (LLaMA integration) to generate realistic, context-sensitive NPC conversations based on their roles and current simulation metrics.

2. **Natural Conversation Flow:**  
   - Build a conversation scheduler where each major meeting or decision event spans several in-game days (e.g., “Day 1” for initial meetings, followed by follow-up discussions on subsequent days).

3. **Simulated "Real-Time" Communication:**  
   - NPC dialogues are timed (using timers or coroutines) to delay dialogue lines and mimic natural pacing.  
   - Include cutscenes or dialogue logs where players can review long conversations and debates.

### **Decision-Making and Task Delegation**

1. **High-Level Meetings:**  
   - The CEO holds scheduled meetings with the C-Suite (CTO, CFO, etc.) to discuss product strategy.
   - Each executive then holds internal team meetings over the next in-game days.

2. **Task Delegation:**  
   - After meetings, each executive assigns tasks to their senior leads.  
   - For example, the CTO directs senior tech leads to prototype features, while the CFO assigns budgeting tasks to finance leads.

3. **NPC Feedback Loop:**  
   - At the end of each in-game day, a review meeting is held where NPCs report progress (via dialogue logs and updated simulation metrics) to the CEO and Board.  
   - These reviews can trigger strategic shifts (e.g., more investment in R&D if production targets aren’t met).

### **Integration with Simulation Metrics**

1. **Key Simulation Metrics:**  
   - **Financial Metrics:** Daily Revenue, Profit Margins, Balance Sheets, COGS, Operating Expenses, Cash Flow.  
   - **Operational Metrics:** Production Volume, Quality Control Pass Rate, Supply Chain Efficiency, Team Performance, and Productivity.
   - **Market & Customer Metrics:** Customer Acquisition Cost (CAC), Customer Lifetime Value (CLV), Market Share, and Customer Satisfaction (NPS or CSAT).
   - **Growth & Innovation Metrics:** R&D Cycle Time, New Product Iterations, Employee Turnover & Engagement.

2. **Dynamic Adjustments:**  
   - NPCs adjust strategies based on metric thresholds (e.g., if daily revenue drops, the CFO triggers a cost-control discussion).

3. **Visualization:**  
   - Display real-time dashboards in the game UI, showing how board and executive decisions affect the business over each simulated day.

### **Creating a Real-Life Pace**

1. **Pacing and Realism:**  
   - Simulate gradual progress; for instance, product quality or revenue changes take several in-game days.
   - Use narrative sequences to show "Day 1", "Day 2", etc., with reflective dialogue highlighting challenges and improvements.

2. **Event-Based Progression:**  
   - Certain events (e.g., product launch or funding round) require multiple days of planning, discussion, and execution.
   - This creates a dynamic, realistic environment with gradual decision-making rather than rapid-fire responses.

---

## Example Scenario: "Jackfruit Delight" Product Launch

### **Day 1: Product Initiation**
- **User Input:**  
  - Player enters the product name “Jackfruit Delight.”
- **Board Meeting:**  
  - The main investor (user) and NPC board directors hold an initial meeting. The CEO outlines the vision.
- **Dialogue:**  
  - NPCs discuss initial market research and decide on preliminary budget allocations.

### **Day 2-3: C-Suite Meetings and Team Formation**
- **C-Suite Meetings:**  
  - The CEO meets with CTO, CFO, and CMO.
- **Team Formation:**  
  - The CTO holds sessions with senior tech leads to form a small product development team.  
  - The CFO meets with senior finance leads to set up the financial model.
- **Dialogue:**  
  - Conversations unfold over several in-game hours, reflecting realistic discussions and decision-making.

### **Day 4-5: Operational Rollout and Feedback Loop**
- **Operational Rollout:**  
  - Teams execute tasks: production planning, marketing strategies, and financial forecasting are underway.
- **Metrics Update:**  
  - Daily revenue and KPIs are updated on a dashboard visible to the player.
- **Feedback Loop:**  
  - A daily review meeting occurs where teams share progress and the board reviews performance, triggering adjustments if needed.

---

## FINAL THOUGHTS

### **User as Main Investor & Board of Directors**
- The user inputs the product name and acts as the primary investor, setting the initial vision and strategic direction.
- NPC board directors (long-term visionaries) complement the user’s input by generating ideas and managing budgets if no additional input is provided.

### **Executive Team and Communication Flow**
- The CEO, supported by the C-suite (COO, CFO, CTO/CPO, CMO, etc.), drives strategy and operational execution.
- Each executive builds their team by engaging with senior leads who then assemble middle and lower management teams.
- Decisions and strategic adjustments are made collaboratively over multiple in-game days to simulate realistic business pacing.

### **Simulation Dynamics**
- Key metrics (financial, operational, market, and innovation) update throughout the game, influencing NPC dialogue and decision-making.
- The game uses scheduled phases (morning, afternoon, evening) to mimic daily business operations, ensuring a realistic pace that mirrors real-life company dynamics.

---

This Markdown file provides a comprehensive outline of your simulation game’s scope, organizational structure, NPC roles, responsibilities, and key simulation metrics. It’s designed to capture a realistic, time-based, business simulation where decisions unfold gradually over “days” (with each game day equal to one real hour), closely mimicking the pacing and conversations found in real-life companies.


# DEVELOPMENT OF COMPIXS 

