# 7 - Designing and Running Experiments: The Epistemology of Product

## 🎯 Learning Philosophy: First Principles of Experimentation

In this module, we transition from _guessing_ to _knowing_. We treat product development not as a series of features to ship, but as a systematic process of **reducing uncertainty** and **increasing confidence**.

### Core Pillars

1.  **Epistemology of Product:** How do we know what we know? We distinguish between "The Truth" (market reality) and "Our Assumptions" (internal beliefs).
2.  **Capital Allocation:** Every engineering hour is a financial bet. Experiments are our insurance policy against catastrophic waste of the company's most expensive resources.
3.  **Scientific Thinking:** Forming falsifiable hypotheses and seeking evidence that could prove us wrong (falsification), not just right (confirmation).

---

## 🧠 Core Concepts & First Principles

### 1. The MVP (Minimum Viable Product)

An MVP is fundamentally an **experiment designed to reduce the cost of being wrong**. It is the smallest unit of effort required to generate a "surprise"—maximum information learned per dollar/time spent.

- **Information Theory:** An MVP seeks to maximize the "bits" of information gained. If results match expectations, little is learned. If results surprise (failure or unexpected success), information is maximized.
- **Economics (Option Value):** An MVP is a **call option** on the future product. You pay a small "premium" (the cost of the experiment) for the right to decide whether to invest more (persevere) or let the idea expire (pivot/kill).
- **Psychology (Confirmation Bias):** Human brains seek to prove themselves right. A true MVP is designed for **Falsification**—finding the one thing that proves the idea is fundamentally flawed before it's too late.
- **The Tension ("Minimum" vs. "Viable"):**
  - _Minimum:_ The lowest fidelity required to provoke a human reaction (Physics/Resources).
  - _Viable:_ Enough core utility that a user will change behavior or tolerate a "broken" experience to get the result (Value Exchange).
- **MVP vs. V1.0:** V1.0 is the first version of the _solution_. The MVP is the first version of the _learning loop_.

### 2. The "Fail Fast" Strategy

"Fail Fast" is a rigorous strategy for **capital preservation** and **opportunity cost management**.

- **Opportunity Cost:** Every day spent polishing a failing idea is a day _not_ spent on a game-changing one. "Fail Fast" means "Stop Wasting Time Fast."
- **Statistical Power Law:** Most product ideas have zero impact. Success depends on the velocity of iterations—the faster you filter out the 90% of losers, the sooner you find the 10% of "Home Runs."
- **Sunk Cost Fallacy:** The longer we work on something, the harder it is to kill. Failing at week 2 preserves objective rationality; failing at month 6 leads to emotional attachment and "optimization of garbage."
- **Learn Fast:** Failure is only valuable if it provides a clear, actionable signal. If you don't know _why_ you failed, you haven't failed fast; you've just wasted time quickly.

### 3. The Role of the Product Manager

A PM is a **Portfolio Manager of Opportunities** and a **Manager of Uncertainty**.

- **The Gatekeeper:** PMs act as a filter, preventing "trash" (unvalidated ideas) from entering the expensive "factory" of engineering.
- **The Truth-Seeker:** The PM's job is not "to be right," but to **find the truth as fast as possible**.
- **Prediction of Failure:** A core PM competency is identifying the **Single Point of Failure** in an idea before resources are committed.
- **Regret Minimization:** Success is defined by looking back and knowing that no effort was wasted on ideas that were "knowably" wrong from the start.

### 4. Zero-Budget Distribution (How to Reach Customers)

If you must pay for users (Ads), you are masking the signal. Organic discovery is the ultimate validator.

