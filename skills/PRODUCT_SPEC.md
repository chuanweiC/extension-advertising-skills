# PRODUCT_SPEC

## Project Name
Extension Advertising Skills

## One-Sentence Summary
Turn a client advertising brief into a structured AI-generated paid acquisition plan, including audience strategy, offer positioning, ad angles, messaging, funnel recommendations, and testing priorities.

---

## 1. Purpose

This project is designed to help businesses, operators, media buyers, and agencies convert raw client information into a usable advertising strategy.

Instead of asking AI to immediately "write ads," this system breaks the work into structured reasoning steps:
- understand the audience
- clarify the offer
- identify awareness stage
- determine positioning
- develop mechanisms and angles
- recommend funnel paths
- generate messaging directions
- flag risks, assumptions, and testing priorities

The goal is not just better-looking outputs.  
The goal is better advertising thinking.

---

## 2. Problem Statement

Most AI-generated marketing outputs fail because they:
- jump straight into writing
- rely on generic language
- ignore customer awareness level
- ignore market sophistication
- fail to connect ad messaging with funnel structure
- produce content that sounds polished but does not convert

Most client briefs are also incomplete, vague, or unstructured.  
This project solves that problem by turning messy input into a structured advertising plan.

---

## 3. Core Product Goal

The primary goal of this project is to produce a structured paid acquisition plan from a client brief.

The system should help answer questions such as:
- Who exactly is the target customer?
- What is the strongest version of the offer?
- What problem and desire should the campaign focus on?
- What awareness stage is the audience in?
- What advertising angles are most likely to resonate?
- What should happen after the ad click?
- What should be tested first?
- What assumptions or missing inputs could reduce performance?

---

## 4. Target Users

This project is built for the following users:

### 4.1 Founders and small business owners
Users who want help planning paid campaigns without relying entirely on an agency or senior media buyer.

### 4.2 Media buyers
Users who want a faster, more structured way to generate campaign strategy, angles, hooks, and testing plans.

### 4.3 Agencies
Teams that want a repeatable system for turning briefs into campaign plans with more consistency across team members.

### 4.4 AI workflow builders
Developers or operators who want to embed structured advertising intelligence into agents, apps, or internal workflows.

---

## 5. Primary Use Case

A user provides a campaign brief.

The system analyzes the brief and returns a structured advertising plan that may include:
- target audience summary
- offer clarification
- positioning recommendations
- awareness stage assessment
- dominant desire
- mechanism hypotheses
- ad angles
- creative directions
- funnel recommendations
- landing page structure
- objection handling themes
- testing roadmap
- assumptions and risks

This output is intended to support real campaign planning before launch.

---

## 6. Product Scope

## 6.1 In Scope for V1
Version 1 focuses on campaign planning and messaging strategy.

The system should support:
- brief intake
- audience clarification
- offer extraction
- positioning analysis
- awareness mapping
- ad angle generation
- creative direction generation
- funnel path recommendation
- landing page outline generation
- objection mapping
- generic language cleanup
- structured output formatting
- test priority recommendations

## 6.2 Out of Scope for V1
Version 1 does not directly execute media buying tasks inside ad platforms.

The system does not:
- create ad accounts
- upload creatives to Meta, TikTok, or Google Ads
- set campaign budgets in platform dashboards
- manage bidding automatically
- pull live ad account data by default
- generate performance guarantees
- replace legal or compliance review

These may be future expansion areas, but they are not required in V1.

---

## 7. Inputs

The system requires a structured campaign brief.

## 7.1 Required Inputs
The minimum required fields are:

- business_type  
  Example: online coaching, SaaS, e-commerce, local service

- product_or_service  
  A clear description of what is being sold

- campaign_goal  
  Example: booked calls, lead generation, direct purchase, webinar registration

- target_audience  
  A best-available description of the intended customer

- primary_platform  
  Example: Meta, TikTok, YouTube, Google

## 7.2 Recommended Inputs
These are highly recommended for better output quality:

- offer_details  
  Pricing, package structure, bonuses, guarantee, urgency, or CTA

- current_positioning  
  How the client currently describes the product or service

- proof_assets  
  Testimonials, case studies, results, reviews, data points, credentials

- existing_landing_page  
  URL or summary of the current page

