# Business Idea Discovery Phase

A structured framework for validating a business idea before committing resources. This document was produced by a six-member advisory team, each contributing their domain expertise.

**Advisory Team:**
1. Product Strategist -- Problem definition and opportunity framing
2. Market Researcher -- Market sizing, trends, and industry analysis
3. Customer Development Expert -- Personas, interviews, and validation signals
4. Competitive Analyst -- Landscape mapping, differentiation, and positioning
5. Business Model Designer -- Revenue models, unit economics, and pricing
6. Risk & Feasibility Advisor -- Assumptions, experiments, and kill criteria

---

## 1. Product Strategy: Problem Discovery & Opportunity Framing

### Problem Definition Framework

A well-defined problem is the foundation of any viable product. Use the **PUFS framework** to articulate it with precision:

- **Person** -- Who specifically has this problem? Define the target persona by role, context, and constraints. "Small business owners managing 1-10 employees without a dedicated HR function" is actionable; "businesses" is not.
- **Urgency** -- How painful is the problem today? Rate severity on a scale: (1) mild inconvenience, (2) recurring frustration, (3) significant time/money loss, (4) existential threat to their workflow or business.
- **Frequency** -- How often does the problem occur? Daily problems build habits; annual problems require heavy marketing to stay top-of-mind.
- **Status Quo** -- What do they do today instead? The current workaround reveals both the pain threshold and the baseline you must beat.

**Key questions to ask during discovery interviews:**

1. "Walk me through the last time you dealt with [problem]. What happened step by step?"
2. "What did that cost you in time, money, or stress?"
3. "How often does this come up -- daily, weekly, monthly?"
4. "What have you tried to solve it, and why did those solutions fall short?"

### Jobs-to-Be-Done Analysis

Customers do not buy products -- they hire them to make progress in a specific situation. Map the job across three dimensions:

| Dimension | Core Question | Example |
|-----------|--------------|---------|
| **Functional** | What task needs to get done? | "Generate a compliant invoice in under 2 minutes" |
| **Emotional** | How does the person want to feel? | "Confident I won't make an embarrassing mistake" |
| **Social** | How does the person want to be perceived? | "Seen as organized and professional by my clients" |

Write your job statement using this template: **"When I [situation], I want to [motivation], so I can [desired outcome]."**

Identify competing "hires" -- spreadsheets, manual processes, a competing tool, or simply ignoring the problem -- to understand the real competitive landscape.

### Problem Validation Checklist

Before committing resources, confirm the problem passes these gates:

- [ ] **Expressed demand** -- At least 10 target users have described this problem unprompted in interviews, forums, or support tickets.
- [ ] **Willingness to pay** -- At least 5 prospects answer "yes" to: "If a solution existed today, would you pay for it?" Follow up with price anchoring.
- [ ] **Failed alternatives** -- Users can name workarounds they have tried and explain why those workarounds are insufficient.
- [ ] **Quantifiable impact** -- You can attach a number to the pain: hours wasted per week, revenue lost per quarter, error rate percentage.
- [ ] **Accessible market** -- You have a realistic channel to reach these users (community, marketplace, content, sales motion).
- [ ] **Timing rationale** -- You can articulate why this problem is solvable or newly urgent *now* (regulatory change, technology shift, market trend).

A problem that clears all six gates is worth building for. Four or fewer signals a need for deeper research or a pivot in framing.

### Vision & Opportunity Framing

Once validated, frame the opportunity in a single narrative arc that connects problem to impact:

> **"[Target users] struggle with [specific problem] every [frequency]. Today they rely on [status quo], which costs them [quantified pain]. We will deliver [core value proposition] by [mechanism/approach], unlocking [measurable outcome] for an addressable market of [size]."**

Pair this narrative with a **before-and-after table** to make the value concrete:

| Metric | Before (Status Quo) | After (With Product) |
|--------|---------------------|----------------------|
| Time per task | e.g., 45 min | e.g., 5 min |
| Error rate | e.g., 12% | e.g., < 1% |
| User sentiment | Frustrated | Confident |

This framing serves double duty: it aligns the internal team around a shared mission and provides the skeleton for investor, stakeholder, and go-to-market messaging later.

---

## 2. Market Research & Sizing

