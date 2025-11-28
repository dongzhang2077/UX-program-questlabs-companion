## 6. 原型评估 - User Study 2 (Prototype Evaluation)

### 6.1 User Journey Map

We developed five comprehensive user journey maps covering the core scenarios of QuestLabs Companion:

1. **Daily Check-in Journey** - Quick emotional and academic tracking (<2 minutes)
2. **Progress Review Journey** - Visualizing personal growth over time
3. **Goal Management Journey** - Connecting daily actions to long-term vision
4. **Cohort Interaction Journey** - Privacy-preserving peer support
5. **Onboarding Journey** - First-time user experience and setup

**Reference**: Detailed user journey maps are documented in `/StoryBoard/User_Journey_Maps.md`, including touchpoints, emotional states, pain points, and opportunities at each stage.

---

### 6.2 Objectives

The primary objective of this usability testing was to **validate the effectiveness and usability of our high-fidelity Figma prototype** before final delivery. Specifically, we aimed to:

1. **Assess Usability**: Measure overall system usability using the standardized System Usability Scale (SUS)
2. **Validate Core Features**: Confirm that all four core features (Daily Check-in, Progress Dashboard, Goal Framework, Cohort Space) meet user needs
3. **Test Task Completion**: Evaluate whether users can successfully complete key workflows without assistance
4. **Verify Privacy Design**: Validate our privacy-first approach to cohort features
5. **Identify Issues**: Discover usability problems and pain points that need addressing
6. **Measure Adoption Intent**: Gauge user willingness to download and use the app

This testing was critical because it provided real user feedback on our design decisions, allowing us to validate our earlier research findings (14-person survey) and identify areas for improvement before final submission.

---

### 6.3 Methodology

#### Testing Approach

**Method**: Remote Moderated Usability Testing  
**Tool**: Figma Interactive Prototype  
**Duration**: 20-25 minutes per participant  
**Testing Period**: November 25-27, 2025

#### Participants

**Sample Size**: 5 participants  
**Recruitment Criteria**:

- College students aged 18-31+
- Currently enrolled in or interested in personal development programs
- High comfort level with mobile applications
- Willing to provide honest feedback

**Demographics**:

- Age distribution: 20% (18-20), 40% (27-30), 40% (31+)
- Tech proficiency: 100% rated "Very comfortable with mobile apps"
- Gender: Mixed (not collected to maintain privacy)

#### Testing Procedure

**Phase 1: Introduction** (2-3 minutes)

- Explain testing purpose and think-aloud protocol
- Clarify that we're testing the prototype, not the participant
- Obtain consent and answer questions

**Phase 2: Task Completion** (15-18 minutes)
Participants completed 4 core tasks:

1. **Task 1: Complete Daily Check-in**

   - Rate mood, relationships, academics
   - Select completed activities
   - Submit reflection

2. **Task 2: Review Progress Over Time**

   - Navigate to Stats section
   - View 30-day trends
   - Interpret Wheel of Life visualization

3. **Task 3: Set Up a New Goal**

   - Explore three-tier goal structure
   - Create a new weekly quest
   - Link to higher-level goals

4. **Task 4: Interact with Cohort**
   - View team progress
   - Explore privacy settings
   - Find interaction options

**Phase 3: Post-Test Survey** (5-7 minutes)

- Demographics (2 questions)
- Task-specific questions (4 questions)
- System Usability Scale (10 questions)
- Feature importance ratings (4 questions)
- Design and visual appeal (2 questions)
- Adoption intent (2 questions)
- Open feedback (3 questions)

**Total Questions**: 27

#### Data Collection

- Task completion rates and ease ratings
- SUS scores (standardized usability metric)
- Feature importance ratings (1-5 scale)
- Qualitative feedback (open-ended responses)
- Observation notes on user behavior

---

### 6.4 Data Visualization & Analysis

#### System Usability Scale (SUS) Results

**Overall SUS Score: 78.0 / 100** (Grade B - "Good")

