# Health Companion App
## A UX Case Study on Designing for Chronic Health Management

**Author:** Ranjit Singh Dhunna  
**Course:** SOEN 357 User Interface Design, Concordia University  
**Date:** February 2026  
**Tools Used:** Figma, Paper prototyping, Survey forms, Semi-structured interviews

---

> *"I don't want something complicated. I just want to know: Did I take my pills? When is my next appointment? That's it."*
> - Margaret, 68, research participant

---

## Table of Contents

1. [Overview](#overview)
2. [The Problem](#the-problem)
3. [The Solution](#the-solution)
4. [Research](#research)
5. [Personas](#personas)
6. [User Journey Maps](#user-journey-maps)
7. [Storyboards](#storyboards)
8. [User Flow Charts](#user-flow-charts)
9. [Wireframes](#wireframes)
10. [Prototype](#prototype)
11. [Usability Testing Plan](#usability-testing-plan)
12. [Key Design Decisions](#key-design-decisions)
13. [Reflections & Takeaways](#reflections--takeaways)

---

## Overview

| | |
|---|---|
| **Type** | Mobile Health Application (iOS) |
| **Timeline** | January–February 2026 |
| **My Role** | UX Researcher & Designer (solo project) |
| **Research** | 10 interviews + 50 surveys = 60 participants |
| **Deliverable** | Figma clickable prototype (~25–30 screens) |

The **Health Companion App** is a mobile application designed to help individuals with chronic health conditions manage their medications and appointments without the cognitive overload, notification fatigue, or accessibility barriers that plague existing solutions.

---

## The Problem

Millions of people living with chronic conditions manage complicated daily health routines while also maintaining careers, families, and lives. The tools available to them are fundamentally broken:

- 📦 **Pill organizers** don't tell you *if* you already took your medication
- 🔔 **Phone alarms** become background noise after a week
- 📱 **Existing health apps** overwhelm users with notifications until they abandon them
- 📋 **Paper calendars** can't prevent double-booking across multiple specialists

The consequences are real:

> **76% of people with chronic conditions miss medications at least sometimes.**  
> The #1 reason? They forgot.

And appointment management is, in the words of one participant, *"a logistical nightmare"*  especially when coordinating between 3–5 different specialists who don't communicate with each other.

### The Gap

Most health apps make one of two mistakes: they're either too simple (just a glorified alarm) or too complex (overwhelming dashboards full of features nobody asked for). Neither solves the real problems people face every day.

---

## The Solution

The Health Companion App takes a different approach: **adaptive design**.

Rather than building one interface for an imaginary "average user," the app offers three modes:

| Mode | For | Key Design Choices |
|---|---|---|
| 🟢 **Simple** | Tech beginners, seniors | 60pt+ touch targets, 24pt font, voice reminders, one task per screen |
| 🔵 **Standard** | Everyday users | Calendar integration, smart notifications, quick-tap logging |
| ⚫ **Advanced** | Power users | Data visualization, health exports, symptom trend analysis |

**Core features across all modes:**
- ✅ Medication confirmation with timestamps (solves "did I take it?")
- 📅 Smart appointment scheduling with clustering
- 📷 OCR pill bottle scanning for easy onboarding
- 👨‍👩‍👧 Caregiver sharing with granular permissions
- 🌙 "Bad Day Mode" for flare-ups and tough days

---

## Research

### Methodology

I used two complementary research methods to gather both qualitative depth and quantitative scale:

| Method | Participants | Duration | Format |
|---|---|---|---|
| Semi-structured interviews | 10 | 30–45 min | Video calls |
| Online surveys | 50 | 5–7 min | Health forums & patient advocacy groups |

**Total: 60 participants**

Participant breakdown:
- **Ages:** 18–75+ (interviews: 29–73)
- **Gender:** 60% female, 40% male
- **Conditions:** Hypertension (56%), Diabetes (44%), Arthritis (28%), Heart Disease (24%)
- **Tech proficiency:** Expert 20% / Comfortable 36% / Basic 32% / Beginner 12%
- **Medications:** Average of 5–6 per day

---

### What the Interviews Revealed

I conducted a 19-question semi-structured interview covering medication habits, appointment management, technology usage, and health concerns. The conversations were revealing not just for *what* people said, but for the emotion behind it:

> *"I'll stand there staring at the organizer wondering, 'Did I take these already?' It's scary because with my blood pressure medication, you can't double up."*  
> — Margaret Chen, 68

> *"I've tried probably six different medication apps. They all start out great, but then the notifications become overwhelming."*  
> — James Rodriguez, 42

> *"I have to go to an infusion center once a month for my MS medication. It's a three-hour appointment... scheduling it is a logistical nightmare."*  
> — Sarah Patel, 36

> *"On my worst days, I can barely get out of bed. I need something really easy to use even when I'm in brain fog."*  
> — Emily Nguyen, 45

**Top pain points (out of 10 interviews):**

| Pain Point | Reported by |
|---|---|
| Medication adherence | 10/10 |
| Appointment coordination | 9/10 |
| Fragmented systems | 7/10 |
| Accessibility needs | 6/10 |
| Notification fatigue | 3/10 |

---

### What the Survey Revealed

50 survey respondents confirmed and quantified what the interviews suggested:

#### Medication Adherence

```
76% miss medications at least sometimes
76% cite forgetting as the primary reason
64% rely on memory/routine (which fails them)
28% confused about dosage or timing
```

#### Feature Priorities (Top 3 Selections)

| Feature | Selected By |
|---|---|
| Medication reminders | **88%** |
| Appointment reminders | **76%** |
| Medication tracking/history | 56% |
| Doctor communication | 44% |
| Refill reminders | 40% |
| Health data tracking | 32% |

#### Accessibility & Privacy

```
64% — need large text / simple navigation (essential or very important)
56% — have some form of accessibility need
72% — very or extremely concerned about health data privacy
```

---

### 8 Key Research Insights

From the combined 60-participant study, eight core findings guided every design decision:

1. **Medication adherence is multifaceted** — Not just forgetting; confirmation, timing, and identification are all problems.
2. **Notification fatigue is real** — Users abandon apps that over-notify.
3. **One size does NOT fit all** — 44% beginner/basic vs. 20% expert users demand an adaptive interface.
4. **Appointment management is a logistical nightmare** — 40% have 7+ appointments/year.
5. **Healthcare is fragmented** — 8/10 participants see multiple providers who don't communicate.
6. **Accessibility is essential, not optional** — 56% have real accessibility needs.
7. **Trust and privacy are non-negotiable** — 72% very/extremely concerned about data.
8. **Caregiver support is critical** — 32% rely on family members for medication help.

---

## Personas

Two data-driven personas were developed from the research, representing the two most underserved user segments.

---

### Persona 1: Margaret Chen — The Simplicity Seeker

![Margaret Chen Persona](Persona/persona_margaret_chen.png)

| | |
|---|---|
| **Age** | 68 |
| **Occupation** | Retired teacher |
| **Location** | Suburban |
| **Tech proficiency** | Beginner |
| **Conditions** | Type 2 Diabetes, Hypertension |
| **Medications** | 5 daily |
| **Appointments/year** | 6–8 |
| **Lives with** | Alone; daughter visits weekly |

**Goals:** Take medications correctly and on time without confusion.

**Pain Points:**
- Daily "Did I already take this?" anxiety
- Fear of dangerous double-dosing (blood pressure meds)
- Small text on pill bottles is hard to read
- Complex timing rules (with food, before meals, etc.)
- Technology anxiety — struggles with new apps

**What she needs:**
- Large, simple interface (60×60pt minimum touch targets)
- Voice reminders for medications
- Visual confirmation with timestamps
- Medication photos for identification
- Caregiver sharing with her daughter

> *"I don't want something complicated. I just want to know: Did I take my pills? When is my next appointment? That's it."*

**Represents:** ~30% of users — Simplicity Seekers, aged 65–75+

---

### Persona 2: Sarah Patel — The Busy Balancer

![Sarah Patel Persona](Persona/persona_sarah_patel.png)

| | |
|---|---|
| **Age** | 36 |
| **Occupation** | Marketing Manager |
| **Location** | Suburban |
| **Tech proficiency** | Advanced |
| **Conditions** | Multiple Sclerosis, Depression |
| **Medications** | 5 daily + monthly infusion |
| **Appointments/year** | 12+ |
| **Lives with** | Husband + 2 children (ages 7 and 10) |

**Goals:** Efficiently manage complex health needs while maintaining work and family life.

**Pain Points:**
- Complex schedule (5 daily meds + monthly 3-hour infusion)
- Coordinating 4+ specialists who don't talk to each other
- Notification fatigue from existing apps
- Managing side effects and symptom tracking
- Health management feels like a "part-time job"

**What she needs:**
- Smart, calendar-aware notifications
- One-tap medication logging
- Appointment clustering to reduce travel time
- Google Calendar integration
- Data visualization and symptom trends

> *"I'm managing a complex condition while working full-time and raising kids. I need an app that simplifies my life, not complicates it."*

**Represents:** ~40% of users — Busy Balancers, aged 33–58

---

### Persona Comparison

| | Margaret | Sarah |
|---|---|---|
| **Age** | 68 | 36 |
| **Tech Level** | Beginner | Advanced |
| **Interface Mode** | Simple | Standard |
| **Primary Need** | Simple medication reminders | Efficient health management |
| **Key Feature** | Large buttons + voice reminders | Smart notifications + data viz |
| **Main Fear** | "Did I take my medication?" | Running out of time |
| **Success = ?** | Confidence + adherence | Time saved + symptom insights |

The contrast between these two personas created productive creative tension — every design decision had to be tested against both of them.

---

## User Journey Maps

### Margaret's 7-Stage Journey

Margaret's journey begins with **skepticism** and ends with her becoming an **advocate**.

| Stage | Scenario | Emotion | Design Response |
|---|---|---|---|
| 1. Discovery | Daughter notices medication confusion | Skeptical → Curious | N/A |
| 2. Onboarding | Daughter helps set up at kitchen table | Overwhelmed → Relieved | Progressive 3-step onboarding, large text |
| 3. First Use | 7:00 AM — first independent reminder | Nervous → Proud | Voice reminder → pill photo → "I TOOK IT" → green checkmark |
| 4. Week 1 | Twice-daily logging becomes routine | Confident → Proud | Caregiver notifications, positive reinforcement |
| 5. Appointment | 3-day reminder before Dr. Smith visit | Relieved → Prepared | Multi-stage reminders, printable medication list |
| **6. Key Moment** ⭐ | 10:00 AM — "Did I take my pills?" | **Anxious → Relieved** | Opens app: "Morning meds — Taken ✓ at 7:05 AM" |
| 7. Long-term | App is daily companion; she recommends it | Confident → Advocate | 98% adherence, zero missed appointments |

**Margaret's Emotional Arc:**
```
Skeptical → Anxious → Accomplished → Confident → Grateful → Advocate
   😟         😰          🙂            😊           ❤️          🌟
```
<img width="2752" height="1536" alt="Gemini_Generated_Image_qqzsb5qqzsb5qqzs" src="https://github.com/user-attachments/assets/41408713-3331-4171-bbe4-8bfc260fadd7" />


**The killer moment:** Stage 6. Margaret opens the app at 10:00 AM wondering if she took her pills. She gets an instant answer: *"Morning medications, All taken ✓ 7:05 AM."* Her anxiety dissolves in seconds. This single feature: immediate, timestamped confirmation, became the central value proposition for the Simplicity Seeker segment.

---

### Sarah's 7-Stage Journey

Sarah's journey is driven by **efficiency** and discovering that the app can actually **learn her life**.

| Stage | Scenario | Emotion | Design Response |
|---|---|---|---|
| 1. Discovery | Searching "best medication tracking app" during lunch | Frustrated → Analytical | Impressed by integration list |
| 2. Onboarding | Downloads during subway commute | Rushed → Impressed | Google sign-in + OCR = under 10 min setup |
| 3. First Day | Busy workday with back-to-back meetings | Relieved → Hopeful | App delays reminder until meeting ends |
| 4. Week 1 | Discovers data insights before neurologist visit | Surprised → Curious | "My fatigue is worse on days with more meetings" |
| **5. Key Moment** ⭐ | Needs to schedule infusion + neurologist + lab | **Frustrated → Amazed** | App clusters 3 appointments, saves 2 hours travel |
| 6. Bad Day | Severe MS fatigue + brain fog | Anxious → Supported | One tap → simplified interface + husband notified |
| 7. Long-term | Power user, 97% adherence, sends feature feedback | Satisfied → Engaged | "Less time managing health, more time with kids" |

**Sarah's Emotional Arc:**
```
Frustrated → Impressed → Satisfied → Surprised → Delighted → Grateful → Advocate
    😤          😲          🙂          😲          🌟          ❤️          🎯
```
<img width="2752" height="1536" alt="Gemini_Generated_Image_69zect69zect69ze" src="https://github.com/user-attachments/assets/5376ee9d-9601-46fc-b3d7-7e66cc0bdb8e" />


**The killer moment:** Stage 5. Sarah needs to schedule three separate medical appointments while her work calendar is packed. The app analyzes her calendar, finds the optimal day, and clusters all three appointments saving her two hours of travel. This appointment clustering feature became the defining value for the Busy Balancer segment.

---

## Storyboards

### Storyboard 1: Margaret's Morning Medication Routine
![PHOTO-2026-02-21-19-07-45](https://github.com/user-attachments/assets/cc7d2541-a001-4c7a-8c94-87ed751e94ed)


**Features demonstrated:** Voice reminder → visual pill photo → oversized action button → timestamp confirmation

---

### Storyboard 2: Sarah's Appointment Scheduling

<img width="1536" height="2752" alt="Gemini_Generated_Image_u8akoxu8akoxu8ak" src="https://github.com/user-attachments/assets/ed573f75-6e7e-40cb-a0b1-94860390bcc9" />


**Features demonstrated:** Calendar integration → intelligent clustering → time savings visualization → auto-generated preparation checklists


### More
<img width="1536" height="2752" alt="Gemini_Generated_Image_tbjrartbjrartbjr" src="https://github.com/user-attachments/assets/a0556173-241b-4e4f-ae8b-4dafce309a57" />

<img width="1536" height="2752" alt="Gemini_Generated_Image_scfw5oscfw5oscfw" src="https://github.com/user-attachments/assets/0df04642-c308-44fb-b83e-a5479cc5b8f2" />
<img width="1536" height="2752" alt="Gemini_Generated_Image_q1j4ouq1j4ouq1j4" src="https://github.com/user-attachments/assets/a25fb197-d31f-428a-a8c9-261cd852ebb0" />

---

## Wireframes

The design system was built before any screens, ensuring consistency across all three modes.

### Design System

**Typography by Mode**

| Element | Simple Mode | Standard Mode | Advanced Mode |
|---|---|---|---|
| Body text | 18–24pt | 16pt | 14pt |
| Headings | 32pt+ | 24pt | 20pt |
| Minimum | 18pt | 14pt | 12pt |

**Touch Targets**
- Simple Mode: 60×60pt minimum, 80×80pt for primary actions
- Standard Mode: 44×44pt minimum (Apple HIG standard)
- Accessibility: WCAG AA (4.5:1 contrast ratio) throughout

---

### Screen 1 — Welcome & Mode Selection

![Welcome & Mode Selection](wireframes/1frame.png)

Three mode cards are presented at launch with clear plain-language descriptions. A "Need help? Invite a family member" option supports caregiver-assisted setup for users like Margaret.

*Research basis: 73% of participants worried about app complexity on first use.*

---

### Screen 2 — Home Dashboard

![Home Dashboard](wireframes/2frame.png)

The home screen opens with a personalized greeting and puts "Today's Medications" at the very top because that's the question users are asking the moment they open the app. Color-coded status indicators and timestamps eliminate all ambiguity.

*Research basis: Solving the #1 "Did I take it?" question in under 5 seconds.*

---

### Screen 3 — Home Dashboard (Alternate View)

![Home Dashboard Alternate](wireframes/3frame.png)

The Quick Actions 2×2 grid offers fast navigation to My Health, Appointments, Settings, and Help accessible without hunting through menus.

---

### Screen 4 — Medication List

![Medication List](wireframes/4frame.png)

Each medication card shows a photo for visual identification, special instructions (e.g., "Take with food"), and a color-coded status indicator. Filter chips help users browse by All / Daily / As-needed / Weekly.

*Research basis: 6/10 interview participants struggled to identify their medications by name alone.*

---

### Screen 5 — Add Medication (OCR Scan)

![Add Medication](wireframes/5frame.png)

A dual-input system defaults to camera scanning. The OCR reader auto-detects medication name, dosage, and form from the pill bottle eliminating the high-error-rate manual text entry that causes incorrect medication records.

---

### Screen 6 — Medication Reminder

![Medication Reminder](wireframes/6frame.png)

The reminder screen has one dominant action: a full-width green **"I TOOK IT"** button. The medication photo is large and prominent. Secondary options (Snooze 15 min, Skip this dose) are visually de-emphasized to reduce accidental taps. A 30-second undo window catches mistakes.

*Research basis: Single large CTA reduces cognitive load for Margaret; immediate confirmation reduces anxiety.*

---

### Screen 7 — Daily Medication Log

![Daily Medication Log](wireframes/7frame.png)

The log page opens with the instant answer at the top: *"All medications taken ✓"* or a specific count of what's pending. A timeline layout (Morning / Afternoon / Evening) with timestamps makes the full picture clear. Adherence percentage is celebrated positively.

---

### Screen 8 — Appointment List

![Appointment List](wireframes/8frame.png)

Appointment cards include auto-generated preparation checklists (bring insurance card, medication list, notes for doctor). Multi-stage reminders (3 days, 1 day, morning-of) are configured automatically by appointment type.

---

### Screen 9 — Smart Appointment Scheduling

![Appointment Scheduling](wireframes/9frame.png)

The scheduling assistant analyzes the user's work calendar to suggest optimal appointment days. When multiple appointments are needed, it proposes clustering them to save travel time and displays concrete savings: *"💰 Save 2 hrs travel" / "💰 Save $15 parking."*

*Research basis: Sarah's #1 pain point coordination across 4+ specialists.*

---

### Screen 10 — Settings & Accessibility

![Settings & Accessibility](wireframes/10frame.png)

Mode switching, text size with live preview, high contrast and voice command toggles, and caregiver connection management all surfaced clearly without hiding critical features in nested menus.

---

## Prototype

The clickable prototype was built in **Figma** targeting the **iPhone 17 Pro**.
https://www.figma.com/design/NAPWQgbW47pHnod1PSxhqm/Untitled?node-id=0-1&t=RqtKJFwCyFmmnI4S-1

| | |
|---|---|
| **Total screens** | ~25–30 frames |
| **Interactive hotspots** | ~50–70 clickable elements |
| **Transitions** | Smart Animate, Dissolve, Slide |

### Four Complete User Flows

**Flow 1: First-Time Onboarding** (8 screens)  
`Welcome → Mode Selection → Profile → Add Medications (OCR) → Scan Result → Notification Prefs → Success → Home`

**Flow 2: Medication Management** (5 screens)  
`Home → Medication List → Add Medication → Reminder → Logged Confirmation`

**Flow 3: Appointment Scheduling** (7 screens)  
`Appointments → Add Appointment → Smart Date Suggestions → Clustering Proposal → Optimized Schedule → Booking → Success`

**Flow 4: Settings & Accessibility** (3 screens)  
`Settings Menu → Mode Selection → Invite Caregiver`

---

## Usability Testing Plan

### Testing Goals

**Primary:**
1. Verify task completion across all core flows
2. Assess first-time learnability without instruction
3. Validate accessibility for Simple Mode users
4. Identify error-prone interaction points

**Secondary:**
5. Gauge perceived value and adoption intent
6. Understand notification preferences
7. Capture emotional response and satisfaction (NPS)

### Participants

- 5–8 participants per testing round
- Age mix: 30–45 and 60–75+
- At least 2 beginner/basic + 2 intermediate/advanced users
- Mapped to personas: Margaret-like users test Simple Mode; Sarah-like users test Standard Mode

### Task Scenarios

| # | Task | Key Metrics |
|---|---|---|
| 1 | Complete first-time onboarding | Completion rate, time, step drop-offs |
| 2 | Log a medication from a reminder | Time to tap, confidence rating |
| 3 | Answer "Did I take my morning meds?" | Time to answer (target: <5 sec) |
| 4 | Add a new medication via OCR scan | Completion rate, error count |
| 5 | Schedule 3 appointments with clustering | Clustering comprehension, time saved |
| 6 | Invite a caregiver with view-only permission | Discoverability, privacy confidence |

### Success Criteria

| Metric | Target |
|---|---|
| Overall task completion rate | ≥ 85% |
| System Usability Scale (SUS) score | ≥ 70 |
| Average task difficulty (5-pt Likert) | ≤ 2.5 |
| Critical blocking errors | 0 |
| "Did I take it?" confidence | ≥ 4/5 |

---

## Key Design Decisions

Each major design element traces directly back to a specific research finding:

### Decision 1: Adaptive Three-Mode Interface
**Research trigger:** 44% beginner/basic users vs. 20% expert users  
**Problem:** A single interface would compromise the experience for both extremes  
**Solution:** Mode selection at onboarding, switchable at any time in Settings  
**Impact:** Margaret gets a screen with 3 options max; Sarah gets data dashboards

### Decision 2: Timestamped Confirmation System
**Research trigger:** 10/10 interview participants experienced "Did I take it?" anxiety  
**Problem:** No current solution provides undeniable proof of medication taken  
**Solution:** Every logged dose gets a permanent timestamp shown on the home dashboard  
**Impact:** Margaret's core anxiety is resolved within 3 seconds of opening the app

### Decision 3: Smart (Not Dumb) Notifications
**Research trigger:** 3/10 participants had abandoned apps specifically due to notification overload  
**Problem:** Generic alarms get ignored; too many reminders cause abandonment  
**Solution:** Escalating reminders (gentle → persistent), calendar-context awareness, user-set quiet hours  
**Impact:** Notifications feel helpful, not harassing

### Decision 4: Appointment Clustering
**Research trigger:** 9/10 interview participants cited appointment coordination as a major pain point; 40% have 7+ appointments/year  
**Problem:** Scheduling 3–4 specialists requires hours of juggling calendars  
**Solution:** App analyzes work calendar and proposes clustering multiple appointments on the same day  
**Impact:** Sarah's #1 time sink calendar coordination is solved automatically

### Decision 5: "Bad Day Mode"
**Research trigger:** Emily (45): "On my worst days, I can barely get out of bed"  
**Problem:** Illness itself makes managing illness harder  
**Solution:** One-tap mode that strips the interface to essentials + auto-notifies designated caregiver  
**Impact:** Users are supported exactly when they need it most

### Decision 6: Accessibility-First, Not Accessibility-Added
**Research trigger:** 56% have some accessibility need  
**Problem:** Accessibility features feel segregated in most apps ("go to accessibility settings")  
**Solution:** Large touch targets, high contrast, and voice reminders are present across all modes invisible infrastructure that elevates the experience for everyone  
**Impact:** Features designed for Margaret benefit all users under stress, distraction, or low-light conditions

---

## Reflections & Takeaways

### How the Process Worked

The most important insight from this project is that every good design decision was *pulled* out of user research not invented. Before the interviews, the obvious assumption was that users simply "forget" medication and need a reminder. The research revealed something more nuanced:

- There's a **confirmation problem** (Did I take it?)
- There's an **identification problem** (Which pill is this?)
- There's a **timing problem** (With food? Before breakfast?)
- There's a **complexity problem** (The schedule itself is overwhelming)

If I had designed based on the assumption, I would have built a better alarm clock. Instead, I designed a **confirmation system** and that's a completely different product.

---

### Challenges & How I Solved Them

**Challenge 1: Designing for both Margaret and Sarah simultaneously**

The two personas have almost opposite needs. Margaret needs extreme simplicity. Sarah needs powerful efficiency features. There's no single interface that satisfies both.

*Solution:* The adaptive three-mode system. Both Margaret and Sarah get a version of the app that feels made for them because it is.

---

**Challenge 2: Making reminders valuable without being annoying**

The app's core value *is* reminders. But too many reminders is exactly why users abandon apps. This is a genuine design paradox.

*Solution:* Smart escalation only one gentle reminder initially, escalating to persistent only if ignored. Calendar awareness no interruptions during detected meetings. User control full preference configuration during onboarding.

---

**Challenge 3: Keeping the prototype focused**

24 prioritized features and 10+ pain points could easily become a bloated prototype with no coherent experience.

*Solution:* A P0–P3 prioritization matrix. P0 features (must-have for core value) got dedicated screens. P2–P3 features were documented but deferred. The prototype does fewer things but does them excellently.

---

### 5 Takeaways

1. **Research prevents assumption-driven design.** The "Did I take it?" confirmation feature is the heart of this app and it never would have existed without user interviews.

2. **Personas are decision tools, not deliverables.** Every time there was a design conflict, asking "Does this work for Margaret?" and "Does this work for Sarah?" resolved it.

3. **Journey maps reveal what wireframes miss.** The emotional stakes of Margaret's first independent morning use only emerged from journey-level thinking — not screen-level design.

4. **Accessibility benefits everyone.** Features designed for the most constrained user (large touch targets, voice reminders) raise the quality bar for all users.

5. **Scope discipline is a design skill.** Knowing what to leave out is as important as knowing what to include.

---

*Health Companion App — SOEN 357 Final Mini Project, Concordia University*  
*Ranjit Singh Dhunna — February 2026*