Market research during discovery answers a single critical question: **is this opportunity large enough and well-timed enough to pursue?** The following frameworks turn that question into quantifiable analysis.

### Market Sizing (TAM / SAM / SOM)

Use both top-down and bottom-up approaches, then triangulate. If the two methods diverge by more than 3x, your assumptions need scrutiny.

**Top-Down (start from the whole, narrow down):**
Begin with a known industry figure and apply filters. Example: the global CRM market is $80B. If you are building a CRM exclusively for independent insurance agents in the US, filter by geography (~40% = $32B), then by segment share (~2% of CRM users are independent agents = $640M). That $640M is your TAM.

**Bottom-Up (start from the unit, scale up):**
Count the buyers and multiply by what they would pay. Example: there are roughly 400,000 independent insurance agencies in the US. If your tool costs $150/month, the bottom-up TAM is 400,000 x $1,800/year = $720M. Close agreement with the top-down figure builds confidence.

**Defining SAM and SOM:**
- **SAM (Serviceable Addressable Market):** The slice you can actually reach with your current product scope and go-to-market. If you only support P&C insurance workflows at launch, and 55% of agencies do P&C, SAM = $720M x 0.55 = ~$396M.
- **SOM (Serviceable Obtainable Market):** A realistic 3-year capture target. New entrants in vertical SaaS typically capture 1-5% of SAM within 3 years. Conservative SOM = $396M x 0.02 = ~$8M ARR.

Present all three numbers with explicit assumptions. Investors and stakeholders discount sizing that lacks traceable logic.

### Market Trends & Timing

Timing determines whether a good idea becomes a viable business. Investigate three layers:

- **Macro shifts:** Demographic changes, remote work adoption, interest rate environments. Use FRED (Federal Reserve Economic Data), World Bank Open Data, and Bureau of Labor Statistics for free, authoritative datasets.
- **Technology inflections:** New capabilities that remove previous blockers (e.g., LLMs enabling natural-language interfaces, or API-first banking enabling fintech). Track these through Gartner Hype Cycles, CB Insights research, and Hacker News sentiment.
- **Regulatory changes:** New compliance requirements often create forced buying events. Monitor Federal Register updates, industry association bulletins, and legislative tracking tools like Congress.gov.

The strongest opportunities sit at the intersection of at least two of these forces. Document the specific trigger events and their timelines.

### Industry Analysis (Porter's Five Forces)

Apply Porter's framework to stress-test the competitive environment:

| Force | Key Discovery Questions |
|---|---|
| **Rivalry** | How many direct competitors exist? Are they well-funded? Is the market growing fast enough to absorb new entrants? |
| **Buyer Power** | Are customers concentrated or fragmented? What are switching costs? Do they have alternatives? |
| **Supplier Power** | Do you depend on a single platform, API, or data provider that could raise prices or cut access? |
| **Threat of Substitutes** | Could buyers solve this with spreadsheets, manual processes, or a different product category entirely? |
| **Barriers to Entry** | What moats exist (data, network effects, regulatory licenses)? How quickly could a well-funded competitor replicate your offering? |

Score each force as low, medium, or high. Markets with high rivalry, high buyer power, and low barriers are structurally difficult regardless of product quality.

### Data Sources & Research Methods

**Free sources:** US Census Bureau, BLS, FRED, SEC EDGAR filings (competitor revenue), Crunchbase (funding data), Google Trends (demand signals), Statista (limited free tier), and SBA industry profiles.

**Paid sources:** IBISWorld, PitchBook, Gartner, Forrester, and CB Insights offer deeper segmentation. Many are accessible through public library systems with a library card.

**Primary research:** Conduct 10-15 customer discovery interviews within the target segment. Ask about current spending, pain severity (1-10), and willingness to switch. These conversations validate or invalidate your sizing assumptions faster than any report.

**Triangulation rule:** Never rely on a single source. Cross-reference at least three independent data points for any critical number. When sources conflict, document the range and state your chosen assumption with reasoning.

---

## 3. Customer Development

Customer development is the discipline of systematically testing assumptions about who your customer is, what problems they face, and whether those problems are worth solving. Every assertion in this section should be grounded in direct evidence from real conversations, not internal brainstorming.

### Customer Persona Development

