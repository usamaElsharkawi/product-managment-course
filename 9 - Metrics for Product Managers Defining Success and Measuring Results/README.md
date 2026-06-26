# 9 — Metrics for Product Managers: Defining Success and Measuring Results

> **Core Principle:** *"Metrics are not goals. They are measurements that tell you whether you're moving toward your goals. The most dangerous mistake is confusing the metric with the outcome."*

---

## What Is a Metric?

**A metric is a signal that reduces uncertainty about whether you're creating value.**

Every metric exists because you have a question you can't answer by intuition alone:
- *"Are more people using the product than last month?"* → MAU
- *"Are users getting value before they churn?"* → Activation rate
- *"Is the product actually solving their problem?"* → Task completion rate

The metric doesn't *define* success. It *indicates* whether you're moving toward it.

---

## Why Metrics Matter (The Problem They Solve)

### 1. Your Brain Lies to You
Humans suffer from systematic biases — confirmation bias, recency bias, overconfidence, illusion of control. Metrics are a **corrective lens** that gives you an observation independent of your biases.

### 2. Feedback Loops Drive Behavior
The radar speed sign principle: **instant feedback changes behavior more effectively than delayed consequences.** Short feedback loops → fast learning. Long feedback loops → slow learning, high risk. The job of a product manager is to shorten feedback loops.

### 3. Human Nature Follows the Signal
Humans are **feedback-seeking prediction machines**. Dopamine is released not by reward, but by the *gap between prediction and outcome* — a prediction error. Your brain will prioritize whatever gives the clearest, fastest signal, regardless of whether that signal represents the outcome you care about.

**The principle:** *"What gets measured gets attention. Where attention goes, resources flow. Where resources flow, change happens. Whether that change is good or bad depends on whether you measured the right thing."*

### 4. Without Measurement, You Can't Distinguish Progress from Activity
Activity is *what you do*. Progress is *the change in the metric that matters*. If you're not tracking that metric, you can't tell the difference.

### 5. Define Success Before You Build
If you can't define what success looks like before you start, you don't understand the problem well enough to build the solution.



---

## The Causal Chain: How Metrics Relate to Each Other

Every team-level metric is a **causal hypothesis** about a higher-level outcome:

```
Feature change → Comments/person ↑ → Time spent ↑ → Company goal achieved
```

The chain must be articulated. If you don't understand why X causes Y, you can't trust that improving X will improve Y.

### Correlation vs. Causation (Ice Cream & Drowning)
Ice cream sales and drowning deaths both rise in summer. They correlate perfectly. But banning ice cream won't stop drowning — a third factor (heat) drives both. Metrics should be based on a plausible causal mechanism, not a coincidental correlation.

---

## Real Company Examples

### Twitter
| Category | Metrics |
|----------|---------|
| Growth | New users/month, MAU, DAU, Activated users |
| Engagement | Logins/day, Time spent, Tweets/user, Avg likes, Avg retweets, Avg follows, DMs |
| **Core strategic metric** | **DAU/MAU (Stickiness)** — is Twitter a daily habit or a monthly visit? |

### YouTube
| Category | Metrics |
|----------|---------|
| Growth | MAU, New users, Activated users |
| Engagement | Views over 30 seconds, Watch time, Subscriptions/user, Uploads/creator |
| **Core strategic metric** | **Watch time** — YouTube famously switched from views to watch time to prevent clickbait gaming |

### Facebook
| Category | Metrics |
|----------|---------|
| Growth | MAU, New users, Activated users |
| Engagement | Likes/day, Likes/post, Comments, Newsfeed position engagement |
| **Core strategic metric** | **Time spent** — later added "meaningful social interactions" because pure time optimization led to toxic content |

### The Key Insight
> *"Growth metrics are generic across companies. Engagement metrics are specific to what the platform is trying to get you to do."*


---

## The Five Categories of Metrics (Customer Lifecycle)

The purpose of these categories is to ensure you cover the **full customer lifecycle** — not just the part that's easiest to measure.

### 1. Growth & Activation
- **Growth:** Are people finding us? (New users, traffic sources)
- **Activation:** Did the user experience core value for the first time? (The "aha moment")

**The trap:** Growth without activation is an expensive leaky bucket. You pour water in, it drains out.

**The principle:** *Growth brings people in. Activation makes them stay. Without activation, growth is just expensive churn.*

### 2. Engagement
Are users coming back and using the product deeply?

Engagement metrics are **specific to your product** — they should measure the behavior that correlates with long-term retention:
- Twitter: Tweets, likes, retweets
- YouTube: Watch time, views over 30 seconds
- Spotify: Minutes listened, playlists created
- Uber: Rides per week