- **The "Hair on Fire" Principle:** Find users in such acute pain that they don't care if the solution is "minimum." They are searching for a bucket of water, not a designer hose.
- **Community Infiltration:** Go to the "watering holes" (Reddit, Discord, niche forums) where the victims of the problem gather. Answer questions and build social capital before mentioning your solution.
- **Direct Outreach (Do things that don't scale):** Spend time instead of money. One deep conversation with a "Power User" provides more signal than 1,000 anonymous ad clicks.

---

## 🛠️ The 7-Step Experimentation Protocol

This is the operational implementation of the "Fail Fast" strategy.

1.  **Identify Your Assumptions:** Create an **Inventory of Ignorance**. List everything that _must_ be true (Demand, Usability, Feasibility, Viability).
2.  **Find the Riskiest Assumption:** Use the **Single Point of Failure** lens. If Assumption A is wrong, the project dies. Attack that one first.
3.  **Define Your Hypothesis:** Use a **Falsifiable Prediction** format: _"If we [Do X], then [Y% of people] will [Action Z]."_
4.  **Minimum Criteria for Success (MCS):** The **Contract with Truth**. Decide _before_ the experiment what "Pass/Fail" looks like to prevent "Moving the Goalposts" later.
5.  **Pick Your MVP Technique:** Choose the cheapest way to generate the required signal (Landing Page, Concierge, Wizard of Oz, Smoke Test).
6.  **Run the Experiment:** Maintain **Statistical Integrity**. Observe the system without meddling or "fixing" it mid-stream.
7.  **Analyze and Learn (Pivot or Persevere):** Use **Bayesian Updating**. Compare data to your MCS. If you failed, celebrate the "Win" of saved resources and pivot or kill the idea.

---

## 💡 Key Misconceptions & Pitfalls

- **Euphemism for V0.1:** Calling a shrunken roadmap an "MVP" ignores the learning objective.
- **The "Polished" MVP:** Established brands often over-build their "minimum," sacrificing learning speed for brand protection.
- **Vanity Metrics:** Measuring "Page Views" instead of "Actions that demonstrate value" (e.g., clicks on a 'Buy' button or email signups).
- **Skipping the MCS:** This is the most common failure mode, allowing confirmation bias to keep dead projects alive.

---

## 🧪 In-Depth: The Hypothesis

**The underlying problem:** Every product decision begins with a gap between what you know and what you need to know to act confidently. If you already knew with certainty that a feature would work, you wouldn't need a hypothesis — you'd just build it.

**What it is:** A formal way of saying: *"I believe X will lead to Y, and here's how I'll know if I'm wrong."* It transforms a vague idea into something **falsifiable** — something that can be proven wrong by evidence.

**First principles — three elements stripped of all methodology:**
1. **A proposed causal mechanism** — "If I do A, then B will happen."
2. **A reason for that belief** — "Because C is true about human behavior, system dynamics, or physics."
3. **An observable signal** — "I will measure D to determine if B happened."

**The null hypothesis (the default):** "Nothing interesting is happening. Any observed effect is due to random chance." Your hypothesis is the alternative — "Something real is happening here." The null is not the pessimistic view; it's the default explanation that requires the least assumption.

**Core question every hypothesis answers:** *"What do I believe is true, and what would convince me I'm wrong?"*

**Psychology involved:**
- **Confirmation bias:** Once we state a belief, we seek evidence to confirm it. A well-formed hypothesis forces you to design for *disconfirmation*.
- **Pattern-seeking:** Humans automatically generate causal stories. The hypothesis forces you to check whether your causal story is correct before acting on it.

**Common misconceptions:**
- ❌ "A hypothesis is a guess." — No. A guess has no reasoning. A hypothesis includes the *mechanism* — why you believe the causal relationship exists.
- ❌ "You need a hypothesis for everything." — No. Many operational decisions don't need explicit hypotheses. Some things are known.
- ❌ "The hypothesis is the feature description." — No. The feature is the intervention. The hypothesis is the predicted causal effect of that intervention.
- ❌ "My hypothesis was wrong, so I failed." — The opposite. If you *learned* that your belief was wrong, the experiment succeeded.

---

## 🎯 In-Depth: Minimum Criteria for Success (MCS)

**The underlying problem:** You form a hypothesis. You run the experiment. You get results. Now what? Without a pre-defined success criteria, three things happen:
1. **Confirmation bias takes over** — you'll interpret ambiguous results as success.
2. **Goalposts move** — you see the data, then decide what threshold makes you comfortable.
3. **"Interesting" is conflated with "decisive"** — a tiny effect might be interesting but not worth the investment.

**What it is:** The **decision rule you commit to in advance**. It answers: *"What would convince me that this is worth pursuing?"*

**First principles — three independent judgments:**

1. **Minimum Detectable Effect (Economic/Strategic)** — The smallest outcome that would justify the investment. Not the smallest you *could measure* — the smallest that actually *matters*. This forces you to ask: "If this feature improves retention by 0.1%, is that worth the engineering cost, maintenance, complexity, and opportunity cost?" The answer depends on context: a zero-cost code change might justify 0.1%; a 3-month engineering effort might need 5%.

2. **Confidence Threshold (Statistical/Decision-Theoretic)** — How sure do you need to be before acting? This is a **risk preference**, not a mathematical universal. The "95% confidence" standard came from agricultural statistics in the 1920s (Ronald Fisher). Your threshold depends on:
   - High cost of false positive → higher confidence needed
   - High cost of false negative → accept lower confidence

3. **Time Horizon (Operational)** — When will you check? Check too early → noise misleads you. Check too late → wasted resources.

**Psychology involved:**
- **Loss aversion:** Losses feel twice as intense as equivalent gains → teams are biased toward inaction when results are ambiguous.
- **Sunk cost fallacy:** Investment creates bias toward positive interpretation. Pre-committing to criteria blocks this.
- **Anchoring:** If you see data before setting the threshold, the data becomes your anchor. Set criteria *before* seeing numbers.
- **Optimism bias:** Teams systematically overestimate the impact of their ideas. Pre-committing forces realism.

**Common failure modes:**
- ❌ **"Anything Is Better Than Nothing"** — Setting criteria at 5% lift, getting 2.3% (not significant), and shipping anyway. The criteria wasn't a suggestion — it was the line between "evidence supports action" and "evidence does not."
- ❌ **Multiple Outcome Trap (p-hacking)** — Measuring 20 metrics and declaring success if any one shows "significance." With 20 metrics, one will likely show significance by random chance.
- ❌ **Moving Target** — Changing the criteria after seeing the data. If the criteria changes after seeing results, it's rationalization, not evaluation.
- ❌ **Impossible Threshold** — Setting criteria so ambitious no experiment could meet it. Fear of failure disguised as rigor.

**Different thresholds for different stages:**
- **Exploration (new product/market):** Low economic threshold, low confidence — looking for directional signals.
- **Validation (have signal, need confirmation):** Moderate threshold, moderate confidence (80-90%).
- **Optimization (improving what exists):** High economic threshold, variable confidence (depends on reversibility).

---

## 💰 In-Depth: Lifetime Value (LTV) & Growth Margins

**The underlying problem of LTV:** How much should you be willing to spend to acquire a customer? Without LTV, acquisition is blind. You don't know whether spending $50 to get a user is smart or suicidal.

**LTV from first principles:** The total net profit you expect from a customer over the entire relationship.
```
LTV = (Average Revenue Per User per Period × Gross Margin) × Average Customer Lifetime
LTV = (ARPU × Gross Margin) / Churn Rate
```

**What LTV really solves:** The **investment sizing problem**. It tells you the upper bound of what you can spend to acquire a customer. If LTV < CAC, growth is destruction — the faster you grow, the faster you go bankrupt.

**Psychology involved:**
- **Temporal discounting:** Acquisition costs are immediate; LTV is in the future. This creates systematic bias toward overspending on acquisition.
- **Survivorship bias:** Calculating LTV using only existing customers ignores churned ones, inflating the estimate.

**Gross margin from first principles:** Not all revenue is equal.
```
Gross Margin = (Revenue - COGS) / Revenue
```
Gross margin tells you whether *unit economics* work before layering on acquisition costs. High margin (80% SaaS) → room to spend on acquisition. Low margin (20% grocery delivery) → must be ruthlessly efficient.

**Growth margins (the advanced concept):** Growth itself has a cost structure. When you grow:
- Marketing costs increase
- Support/onboarding teams need to scale
- Infrastructure costs may increase non-linearly
- Channels degrade — the first channel was best; each additional is worse

Growth margins separate **product economics** from **growth economics**. A business is sustainable only if:
1. Gross margins are positive
2. LTV > CAC
3. Growth margins remain positive as you scale

---

## 🛠️ The 8 MVP Techniques (Lectures 78-80)

**The core problem all techniques solve:** You have an idea. Building the full product would take months and cost millions. You need evidence before you commit. Create the *cheapest possible representation of reality* that lets you observe real user behavior.

**The spectrum:**
```
Most Fake ──────────────────────────────────── Most Real
(Fastest, cheapest)              (Slowest, most expensive)

Email → Shadow → 404/Coming Soon → Explainer → Landing Page → Piecemeal → Concierge → Wizard of Oz
```

The choice is always a trade-off between **speed** and **fidelity** — how fast you can get signal vs. how much you can trust the signal you get.

---

### Technique 1: Email MVP

**What it is:** You send an email to a segment of your audience pitching a new feature/product as if it already exists. Measure clicks, sign-ups, or purchases directly from the email.

**What it tests:** Demand — *When presented with this value proposition, do people take action?*

**First principle:** You don't need a product to test a value proposition. You only need a channel to deliver it and a way to observe response. Email is the lowest-friction channel for most businesses.

**Trade-offs:**
- ✅ Fastest test. No engineering required.
- ✅ Can test multiple value propositions in parallel.
- ❌ Only works if you have an email list.
- ❌ Limited signal. A click ≠ purchase.
- ❌ Risk of damaging trust if users feel deceived.

**Example (AppSumo):** They routinely test new products by emailing their list with an order button. If enough people buy, they acquire or build. If not, they don't. Nothing is ever built until purchase happens.

---

### Technique 2: Shadow Button MVP

**What it is:** You place a button in your existing product that appears to link to a new feature. When clicked, it either does nothing (appears broken) or shows "Coming Soon." Track clicks.

**What it tests:** Demand from existing users — *Do users actively seek this feature within the natural flow of your product?*

**First principle:** Intent expressed in context is more reliable than intent expressed in abstraction. Observing a click in the real product is meaningful; asking "Would you want X?" in a survey is not.

**Trade-offs:**
- ✅ Behavioral data from real usage context. High ecological validity.
- ✅ Can test multiple features simultaneously.
- ❌ Requires an existing product.
- ❌ Risk of frustrating users.
- ❌ Ethical concern: deliberately misleading users.

**Example:** A startup deciding between Facebook, Google, Twitter, and LinkedIn login places all four buttons but only implements one. They measure which unused buttons get clicked to determine priority.

---

### Technique 3: 404 Page / Coming Soon Page

**What it is:** You create a page that looks like a new product/feature page. When users navigate to it, they get a 404 error or "Coming Soon" with an option to sign up.

**What it tests:** Whether existing users navigate to where this feature would live — revealing organic interest without active promotion.

**First principle:** The strongest demand signal is unprompted behavior. If users navigate to a page that doesn't exist, they're telling you what they want without being asked.

**Trade-offs:**
- ✅ Extremely high validity — unprompted user behavior.
- ✅ Low cost (one static page).
- ❌ Only works with existing traffic/users.
- ❌ 404 pages degrade user experience.
- ❌ Coming Soon pages create future expectations.

**Example (Amazon):** Amazon tests new product categories by creating links to them. Clicking gets a "Coming Soon" page with sign-up. They track interest before committing inventory. Oculus Rift used a pre-order page (coming soon + purchase) before they had a working product.

---

### Technique 4: Explainer Video MVP

**What it is:** A video demonstrating a product/feature that doesn't exist yet. Two styles:
- **Tutorial:** Screencast showing someone "using" the feature, created with editing between static mockups.
- **Sales:** Promotional video pitching the product's value.

**What it tests:** Whether the *idea* generates enough interest to drive action (sign-ups, waitlist, shares).

**First principle:** People don't buy products; they buy the *outcomes* products enable. If you can convincingly demonstrate the outcome, you don't need the product to test demand.

**Trade-offs:**
- ✅ Rich communication of complex value propositions.
- ✅ Scalable — one video reaches thousands.
- ❌ Requires production skills/budget.
- ❌ Risk of over-promising — fake video creates expectations the real product can't meet.
- ❌ Views ≠ adoption.

**The Dropbox story:** Drew Houston created a simple screencast showing how Dropbox would work. It wasn't a working product — it was a simulation. The video went viral, driving hundreds of thousands of sign-ups. That demand justified building the real thing.

---

### Technique 5: Fake Landing Page / Pitch Experiment

**What it is:** A dedicated webpage pitching a product/feature with a call to action (sign up, buy, join waitlist). Drive traffic via ads, email, or internal channels. Measure conversion rate.

**What it tests:** Whether the value proposition converts visitors to takers.

**First principle:** Purchase intent is the closest proxy for purchase behavior. If someone fills out a form or enters a credit card on a landing page, they've crossed from "interested" to "committed."

**Trade-offs:**
- ✅ Gold standard for pre-product validation.
- ✅ Can test multiple value propositions with different pages.
- ✅ Can drive real paid traffic — generating actual CAC data.
- ❌ Requires traffic generation (ads, content, SEO).
- ❌ A sign-up ≠ a paying customer.
- ❌ More expensive than email or shadow button.

**Examples:**
- **Buffer:** Created a landing page describing their social media scheduling tool with pricing tiers. People clicked "Plans & Pricing" to see what each tier cost. That behavior told them what to prioritize. They built the product around what people engaged with.
- **Basecamp (37 Signals):** For every new feature or side project, they create a landing page first. They don't build until the page generates sufficient signal.

---

### Technique 6: Piecemeal MVP (Frankenstein MVP)

**What it is:** You assemble existing off-the-shelf tools (WordPress, Typeform, Twilio, Zapier, Stripe) to simulate your intended product without writing custom code.

**What it tests:** Whether the end-to-end *service* works — can you deliver value using cheap, combinable components?

**First principle:** Custom engineering is a tax you pay for scale, not a prerequisite for value delivery. If you can deliver the outcome with manual + off-the-shelf tools, you don't need code to validate.

**Trade-offs:**
- ✅ No custom development required. Non-technical founders can do this.
- ✅ Fast to assemble (days or weeks instead of months).
- ❌ Brittle. The "Frankenstein" breaks easily and doesn't scale.
- ❌ Limited to what existing tools can approximate.
- ❌ Clunky UX may distort user behavior.

**Groupon's origin (The Point):** Before building their sophisticated system, Groupon ran on a WordPress site. Orders came via email. They used Apple Mail and AppleScript to generate PDF coupons automatically. A handful of glued-together tools running a billion-dollar idea.

---

### Technique 7: Concierge Service MVP

**What it is:** You manually deliver the service your product would eventually automate. You do for a small number of users, by hand, what the software would do at scale.

**What it tests:** Whether the service delivers enough value that people want it — before you invest in automating it.

**First principle:** Automation is just manual work done faster. If the manual version doesn't create value, the automated version won't either. You validate the *what* before investing in the *how*.

**Trade-offs:**
- ✅ Maximum learning density. Direct contact with users.
- ✅ No technology risk — the "product" is your labor.
- ✅ You discover nuances and edge cases that surveys never reveal.
- ❌ Not scalable by definition. You're the bottleneck.
- ❌ Labor intensive.
- ❌ Manual experience may be superior to the automated version, creating false positive.

**Rent the Runway:** Before building their online dress rental platform, they ran an in-person concierge on college campuses. They physically brought dresses, helped pick, managed inventory, handled returns, charged manually. The in-person demand validated the concept.

---

### Technique 8: Wizard of Oz MVP

**What it is:** From the user's perspective, the product appears fully functional and automated. Behind the scenes, a human is manually performing the tasks the software would automate.

**What it tests:** Whether the *full experience* (front-end + service) creates enough value to justify building the back-end.

**First principle:** The hardest and most expensive part of most products is the server-side logic. But users only see the front-end. If you can simulate the back-end manually, you can validate the full experience before committing to engineering.

**Trade-offs:**
- ✅ Highest validity — users behave exactly as with a real product.
- ✅ You learn everything: demand, usage patterns, feature preferences, willingness to pay.
- ❌ Labor intensive (but less than concierge for many users).
- ❌ Doesn't scale.
- ❌ If discovered, can damage trust.

**Key distinction from Concierge:** In Concierge, the user knows they're getting personalized service (framed as beta). In Wizard of Oz, the user believes the system is fully automated. Higher fidelity, but also higher deception.

**The Zappos story:** Nick Swinmurn didn't build inventory or logistics. He put up photos of shoes from local stores. When someone ordered, he walked to the store, bought the shoes, and shipped them. From the customer's perspective, Zappos was a fully functioning online shoe store. Behind the scenes: one guy with a car.

---

### The Unifying Pattern Across All 8 Techniques

| Technique | What you build | What you test | The deception |
|---|---|---|---|
| Email | An email | Demand | "This exists" |
| Shadow Button | A button | Interest | "This works" |
| 404/Coming Soon | A page link | Organic demand | "This is coming" |
| Explainer Video | A video | Want | "This works like this" |
| Landing Page | A page | Intent | "This is for sale" |
| Piecemeal | Glued tools | Workflow | "This is our system" |
| Concierge | Your labor | Value | "This is a beta" |
| Wizard of Oz | Front-end | Full experience | "This is automated" |

**The unifying principle:** Every MVP is a lie told to users in order to discover the truth. The lie ranges from small (email) to large (Wizard of Oz). The bigger the lie, the better the signal — but the higher the ethical stakes.

---

### How to Choose

There is no "best" MVP type. There is only the **right MVP for the specific uncertainty you're trying to reduce at this moment.**

- Biggest uncertainty = "Do users even understand the value proposition?" → Email or Landing Page
- Biggest uncertainty = "Will users navigate to this feature?" → Shadow button or 404
- Biggest uncertainty = "Will people pay for this experience?" → Landing Page with purchase or Wizard of Oz
- Biggest uncertainty = "What exactly do users need from this service?" → Concierge

**The first question before any MVP:** *What is the specific assumption I am most uncertain about, and what is the cheapest way to get evidence against it?*

---

## 🛠️ In-Depth Guides for Each MVP Technique

---

### Lecture 81: Email-Based MVPs — Deep Dive

**Best suited for:** Smaller organizations that don't yet have much "brand anxiety." The email MVP is the simplest technique — no engineering required, no developers to bug.

**Pros:**
- Very fast to execute
- Can limit testing to a small but statistically significant group
- Can segment users based on secondary data (usage stats, profile info)
- Cheap, fast, targeted, and damage can be limited
- Anyone can do it

**Cons:**
- Can come off as sloppy or tacky
- Not standard practice to ask people to buy directly from an email
- Risk of denting your brand if tone doesn't match normal marketing

**Best practices:**
1. **Be aware of your audience's expectations.** A luxury brand vs. a bargain outlet have different tolerances. AppSumo gets away with it because their audience expects flash deals and is used to pre-launch products.
2. **Match production value.** Use the same templates, designs, images, and tone as your normal email campaigns. Use tools like Canva for quick image creation.
3. **Pair with another technique.** Email alone is tacky. Combine it with a landing page (link in email) or a concierge service (ask them to respond and run a beta program). Email by itself is weak; email + landing page or concierge is stronger.

---

### Lecture 82: Shadow Buttons — Deep Dive

**What they really are:** Fake buttons placed in an app that track when they're clicked — and that's it. When clicked, they either do nothing (looks broken) or show a message.

**Example (Uncommon Goods):** Clicking "Login with Facebook" on their sales page shows a popup saying "Thank you for voting to add Facebook login."

**Pros:**
- Great data — as close as you can get to proving someone is interested in a new feature
- Easy to implement — a developer can do it over lunch

**Cons:**
- Universally negative user response. Nobody thinks "wow, that was awesome." They think "is this broken?"
- Only tolerable if your product already has a reputation for bugs and users are used to it

**Best practices:**
1. **Acknowledge the click.** Put a message like "Thank you for clicking" to soften the blow. An intentional, acknowledged bug is better than a mystery broken button.
2. **Limit user exposure.** Calculate the minimum statistically significant sample size and expose only that many users. Don't let the test linger.
3. **Assess your users' tolerance.** If your users care about polish, this technique will frustrate them.

---

### Lecture 83: 404 Pages & Coming Soon Pages — Deep Dive

**The key question to choose between them:** *"If I'm a user, would I rather think the page is broken (404) or that the page was misleading (Coming Soon)?"* Choose whichever is "least evil" for your context.

**When each works:**

- **404 pages** — Work best for companies with tons of pages (like Amazon). If users hit a 404, they can jump to another product and keep browsing. Minimal damage. Clothing companies also run variations by listing items as "out of stock" — nobody notices.

- **Coming Soon pages** — Work best for smaller companies where the audience knows they're new and working with early adopters. Early adopters have tough skin — they revel in being cutting edge. A Coming Soon page actually excites them. But for a giant like Walmart, it would look universally tacky.

**Best practices:**
1. **Design it well.** A bland, colorless 404 that looks like your site is broken is terrible. A clever, well-designed 404 page can actually enhance your brand (see resources for examples of great 404 pages). Same for Coming Soon pages — don't use generic templates, proofread, and invest in design. Tools like LaunchRock and KickoffLabs help create seamless Coming Soon pages that look like part of your product.
2. **Shorten the horizon.** Don't let the same user see the same 404 or Coming Soon page repeatedly. Annoyance turns into anger fast. Limit the duration of these tests.

---

### Lecture 84: Explainer Videos — Deep Dive

**Why use videos over text?** Video converts significantly better than text pages. It's why companies everywhere are embedding more video content. Some products are inherently complicated and need in-depth explaining — video can cover more ground in less time than text.

**When to use explainer videos:**

- **You already have video infrastructure.** If your company uses video frequently, you likely have the tools and skills to produce half-decent videos without significant outside recruitment.
- **Your users are used to video.** If users regularly engage with your video content, they're more likely to respond to an explainer video. Use platforms like Wistia or YouTube analytics to track engagement (how much of the video was watched).
- **You're pre-product (entrepreneurial).** If you have no online presence yet, you can be as scrappy as you want. Use cheap tools like Powtoon, GoAnimate, or Fiverr. You haven't set a quality bar yet, so whatever you can afford is fine.

**When NOT to use explainer videos:**
- **Your content rarely uses video.** Throwing an explainer video into a text-heavy site will get it ignored and skew results.
- **Your audience is older.** Older demographics are less likely to engage with video content.

**The key constraint:** Try to be as ordinary as possible relative to your other content. If your users are used to slick, fun videos, don't suddenly create a low-quality screencast with bad voiceover. The difference between expectations and reality will taint their perception of whatever you're pitching.

**Bonus:** Video is more engaging and increases the likelihood of social sharing.

**Trade-off:** High production cost vs. high engagement payoff.

---

### Lecture 85: Piecemeal MVPs — Deep Dive

**How to approach it:** Physically write out what your feature/product needs to do. Then use those functions as search terms in Google, adding "software" or "online" at the end. You'd be amazed at how much you can accomplish with existing software.

**Example (certificate of completion):** Instead of building an auto-PDF generator that detects course completion, add a link at the end of the course to a Typeform. The form submits to a Google Sheet, which triggers Zoho Invoice to create and email a PDF certificate. Three steps, no custom code.

**Best suited for:** Adding functionality that's relatively common. If enough products use a feature (e.g., text message reminders), there's likely an online service that simplifies adding it.

**NOT suited for:** Multiple complex functionalities that need to chain together. Getting off-the-shelf software to cooperate is a pain. Dead ends are common — you'll spend hours trying to find some obscure software that sends information to another obscure software. It becomes a "hairball" quickly.

**Best practices:**
1. **Use orchestration tools.** Zapier and IFTTT (If This, Then That) help you daisy-chain different services together. They make the integration process significantly easier.
2. **Look for white-labeling.** Find software that lets you use your own images, colors, and fonts — or better yet, integrates into your existing product so it looks seamless. Users abandoning the process because they're bounced between different external apps is a real risk with Piecemeal MVPs.
3. **Watch for quality.** Piecemeal MVPs can look amateurish. People can tell when you're just sticking services together. White-labeling helps with this.

---

### Lecture 86: Concierge Service MVPs — Deep Dive

**Key distinction from Wizard of Oz:**
1. You don't build anything — just a way to connect users to you
2. You're **upfront** about not having the feature yet

**The hybrid nature:** A concierge service sits between customer development (qualitative interviews) and MVP testing (quantitative behavior). You observe whether users engage meaningfully, AND you get to ask "why" and understand their internal reasoning.

**Advantages:**
- Can run almost in secret — just email a batch of users and manage relationships directly
- No fake buttons, no fake pages needed
- Rich learning — you see behavior AND hear reasoning

**Disadvantages:**
- Management intensive and time-absorbing
- You'll likely need to run it yourself (you know what questions to ask), creating logistical problems with your other responsibilities
- Burns a lot of resources per user
- Rarely profitable in itself (unless you're selling luxury items where high-touch is justified)

**Example (Uber wheelchair-accessible cars):** Pick a city, email a handful of users about a beta program for handicap-accessible cars. Users who sign up get a phone number to text when they need a pickup. One person drives the car, you operate the text messages. No development needed. Track usage frequency and talk to riders during the drive.

**When to use:**
- Smaller organizations (sweet spot)
- When you have the time to be 100% committed
- When small data sets are sufficient (you won't get big samples)

**When to avoid:**
- You're too in demand to be fully committed
- You need large data sets to justify your decision
- The cost-per-user is too high relative to what you're testing

---

### Lecture 87: How Big Companies Think About MVP Experiments

**The risk calculus shifts with size:**

| | Startup | Big Company |
|---|---|---|
| Main risk | Running out of resources | Brand damage |
| Resource concern | Existential — failure = death | Tolerable — can weather failed products |
| Brand concern | Minimal — brand means nothing if you're dead | Paramount — brand is an accumulated asset |

**The spectrum of techniques by brand risk:**
```
Low Resource / High Brand Risk ─────────── High Resource / Low Brand Risk
Email MVP → Shadow Button → 404/Coming Soon → Explainer → Landing Page → Piecemeal → Concierge → Wizard of Oz
```

- **Email MVP** — Easiest on resources, most reckless with brand
- **Wizard of Oz** — Most resource intensive (build front-end), most protective of brand (looks like a real product)

**When companies get large enough:** They move beyond these "tricks." At a certain size, PMs are expected to build what most people *incorrectly* assume an MVP is — a really basic version of the product. They can't rely on "parlor tricks" anymore. They actually have to build something real, just minimal.

**The "One Feature" MVP (not covered in earlier lectures):**
1. List every function/feature in your product
2. Rank them by value to the user
3. Build ONLY the #1 most valuable function
4. Test reception before adding more

**Example (Foursquare):** Foursquare's MVP was literally just the check-in function. Connect social networks, check in, and it sends a notification to friends. No photos, no hashtags, no badges, no prizes. Those were secondary in value to the core check-in mechanism. They tested whether people wanted to check in before building anything else.

**Your job as a PM:** Gauge your company's tolerance for risk. Do they care more about resources or brand? Then find the technique that optimizes resource expenditure against the information you need.

---

### Lecture 88: Evaluating Results & Learning from Them

**The flashlight analogy:** Running MVP experiments is your flashlight in the dark. Coming up with an idea, designing an experiment, setting expectations, and running a test is how PMs decide what to build.

**The decision framework:**
1. Compare your data to your **Minimum Criteria for Success (MCS)**
2. If it passes → congratulations, green light
3. If it doesn't → investigate why it didn't work
4. Then decide: Go, Kill, or Rerun

**Quantitative vs. Qualitative data — why you need both:**

- **Quantitative** (numbers): What happened? Percentages, time spent, signups, behavior. Unbiased records of what users did or did not do.
- **Qualitative** (interviews/conversations): Why did it happen? Verbal, feelings, motivations, context.

**Critical lesson:** The "what" without the "why" can be incredibly misleading.

**The marathon shoe example:**
- Landing page experiment → 14% of visitors signed up to be notified, some pre-ordered → Green light given
- After building the shoe and running a real campaign → Only 1% bought
- What happened? The 14% who signed up weren't marathon runners at all — they were casual runners who liked the shoe design. The quantitative data looked great but the *wrong audience* was responding. Qualitative interviews would have caught this.

**How to get qualitative data:**
- Have regular conversations with users involved in your test
- Incentivize them to talk on the phone
- Install live chat boxes

**Discovery during experiments:** You'll find surprising things:
- Your feature might be popular, but not with the audience you expected
- User behavior might not change your ideal metric, but it changes an entirely different metric

All of this is gold — you're finding the truth about customer needs and preferences.

**The three decisions at the end:**
1. **Go** — Green light the feature (it passed the MCS)
2. **Kill** — Scrap the idea entirely
3. **Rerun** — Test again with a slightly different hypothesis (you learned something but need more signal)

---

## ✅ Section 7 Complete

This concludes the Designing and Running Experiments section. You now understand the full cycle:

1. **Identify assumptions** — What must be true for this idea to work?
2. **Find the riskiest assumption** — Which one kills the project if wrong?
3. **Form a hypothesis** — What do you believe, and what would convince you you're wrong?
4. **Set minimum criteria for success** — The contract with truth, set before seeing data
5. **Pick an MVP technique** — Email, Shadow Button, 404, Coming Soon, Explainer Video, Landing Page, Piecemeal, Concierge, Wizard of Oz, or One-Feature MVP
6. **Run the experiment** — Observe behavior without meddling
7. **Evaluate and learn** — Compare to MCS, gather both quantitative AND qualitative data, decide: Go, Kill, or Rerun

The core principle that ties it all together: **Product development is a continuous process of reducing uncertainty and increasing confidence.** Every experiment is a bet against your own ignorance. The goal is not to be right — the goal is to find the truth as fast as possible, with the least resources possible, while preserving the trust of your users.