```
Individual Participant Scores:
P1 (18-20):  65.0  ████████████████
P2 (31+):    92.5  ████████████████████████
P3 (31+):    85.0  █████████████████████
P4 (27-30):  82.5  ████████████████████
P5 (27-30):  65.0  ████████████████

Average:     78.0  ███████████████████ (Above Industry Avg: 68)
```

**Interpretation**:

- Score of 78.0 places our prototype in the **75th percentile** (top 25%)
- Grade B indicates **good usability**, acceptable for production
- Above industry average of 68, demonstrating strong user experience

#### Task Completion Results

| Task                           | Success Rate | Avg Ease (1-5) | Key Metric                      |
| ------------------------------ | ------------ | -------------- | ------------------------------- |
| **Task 1: Daily Check-in**     | 100%         | 4.4            | 60% rated "Very Easy"           |
| **Task 2: Progress Review**    | 100%         | 4.6            | 80% found section immediately   |
| **Task 3: Goal Management**    | 100%         | 4.6            | 80% understood 3-tier structure |
| **Task 4: Cohort Interaction** | 100%         | 5.0            | 100% felt privacy-comfortable   |

**Key Finding**: 100% task completion across all scenarios demonstrates strong usability and intuitive design.

#### Feature Importance Ratings

```
Feature Importance (1-5 scale, 5 = Very Important)

Daily Check-in       ████████████████████ 4.8/5 (80% rated 5)
Progress Dashboard   ████████████████████ 4.8/5 (80% rated 5)
Goal Framework       ███████████████████  4.6/5 (80% rated 5)
Cohort Space         ███████████████████  4.6/5 (60% rated 5)

Average: 4.7/5 - All features highly valued
```

**Key Finding**: All core features rated 4.6+/5, validating our feature prioritization decisions.

#### Privacy Validation

**Privacy Comfort**: 100% (5/5) rated "Yes, very comfortable"

```
Privacy-First Design Validation:
Very Comfortable      ████████████ 100% ✅
Somewhat Uncomfortable              0%
```

**Key Quote**:

> "I really like the 'Aggregated Cohort' view. It feels supportive to see my group's collective progress without the pressure of sharing private reflections or competing on a leaderboard."

#### Adoption Intent

```
Download Likelihood:
Definitely Would (5)   ████           20% (1/5)
Probably Would (4)     ████████       40% (2/5)
Might or Might Not (3) ████████       40% (2/5)
Probably Not (2)                       0%
Definitely Not (1)                     0%

Average: 3.6/5
Positive Intent (4-5): 60% ✅
```

#### SUS Statement Breakdown

**Strongest Areas** (5 = Best):

- Consistency: 5.0/5 - "Very little inconsistency"
- Ease of Use: 4.8/5 - "Easy to use"
- Learning Curve: 4.4/5 - "Students would learn quickly"
- Independence: 4.8/5 - "Don't need technical help"

**Areas for Improvement**:

- Complexity: 2.0/5 - Some users felt slight complexity
- Learning Required: 2.4/5 - Some initial learning needed

---

### 6.5 Insights (Findings)

Based on comprehensive analysis of usability testing data, we identified the following key findings:

#### ✅ Validated Strengths

**1. Core Functionality Works Well**

- 100% task completion rate across all 4 testing scenarios
- Average task ease rating: 4.6/5 (Very Easy to Easy)
- No participants struggled or failed to complete tasks

**2. Privacy-First Design is Successful**

- 100% of users felt comfortable with cohort privacy features
- Users specifically praised the "aggregated view" approach
- No concerns about oversharing or exposure

**3. Three-Tier Goal Framework Resonates**

- 80% immediately understood Vision → Quarterly → Weekly structure
- Users cited goal framework as one of most liked features
- 80% see high value in connecting daily actions to long-term goals

**4. Visual Progress Dashboard is Effective**

- 100% found charts and graphs clear and understandable
- Users appreciated multiple time ranges (7d/30d/90d)
- Trend lines and Wheel of Life were most valued visualizations

**5. Design is Consistent and Learnable**

- Scored 5.0/5 on consistency (no inconsistency found)
- 4.4/5 on "students would learn quickly"
- 4.8/5 on "easy to use"

#### ⚠️ Critical Issues Identified

**Issue 1: Lack of Cohort Interaction Features** (60% of users mentioned)