- existing_ads  
  Current or previous creatives, hooks, headlines, copy, scripts

- known_objections  
  Why prospects hesitate or do not convert

- desired_customer_action  
  Exact next step: book call, apply, buy now, join waitlist, etc.

- budget_range  
  Rough spending range for planning context

- market_context  
  Competitors, crowded claims, known saturation, or unique advantages

- voice_of_customer_data  
  Reviews, support tickets, sales call notes, survey responses, DMs

## 7.3 Optional Inputs
- region_or_market
- seasonality
- creative_constraints
- legal_constraints
- compliance_notes
- brand_tone
- internal priorities
- timeline

---

## 8. Input Quality Rules

The system should not invent critical missing inputs.

If important information is unavailable, the output must:
- explicitly flag missing information
- separate facts from assumptions
- provide conditional recommendations where needed

The system should prefer clarity over false certainty.

---

## 9. Outputs

The final output should be structured and easy to review, edit, and hand off.

## 9.1 Core Output Sections
The default output format should include:

### 1. Campaign Summary
A brief overview of the campaign goal, business context, and recommended strategic direction.

### 2. Audience Profile
A refined description of the likely buyer, including:
- who they are
- what they want
- what they fear
- what they have already tried
- what would make them act

### 3. Offer Summary
A clarified version of the product/service offer, including:
- what is being sold
- what outcome it promises
- why it matters
- what makes it more attractive

### 4. Positioning Insight
A short explanation of how the offer should be positioned relative to alternatives.

### 5. Awareness Stage
A recommended awareness classification for the audience, with reasoning.

### 6. Dominant Desire
The primary emotional or practical desire driving action.

### 7. Mechanism Hypothesis
A proposed mechanism, narrative frame, or “new way to win” that makes the message more compelling.

### 8. Ad Angles
A set of recommended campaign angles, each with:
- angle name
- core idea
- who it fits
- why it may work

### 9. Creative Directions
Suggested creative routes such as:
- hooks
- opening concepts
- headline directions
- visual concepts
- script directions

### 10. Funnel Recommendation
The recommended path after the click, such as:
- landing page
- lead form
- quiz
- application form
- video sales letter
- webinar
- booked call path

### 11. Landing Page Outline
A suggested structure for the page, including key sections and persuasion sequence.

### 12. Objection Map
The top objections to address and how messaging should reduce them.

### 13. Testing Roadmap
Recommended first-round tests, including:
- hooks
- angles
- mechanisms
- CTA styles
- funnel variants
- proof emphasis

### 14. Risks and Assumptions
A list of:
- missing data
- uncertain assumptions
- possible weak spots
- implementation risks

---

## 10. Output Principles

All outputs should follow these principles:

- specific, not generic
- grounded in provided inputs
- explicit about assumptions
- logically consistent across sections
- connected from ad to funnel
- useful for real campaign planning
- readable by humans, not just machines

The system should avoid empty marketing phrases and vague claims.

---

## 11. Workflow Overview

The intended workflow for the system is:

1. intake the client brief  
2. validate required inputs  
3. identify missing or weak inputs  
4. run foundational extraction and clarification  
5. map awareness and positioning  
6. generate mechanisms, angles, and messaging directions  
7. recommend funnel structure  
8. run QA checks for generic language and consistency  
9. format the final campaign plan

This workflow should be modular and extensible.

---

## 12. System Components

The project is expected to use modular skills grouped into functional layers.

## 12.1 Foundations
Responsible for identifying the commercial reality before writing anything:
- audience extraction
- voice of customer mining
- offer extraction
- proof gathering
- positioning core

## 12.2 Copy Strategy Layer
Responsible for persuasion logic:
- awareness mapping
- market sophistication analysis
- dominant desire extraction
- mechanism development
- headline logic
- objection handling
- close strategy

## 12.3 Operator Layer
Responsible for campaign execution planning:
- ad angles
- creative directions
- conversion path design
- landing page structure
- email sequence direction
- performance diagnosis
- testing roadmap

## 12.4 QA Layer
Responsible for improving final quality:
- generic language removal
- claim review
- consistency review
- final polish

## 12.5 Orchestration Layer
Responsible for deciding which skills run and in what order based on campaign type.

---

## 13. Suggested Campaign Modes