Effective personas are built from observed patterns, not imagination. Start with a blank canvas and fill it in only as interview data accumulates. Each persona should capture:

- **Demographics**: Role/title, company size, industry, decision-making authority, budget ownership.
- **Psychographics**: What motivates them professionally? What do they fear? What does success look like in their role?
- **Behaviors**: What tools do they currently use? How often do they encounter the problem? What is their current workflow?
- **Pain Points**: Specific frustrations stated in their own words. Rank by frequency across interviews and by intensity (mild annoyance vs. blocking their goals).

Start broad. After 8-12 interviews, convergent patterns will reveal natural persona clusters. Resist the urge to define personas before you have the data.

### Discovery Interview Design

The goal of a discovery interview is to learn about the customer's life, not to pitch your idea. Follow these principles:

1. **Talk about their life, not your idea.** Ask about past behavior, not hypothetical futures.
2. **Ask for specifics.** "Tell me about the last time..." is far more reliable than "Do you usually...?"
3. **Never lead.** Replace "Wouldn't it be great if..." with "How do you handle that today?"
4. **Listen for emotion.** Real pain shows up as frustration, wasted money, or repeated failed attempts.
5. **Seek disconfirming evidence.** Actively probe for reasons your assumption might be wrong.

Keep interviews to 20-30 minutes. Take notes verbatim when possible, capturing exact phrases.

### Sample Interview Script

Use this template for initial problem discovery conversations:

1. "Tell me about your role and what a typical week looks like."
2. "What is the hardest part of [problem domain] for you right now?"
3. "Walk me through the last time you dealt with [specific problem]. What happened?"
4. "How are you solving that problem today? What tools or workarounds do you use?"
5. "What do you dislike most about your current approach?"
6. "How much time or money does this problem cost you per week/month?"
7. "Have you looked for a better solution? What did you try, and why did it fall short?"
8. "If this problem disappeared overnight, what would change for you?"
9. "Is there anything else about [problem domain] that I should have asked about but didn't?"
10. "Who else on your team or in your network deals with this problem? Would you be open to introducing me?"

### Synthesis and Pattern Recognition

After every five interviews, pause and synthesize. Use this process:

1. **Extract quotes.** Pull direct customer statements into a shared document, one per row.
2. **Tag themes.** Label each quote with a category (e.g., "time waste," "tool switching," "compliance fear").
3. **Count frequency.** Track how many distinct interviewees raised each theme independently.
4. **Rank severity.** Separate "nice to fix" complaints from "I would pay to solve this today" statements.
5. **Map to personas.** Check whether themes cluster by role, company size, or industry.

A theme mentioned by 5+ out of 10 interviewees with strong emotional language is a reliable signal. A theme mentioned once is an anecdote, not a pattern.

### Validation Signals

Not every stated problem represents a real market opportunity. Look for these concrete signals to distinguish genuine need from polite agreement:

- **Spending signal**: The customer is already paying for a partial or inferior solution.
- **Workaround signal**: They have built spreadsheets, scripts, or manual processes to cope.
- **Frequency signal**: The problem occurs daily or weekly, not once a year.
- **Urgency signal**: They have actively searched for solutions in the past six months.
- **Authority signal**: The person describing the pain also has budget or decision-making power.
- **Referral signal**: They voluntarily offer to connect you with others who share the problem.

If three or more of these signals are present across multiple interviews, you have strong evidence of a real, actionable customer need. If none are present, revisit your assumptions before building anything.

---

## 4. Competitive Analysis

A thorough competitive analysis prevents you from building something the market already offers and reveals gaps you can exploit. This section provides a structured approach to understanding where you stand relative to alternatives.

### Competitive Landscape Mapping

Competitors fall into four categories, and you must map all of them:

- **Direct competitors** - Products solving the same problem for the same audience (e.g., Figma vs. Sketch for UI design).
- **Indirect competitors** - Products solving the same problem differently or for an adjacent audience (e.g., Canva vs. Figma, both handle design but target different users).
- **Substitutes** - Non-product alternatives customers use today, including spreadsheets, email threads, manual processes, or hiring someone to do the task.
- **Do nothing** - The status quo. This is often your biggest competitor. Quantify the cost of inaction to fight it.

To build the map, list every alternative a prospect might evaluate before buying your product. Talk to at least five potential customers and ask: "How do you handle this today?" Their answers populate the landscape.