**User Feedback**:

- "Sometimes I want to send a short 'Keep it up' text message to the group, but I can't"
- "There should be a Notify section to add interaction"
- "Add a Notify/Information section to improve interaction of cohort"
- "Lack of motivation to check-in several times everyday"

**Impact**: High - This is the #1 most mentioned frustration  
**Severity**: Critical - Affects core value proposition of peer support

**Issue 2: Habit Formation and Reminder Challenges** (20% mentioned directly, implied by others)

**User Feedback**:

- "I'm a lazy casual guy. It's highly likely I'll forget to check in update tasks everyday"
- "Fear of the due time" (anxiety about deadlines)

**Impact**: High - Directly affects daily engagement and retention  
**Severity**: Critical - App depends on daily habit formation

**Issue 3: Non-Clickable UI Elements** (20% mentioned)

**User Feedback**:

- "Some icons can not be clicked"

**Impact**: Medium - Breaks user expectations and trust  
**Severity**: High - Creates confusion and frustration

**Issue 4: Wheel of Life Color Contrast** (20% mentioned)

**User Feedback**:

- "The color of the wheel of life, it is not very contractive and hard to be distinguished"

**Impact**: Medium - Affects one visualization  
**Severity**: Medium - Accessibility and clarity issue

#### 🔍 Secondary Issues and Improvement Opportunities

**Issue 5: Differentiation Concerns** (20% mentioned)

**User Feedback**:

- "How to make the app outstanding among too many similarities"

**Impact**: Medium - Marketing/positioning challenge  
**Severity**: Low - Design is solid, needs better communication

**Issue 6: Desire for Passive Tracking** (20% mentioned)

**User Feedback**:

- "Lately my best phases were when I wasn't on my phone at all (screen time <30m a day). If I could track without pulling it out would be sick"

**Impact**: Low - Niche request  
**Severity**: Low - Future enhancement opportunity

**Issue 7: Need for More Examples and Templates** (20% mentioned)

**User Feedback**:

- "Provide practical samples"

**Impact**: Low - Onboarding enhancement  
**Severity**: Low - Can improve first-time experience

#### 📊 Validation of Original Research

Our testing validated all major findings from initial user research (14-person survey):

| Original Finding (Survey n=14) | Testing Result (n=5)       | Status       |
| ------------------------------ | -------------------------- | ------------ |
| 79% want <2min check-in        | Avg ease: 4.4/5            | ✅ Validated |
| 71% prefer visual tracking     | 100% found charts clear    | ✅ Validated |
| 64% value peer accountability  | 100% motivated by cohort   | ✅ Validated |
| 71% need privacy control       | 100% felt comfortable      | ✅ Validated |
| 64% "forget to track" pain     | Users mentioned forgetting | ✅ Validated |

**Conclusion**: Design decisions throughout the project were data-driven and accurately reflected user needs.

#### 💡 Key Insights Summary

**What's Working**:

1. Core usability is strong (SUS: 78.0)
2. Privacy-first approach is differentiator
3. Goal framework is unique value proposition
4. Visual design is clear and consistent

**What Needs Attention**:

1. **Critical**: Add cohort interaction/notification features (60% request)
2. **Critical**: Implement habit formation reminders (retention risk)
3. **High**: Fix non-clickable UI elements (trust issue)
4. **Medium**: Improve Wheel of Life color contrast (accessibility)

**Strategic Recommendation**:
The prototype demonstrates strong product-market fit with above-average usability. The most critical gap is the lack of notification/interaction features in the cohort space - this represents both the biggest user frustration and the greatest opportunity for differentiation. Addressing this while maintaining privacy-first design would significantly strengthen the product.

---

### 6.6 Changes to Design

**[TO BE COMPLETED AFTER TEAM DISCUSSION]**

Based on the findings above, we need to discuss and decide:

- Which issues will we address in the current iteration?
- Which improvements are feasible within our timeline?
- Which valuable features should be documented as "Future Work"?

#### Implemented Changes

[To be filled after team discussion]

#### Future Work (Deferred Due to Time/Technical Constraints)

[To be filled after team discussion]
