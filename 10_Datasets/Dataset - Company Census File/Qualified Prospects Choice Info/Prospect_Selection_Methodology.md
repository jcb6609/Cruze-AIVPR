# Prospect Selection Methodology

## Objective

The purpose of this methodology is to identify and prioritize commercial fleet operators that most closely align with Cruze's AI Video Prospecting workflow before investing time in detailed company research, executive mapping, and personalized video outreach.

Rather than determining whether a company will ultimately become a customer, this process is designed to prioritize research efforts by identifying companies whose fleet operations appear to best match Cruze's target market.

This methodology was developed from the following Cruze onboarding resources:

- **Cruze 101 — What We're Building**
- **Company Profile, Technology & Intern Commissions**
- **AI Video Prospecting Role Guide**

According to these resources, Cruze develops navigation intelligence for **Class 8 commercial truck fleets**, providing AI-driven advisory speed recommendations through real-time telemetry and traffic intelligence. The platform is designed to help commercial fleets reduce:

- Fuel consumption
- Unnecessary braking and acceleration
- Equipment wear
- Highway congestion
- Operational costs
- Safety risks

Additionally, the **AI Video Prospecting Role Guide** instructs interns to identify commercial fleet operators, perform executive mapping, and create personalized outreach to secure commercial fleet pilots.

---

# Step 1 — Screening Qualified Prospects

Before beginning company research, executive mapping, or personalized video creation, every company contained in `Qualified_Prospects.csv` undergoes an initial screening process.

Based on Cruze's onboarding materials, each company is evaluated using the following questions:

### 1. Does the company operate Class 8 commercial truck fleets?

Cruze's technology is specifically designed for commercial heavy-duty truck fleets. Companies without Class 8 operations are generally outside the target market.

---

### 2. Is freight transportation, logistics, or commercial fleet operations a core part of the company's business?

Companies whose primary business depends on operating commercial fleets are generally stronger initial prospects than organizations whose trucks simply support another industry.

---

### 3. Does the company appear to operate regional or interstate highway routes?

Cruze's platform focuses on optimizing vehicle movement through intelligent speed recommendations and real-time traffic intelligence. Companies with significant highway operations are therefore stronger candidates.

---

### 4. Would reducing fuel consumption, unnecessary braking, equipment wear, and traffic-related delays likely provide measurable operational value to this fleet?

These operational improvements represent the primary value proposition described throughout Cruze's onboarding resources and company profile.

---

Companies that strongly satisfy these criteria are considered **high-priority research candidates** and proceed to the next phase of the AI Video Prospecting workflow.

---

# Step 2 — AI-Assisted Screening Procedure

To perform the initial screening efficiently and consistently, companies are reviewed in groups of **10** from `Qualified_Prospects.csv`.

For each group, both **Google Gemini (AI Search)** and **ChatGPT** are used as complementary AI screening tools.

Using a standardized prompt, both models are asked to evaluate each company against the screening criteria established in **Step 1**, including:

- Whether the company operates Class 8 commercial truck fleets.
- The company's primary business.
- Whether trucking is the company's primary revenue-generating activity or a supporting function.
- The type of fleet operated (freight transportation, private fleet, specialized fleet, passenger transportation, etc.).
- Whether the company's operations appear to align with Cruze's target market.

The AI responses are used **only as an initial screening aid**.

Because large language models may infer information or rely on incomplete or outdated public sources, **every promising prospect is subsequently verified using the company's official website and other reliable public sources before proceeding to detailed research.**

This verification step ensures that research time is invested only in companies whose publicly available information supports the AI-assisted screening.

---

## Screening Status

After completing the AI-assisted screening:

- Companies identified as **high-priority prospects** receive a **green background** in `Qualified_Prospects.csv`; meanwhile, companies identified as **medium/high-priority** receive a **yellow background**.

- Every company that has completed the AI-assisted screening process has its **LEGAL_NAME** formatted in *italics*, indicating that the company has already undergone the initial screening, regardless of the final priority assigned.

This visual system allows `Qualified_Prospects.csv` to communicate both:

- Screening progress
- Research priority

without requiring additional tracking files during the initial qualification stage.

## Notes

This methodology is intended to prioritize research efforts during the AI Video Prospecting workflow.

A company that is not initially classified as a high-priority prospect is **not** considered unsuitable for Cruze's platform. Instead, the methodology is designed to maximize research efficiency by directing time toward companies whose publicly available operations appear to align most closely with Cruze's documented target market and value proposition.

As additional experience is gained throughout the internship, this methodology may be refined to better reflect observed prospect characteristics and outreach outcomes.