### Competitor Analysis Framework

For each competitor, evaluate six dimensions:

| Dimension | What to Capture |
|---|---|
| **Features** | Core capabilities, notable gaps, recent launches |
| **Pricing** | Model (per-seat, usage, flat), entry price, enterprise tier |
| **Positioning** | Who they say they serve, primary message, brand tone |
| **Strengths** | What customers praise in reviews, defensible moats |
| **Weaknesses** | Repeated complaints, churn reasons, missing features |
| **Customer Sentiment** | NPS (if available), review site ratings, social mentions |

Compile findings into a single comparison table. Update it quarterly. Assign one team member as the owner of competitive intelligence so it stays current.

### Differentiation Strategy

Differentiation must be real, meaningful to customers, and hard to copy. Work through these questions:

1. **What can you do that competitors cannot?** Look at proprietary data, unique integrations, specialized domain expertise, or a fundamentally different technical architecture.
2. **What do competitors deprioritize?** Read their negative reviews. Patterns in complaints reveal underserved needs you can own.
3. **What audience segment do they ignore?** Large incumbents often neglect small teams, specific verticals, or non-English markets.

Write a one-sentence unique value proposition using this formula: "We help [audience] achieve [outcome] by [mechanism], unlike [alternative] which [limitation]." Test this statement with five prospects. If they do not immediately understand it, rewrite it.

### Positioning Matrix

Create a 2x2 matrix using the two dimensions that matter most to your buyers. Choose axes where you can credibly claim a distinct quadrant.

Example axes to consider: ease of use vs. depth of features, self-serve vs. sales-led, SMB-focused vs. enterprise-focused, horizontal vs. vertical.

```
                High Ease of Use
                     |
        Quadrant A   |   Quadrant B
       (Simple +     |  (Simple +
        Broad)       |   Specialized)
   ------------------|------------------
        Quadrant C   |   Quadrant D
       (Complex +    |  (Complex +
        Broad)       |   Specialized)
                     |
                Low Ease of Use
   Horizontal <------|------> Vertical
```

Plot each competitor on the matrix. Identify the quadrant with the fewest strong players and the highest unmet demand. That is your strategic position.

### Competitive Intelligence Sources

Use these sources to gather ongoing competitor data:

- **Review sites** - G2, Capterra, TrustRadius. Filter by recency and read one-star and three-star reviews for honest assessments.
- **Job postings** - Competitor hiring patterns reveal product roadmap priorities. A surge in ML engineer postings signals AI investment.
- **SEC filings and investor materials** - For public companies, 10-K filings disclose revenue segments, customer counts, and risk factors.
- **Social media and communities** - Twitter/X, LinkedIn, Reddit, and Hacker News surface real user opinions and product announcements.
- **Customer interviews** - Ask churned competitor customers why they left. Ask current competitor customers what they wish were different.
- **Product usage** - Sign up for competitor free trials. Document onboarding flows, feature depth, and UX quality firsthand.
- **Industry reports** - Analyst reports from Gartner, Forrester, or niche analysts provide market sizing and vendor rankings.

Set up Google Alerts for each competitor name. Review the landscape monthly and update your comparison table and positioning matrix as the market shifts.

---

## 5. Business Model Design

The business model is the mechanism that converts value creation into value capture. During discovery, the goal is not to finalize a model but to identify the strongest candidates and design experiments to validate them.

### Revenue Model Exploration

Select a revenue model by matching it to how customers experience value:

| Model | Best When | Key Metric |
|---|---|---|
| SaaS (Subscription) | Value accrues continuously over time | Monthly Recurring Revenue (MRR) |
| Marketplace | You connect two sides of a transaction | Gross Merchandise Value (GMV) |
| Transactional | Each use is a discrete, high-value event | Revenue per Transaction |
| Freemium | Core utility is simple; power features differentiate | Free-to-Paid Conversion Rate |
| Usage-Based | Consumption varies significantly across users | Revenue per Unit Consumed |

**Decision filter:** Ask three questions: (1) Does the customer get value once or repeatedly? (2) Is willingness to pay predictable or variable? (3) Does a free tier accelerate or undermine adoption? The intersection of answers narrows the field to one or two candidate models.