**The principle:** *Not all engagement is equal. The threshold should correspond to value delivery (YouTube's 30-second view is a deliberate choice).*

---

### 4. User Happiness & NPS
How do users *feel* about the product?

#### Why Happiness Is Hard to Measure
Behavioral metrics (clicks, logins) are *observed* — users generate them automatically. Attitudinal metrics (happiness, satisfaction) must be *reported* — users have to consciously tell you something. Problems include: selection bias, social desirability bias, recency bias, survey fatigue, and the action gap (users say they're satisfied but still churn).

#### What Is NPS (Net Promoter Score)?
Developed by Fred Reichheld at Bain & Company (2003).

One question: *"How likely are you to recommend our product to a friend? (0-10)"*

| Classification | Score | Meaning |
|---------------|-------|---------|
| Promoters | 9-10 | Loyal enthusiasts who will refer others |
| Passives | 7-8 | Satisfied but vulnerable to competitors |
| Detractors | 0-6 | Unhappy, can damage brand through negative word-of-mouth |

**Formula:** NPS = % Promoters - % Detractors (range: -100 to +100)

**Why it's popular:** Simple, standardized, comparable across companies.

**Criticism:** Intent ≠ behavior. Lagging indicator. Doesn't tell you *why*. Cultural bias in scoring. Modest correlation with actual referral behavior.

**Better approach:** Triangulate happiness through multiple signals — NPS, support volume, churn reasons, organic referrals, social media sentiment, feature-specific satisfaction surveys.

### 5. Revenue
Does the product generate sustainable financial value?

#### Key Revenue Metrics
| Metric | What It Tells You |
|--------|-------------------|
| MRR / ARR | Predictable recurring revenue base |
| ARPU | How much each user is worth |
| LTV | User value over their entire relationship |
| CAC | Cost to acquire a user |
| LTV:CAC ratio | Unit economics sustainability (target ≥ 3:1) |
| Churn rate | % of users who stop paying |
| Net Revenue Retention (NRR) | Revenue changes from existing customers (upgrades, downgrades, churn) |

**The hierarchy:** *User happiness → Engagement → Retention → Revenue.* You can't skip steps.

**The principle:** *Revenue is an outcome metric, not a driver metric. You can't optimize revenue directly — you can only optimize the behaviors that lead to it.*

### 3. Retention
Do users come back over time?

**Measured via cohort analysis:**
```
Cohort: Users who joined January 1-7
    Week 1: 100%
    Week 2: 40%
    Week 4: 25%
    Week 8: 18%
    Week 12: 15% → **The flattening point** (most important number)
```

**Why retention matters more than growth:** Retention compounds. A product with 20,000 signups/month at 40% retention ends up with more long-term users than one with 100,000 signups/month at 5% retention.

**The principle:** *If you fix retention first, growth becomes leverage. If you grow before fixing retention, you're accelerating failure.*


---

## How to Pick Good Metrics

### The Instructor's Four Criteria
1. **Easily understandable** — People should know what it means in one sentence
2. **Avoid spurious correlation** — Ensure plausible causal link, not coincidental movement
3. **Ratio or rate over absolute number** — Ratios control for scale changes; absolute numbers go up for unrelated reasons (marketing, press coverage)
4. **Able to be affected** — Your team should have agency to move it through product decisions

### Deeper Principles

**Leading vs. Lagging:** Leading indicators predict the future (activation rate, engagement depth). Lagging indicators confirm the past (revenue, churn). You need both.

**Hard to Game:** If a metric can go up without the product improving, it's a bad metric.

**Counter-Metrics:** Every metric has a shadow. If you optimize for speed, track bugs. If you optimize for conversion, track returns. The counter-metric is your early warning system.

**Stable Definition:** A metric must be comparable over time. If you change its definition, you lose trend visibility.

### Exploratory vs. Reporting Metrics
- **Reporting metrics** — Headline numbers you show executives and investors (MAU, revenue, NPS). Change slowly. Represent overall health.
- **Exploratory metrics** — Debugging numbers you track privately (funnel drop-off, feature adoption, error rates). Change quickly. Represent levers you can pull.

**The principle:** *You manage with exploratory metrics. You communicate with reporting metrics. If you only track reporting metrics, you'll see problems too late to fix them.*

### The One Question
> *"If this metric goes up, does the product actually get better for users?"*

---

## The HEART Framework (Kerry Rodden, Google)

### What Problem It Solves
Before HEART, teams tracked whatever was easiest to instrument (clicks, page views) — behavioral metrics only. They optimized for activity, not value. HEART forces you to consider **five distinct dimensions of user experience**, capturing both behavioral and attitudinal signals.

### The Five Dimensions

| Letter | Dimension | Question It Answers | Risk It Surfaces |
|--------|-----------|---------------------|------------------|
| H | Happiness | How do users *feel*? | Users might dislike the product even if they use it |
| E | Engagement | How *deeply* do they use it? | Users might not use it enough to get lasting value |
| A | Adoption | Do new users reach value? | New users might never experience core value |
| R | Retention | Do they come back? | Users might try once and never return |
| T | Task Success | Can they *get things done*? | Users might be unable to complete their goal |

### The Three-Column Structure

For each dimension, you fill three columns:

| Column | Description | Example (Uber for Spiked Lemonade) |
|--------|-------------|-----------------------------------|
| **Goals** | What do we want? | "Maximize drinker satisfaction" |
| **Signals** | What data would tell us? | App store rating, NPS |
| **Metrics** | How do we quantify it? | Average rating, NPS score |

**The principle:** *Goals without signals are wishes. Signals without metrics are anecdotes. All three are necessary.*

### Why the Signals Column Is an Engineering Spec
Once you've defined your signals, you can hand that column to engineers as a specification for what data needs to be instrumented in the database. It bridges the gap between product goals and technical implementation.

### Limitation
HEART is user-centric but not business-centric. It omits revenue and growth dynamics. Best paired with AARRR or other business-focused frameworks.


---

## AARRR Pirate Metrics (Dave McClure, 500 Startups)

### What Problem It Solves
HEART is comprehensive but heavy — it captures user sentiment (happiness, task success) which is valuable but costly to measure. AARRR strips away attitudinal dimensions and focuses purely on **behavioral funnel optimization**. It answers one question: *"Are we moving users from awareness to revenue efficiently?"*

Origin: Dave McClure, a VC at 500 Startups, created it as a standardized framework to evaluate companies for investment.

### The Five Stages

Each stage feeds the next. The funnel is only as strong as its weakest stage.

| Stage | What It Measures | Example Metric |
|-------|------------------|---------------|
| **A** Acquisition | User arrives — visits website, downloads app | Traffic, app installs, signups |
| **A** Activation | User experiences core value for the first time | Completed onboarding, first key action |
| **R** Retention | User comes back repeatedly | DAU/MAU, cohort retention rate |
| **R** Referral | User tells others about the product | Viral coefficient, invites sent |
| **R** Revenue | User pays money | MRR, ARPU, conversion to paid |

### Key Insight: Referral Is the Hidden Gem
Most frameworks stop at retention. AARRR adds Referral because viral growth compounds without paid acquisition. If your product naturally compels users to invite others, growth becomes exponential rather than linear.

### How It Differs from HEART

| Dimension | HEART | AARRR |
|-----------|-------|-------|
| Origin | Google UX researcher | Silicon Valley VC |
| Best for | Mature products optimizing UX | Early-stage startups seeking growth |
| Captures | Behavior + Attitude | Behavior only |
| Includes happiness? | Yes (H) | No |
| Includes referral? | No | Yes |
| Output | Diagnostic (find problems) | Growth-oriented (optimize funnel) |

**The principle:** *Find the stage with the biggest drop-off and fix that first. Don't optimize the whole funnel — optimize the weakest link.*

---

## Tracking Your Metrics in Practice

### What Problem It Solves
Knowing *what* to measure is useless if you can't *actually measure* it. This lecture bridges the gap between metrics theory and instrumentation reality.

### The Tool Landscape (Course Era)

| Tool | Purpose |
|------|---------|
| Google Analytics | General web analytics, traffic, page views |
| Crazy Egg | Heatmaps, click tracking, scroll depth |
| KISSmetrics | Custom metrics, user behavior tracking |
| Optimizely | A/B testing with click tracking |
| Segment | Data hub — decouples data collection from analysis |

### The Key Insight: Data Infrastructure Is Strategic
The instructor's emphasis on Segment reveals an important architectural principle — **data infrastructure is a strategic asset, not a tactical choice.**

If you hard-code Google Analytics tracking into your app, switching to Mixpanel means rewriting code and losing history. If you use a hub (Segment), you instrument once and plug/unplug analytics tools without consequence. You preserve optionality.

**The principle:** *Design your data architecture for flexibility. You will change tools as your needs evolve.*

### Modern Tools (2024-2026)

| Course Tool | Modern Alternative | Why |
|-------------|-------------------|-----|
| Google Analytics | GA4 / Amplitude / Mixpanel | Amplitude/Mixpanel are purpose-built for product analytics (events, cohorts, funnels) |
| Crazy Egg | Hotjar / FullStory / Microsoft Clarity | Clarity is free; FullStory adds session replays with dev logs |
| KISSmetrics | Amplitude / Mixpanel | Event-based product analytics with better UX |
| Optimizely | LaunchDarkly / GrowthBook | Feature flags + experimentation; GrowthBook is open-source |
| Segment | Twilio Segment / RudderStack | Segment is now paid; RudderStack is the open-source alternative |

**The timeless principle:** *Choose tools that minimize the friction between having a question and getting an answer. The best tool is the one your team will actually use — not the one with the most features.*