The system should support multiple campaign planning modes over time.

## 13.1 Booked Call Campaign
For service businesses, coaches, consultants, and high-ticket offers.

## 13.2 Lead Generation Campaign
For form fill, inquiry, or list-building campaigns.

## 13.3 Direct Response Purchase Campaign
For direct purchase offers, especially lower-friction products.

## 13.4 Funnel Diagnosis Mode
For improving an existing campaign with weak performance.

Version 1 may start with just one or two of these modes.

---

## 14. V1 Recommended Scope

To keep the first version realistic, V1 should focus on one core mode:

### Recommended V1 focus:
Booked Call Campaign Planner

Why:
- clear output structure
- good fit for strategic selling
- strong need for positioning and objection handling
- easier to demonstrate value with structured planning output

V1 should produce:
- ICP
- offer summary
- awareness stage
- 3 to 5 ad angles
- 5 to 10 creative hook directions
- funnel recommendation
- landing page outline
- objection map
- testing roadmap

---

## 15. Non-Goals

This project is not trying to do everything in digital marketing.

It is not:
- a full ad platform automation tool
- a fully autonomous media buying system
- a creative production studio by itself
- a CRM replacement
- an analytics warehouse
- a guaranteed performance engine

Its purpose is to improve advertising strategy quality and planning speed.

---

## 16. Success Criteria

The product will be considered successful if it can consistently do the following:

- turn incomplete briefs into clearer campaign plans
- reduce generic AI marketing output
- produce outputs that are more strategically coherent
- save planning time for users
- improve the quality of ad angles and funnel recommendations
- make assumptions visible instead of hiding them
- help users move from “I need ads” to “I have a structured campaign plan”

---

## 17. Evaluation Criteria

The quality of the system output should be evaluated using the following dimensions:

- audience clarity
- offer specificity
- positioning sharpness
- awareness accuracy
- mechanism strength
- angle diversity
- funnel coherence
- objection coverage
- non-generic language quality
- consistency across sections
- actionability of testing roadmap

These criteria may later be formalized into an evaluation rubric.

---

## 18. Constraints

The system is constrained by:
- quality of client inputs
- availability of proof and VOC data
- clarity of offer and audience
- platform-specific realities not always present in the brief
- legal/compliance boundaries in certain industries

The system should acknowledge these limitations instead of pretending certainty.

---

## 19. Risks

Known risks include:
- overconfident outputs based on weak inputs
- generic recommendations when VOC is missing
- mismatch between ad angle and actual funnel experience
- weak mechanism quality in crowded markets
- incorrect assumptions about audience awareness
- excessive breadth without prioritization

Mitigation should include:
- assumption labeling
- QA passes
- output structure discipline
- human review before launch

---

## 20. Human-in-the-Loop Expectations

This project is designed to assist humans, not eliminate all human judgment.

Human review is still recommended for:
- final claim approval
- legal/compliance review
- platform policy review
- budget decisions
- creative production decisions
- launch readiness
- interpretation of ambiguous business context

---

## 21. Future Directions

Potential future improvements may include:
- platform-specific planning modules for Meta, TikTok, YouTube, and Google
- direct integration with ad account data
- campaign diagnosis based on performance metrics
- structured VOC ingestion pipelines
- competitor analysis modules
- creative briefing outputs for designers and editors
- landing page generation support
- dashboard or web app interface
- API-based orchestration
- automated evaluation framework

These are future opportunities, not V1 requirements.

---

## 22. Recommended Repository Deliverables

To make this project usable, the repository should eventually include:

- PRODUCT_SPEC.md
- README.md
- campaign brief template
- example input files
- example output files
- orchestrator logic
- evaluation criteria
- architecture documentation
- roadmap
- contribution guidance

---

## 23. V1 Deliverable Definition

Version 1 should be considered complete when a user can:

1. submit a structured campaign brief  
2. run a defined campaign planning workflow  
3. receive a structured paid acquisition plan  
4. review assumptions and risks  
5. use the output to prepare for campaign launch

---

## 24. Final Product Definition

This project is an AI advertising strategy engine.

Its job is to transform a client brief into a structured campaign plan that is more specific, more strategic, and more usable than standard AI-generated marketing content.

It is not just a prompt library.  
It is a system for encoding advertising thinking.