### Unit Economics Framework

Even pre-revenue, you can estimate foundational unit economics with assumptions drawn from customer interviews and competitive research.

- **Customer Acquisition Cost (CAC):** `CAC = Total Sales & Marketing Spend / New Customers Acquired`. Pre-revenue estimate: sum the cost of your planned channels (ad spend, sales salaries, tooling) and divide by the number of customers you expect to convert based on benchmark conversion rates.
- **Lifetime Value (LTV):** `LTV = ARPU x Gross Margin x Average Customer Lifespan`. For a SaaS product charging $50/month at 80% gross margin with 24-month average retention: `LTV = $50 x 0.80 x 24 = $960`.
- **LTV:CAC Ratio:** Target 3:1 or higher. Below 1:1 means you lose money on every customer.
- **Payback Period:** `Payback = CAC / (ARPU x Gross Margin)`. If CAC is $300 and monthly gross profit per user is $40, payback is 7.5 months.

### Pricing Strategy Discovery

Use multiple methods to triangulate an initial price point:

1. **Van Westendorp Price Sensitivity Meter:** Ask prospects four questions -- at what price is this product too cheap, a bargain, getting expensive, and too expensive? Plot the cumulative responses; the intersection of "too cheap" and "too expensive" curves identifies the acceptable price range.
2. **Willingness-to-Pay Interviews:** Ask "What do you currently pay to solve this problem?" and "What would you pay for a solution that does X?" Anchor on existing spend, then test premium positioning.
3. **Competitive Benchmarking:** Map competitors on a price-vs-feature matrix. Identify whether you are entering as a low-cost alternative or a premium offering.
4. **Value-Based Pricing:** Quantify the economic value delivered (time saved, revenue gained, cost avoided) and price at 10-20% of that value as a starting point.

### Go-to-Market Hypotheses

Define testable GTM hypotheses before launch:

- **Early Adopter Segment:** Identify the single customer profile with the highest urgency and lowest switching cost. Validate with: "Would you use an incomplete version of this product today?"
- **Initial Channel:** Choose one primary channel. For B2B, this is typically outbound sales, LinkedIn, or partnerships. For B2C, consider content, paid social, or community-led growth. Test with a $500-$1,000 budget before scaling.
- **Distribution Strategy:** Decide between direct sales, self-serve, or channel partnerships. Map the decision to deal size -- under $1K ACV favors self-serve; above $25K ACV favors direct sales.

### Business Model Canvas (Lightweight Template)

Use this nine-block canvas to map the full model on a single page:

| Block | Discovery Question |
|---|---|
| **Customer Segments** | Who is the primary early adopter? |
| **Value Propositions** | What job does this solve, and why is our approach better? |
| **Channels** | How will we reach and deliver to customers? |
| **Customer Relationships** | Self-serve, high-touch, or community-driven? |
| **Revenue Streams** | Which revenue model and pricing structure? |
| **Key Resources** | What do we need to build and operate (tech, data, talent)? |
| **Key Activities** | What must we do exceptionally well? |
| **Key Partnerships** | Who do we depend on (suppliers, platforms, integrators)? |
| **Cost Structure** | What are the major fixed and variable costs? |

Fill each block with hypotheses, not answers. Every entry should have a corresponding validation experiment. Revisit the canvas after each round of discovery interviews and update based on evidence.

---

## 6. Risk & Feasibility Assessment

Before committing resources to building anything, you need to systematically surface what you don't know, test your riskiest assumptions cheaply, and define clear criteria for when to walk away. This section provides the frameworks to do exactly that.

### Assumption Mapping

Every business idea rests on a stack of unproven assumptions. Map them across three categories:

- **Desirability** - Will people want this? (e.g., "Freelancers find invoicing painful enough to pay for a solution.")
- **Viability** - Can this sustain a business? (e.g., "Customers will pay $29/month," or "CAC will stay below $50.")
- **Feasibility** - Can we actually build and deliver this? (e.g., "We can process payments across 12 countries.")

Prioritize assumptions using a simple 2x2 matrix: plot each assumption by **importance to the business model** (high/low) against **current evidence level** (strong/weak). Assumptions that are high-importance and weak-evidence are your critical risks -- test these first.

### Experiment Design

Test assumptions before writing code. Match experiment type to what you need to learn:

| Experiment Type | Best For | Cost/Time | Example |
|---|---|---|---|
| **Landing page smoke test** | Demand validation | $100 / 1 week | Describe the product, measure signup rate |
| **Concierge MVP** | Value delivery testing | $0 / 2-4 weeks | Deliver the service manually to 5-10 users |
| **Wizard of Oz** | UX and workflow validation | Low / 2-3 weeks | User-facing prototype with human-powered backend |
| **Pre-sale or letter of intent** | Willingness to pay | $0 / 1-2 weeks | Ask prospects to commit money or sign LOIs |
| **Competitor teardown** | Market positioning | $0 / 3 days | Use rival products and document gaps |

For each experiment, define in advance: the assumption being tested, the metric you will measure, and the pass/fail threshold (e.g., "At least 8% of landing page visitors enter their email").

### Technical Feasibility Assessment

Answer these questions early to avoid costly surprises:

1. **Core technical risk** - What is the single hardest technical problem? Can you build a proof-of-concept in under two weeks?
2. **Data requirements** - What data do you need, and can you access or generate it?
3. **Integration dependencies** - Do you rely on third-party APIs, and what are their reliability, cost, and rate limits?
4. **Build vs. buy** - For each major component, evaluate whether to build custom, use an off-the-shelf tool, or integrate a managed service. Default to buying unless the component is your core differentiator.
5. **Scalability concerns** - Identify any architecture decisions that would be expensive to change later.

### Regulatory & Legal Considerations

Investigate these areas during discovery, not after launch:

- **Data privacy** - Does your product collect personal data? Determine GDPR, CCPA, or sector-specific compliance requirements.
- **Intellectual property** - Conduct a basic prior art search. Confirm your brand name is available for trademark.
- **Industry-specific regulation** - Healthcare (HIPAA), finance (PCI-DSS, SOX), education (FERPA), and food/beverage all carry distinct requirements. Identify which apply.
- **Licensing and terms of service** - Verify that your use of third-party APIs, datasets, or open-source software complies with their license terms.
- **Liability and insurance** - Determine what professional liability or product liability exposure exists.

Engage a specialist attorney for a one-hour discovery consultation once you have narrowed your concept. This small upfront cost can prevent existential legal risk.

### Kill Criteria

Define these before emotional attachment sets in. Agree as a team on specific, measurable thresholds that would cause you to pivot or stop:

- **Demand signal failure** - Fewer than X% of target users express interest after Y outreach attempts.
- **Willingness-to-pay failure** - Fewer than X prospects commit to a pre-order or LOI within Y weeks.
- **Technical dead end** - The core technical proof-of-concept cannot be completed within the time and budget allocated.
- **Regulatory block** - Legal review reveals compliance costs that exceed your runway or fundamentally change the unit economics.
- **Competitive moat absence** - Research reveals an incumbent with identical positioning and strong distribution you cannot realistically overcome.

Write these criteria down and revisit them at each milestone. The discipline to stop is as valuable as the ambition to start.

---

## Discovery Phase Completion Checklist

Use this checklist to confirm you have completed the discovery phase with sufficient rigor:

- [ ] Problem defined using PUFS framework and validated with 10+ interviews
- [ ] Jobs-to-Be-Done statement written and tested with prospects
- [ ] TAM/SAM/SOM estimated using both top-down and bottom-up methods
- [ ] At least 2 market timing forces identified and documented
- [ ] Porter's Five Forces assessed for the target industry
- [ ] 3+ customer personas built from real interview data
- [ ] 10+ discovery interviews completed with synthesis after every 5
- [ ] 3+ validation signals confirmed across multiple interviews
- [ ] Competitive landscape mapped across all four categories
- [ ] Positioning matrix created with clear strategic quadrant chosen
- [ ] Revenue model selected with rationale documented
- [ ] Unit economics estimated (CAC, LTV, payback period)
- [ ] Pricing tested via at least 2 methods
- [ ] Top 5 riskiest assumptions identified and prioritized
- [ ] At least 2 cheap experiments run to test critical assumptions
- [ ] Kill criteria defined and agreed upon by the team

**If all boxes are checked with supporting evidence, you are ready to move from Discovery to Definition (MVP scoping).**
