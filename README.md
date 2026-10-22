# RTO Rescue MVP

A product-management prototype for a generic SaaS platform serving Shopify merchants with WhatsApp and voice communication. This concept explores reducing Return to Origin (RTO) through recoverable NDR events and measurable shipment outcomes.

## Two initiatives

### 1. Conversational NDR Rescue
A simulated workbench for fictional non-delivery report (NDR) cases. Select a case, simulate customer intent and submit a simulated next action. The interface distinguishes a submitted request from verified delivery and routes refusal to merchant review.

### 2. RTO Outcome Intelligence
A sample analytics dashboard connects NDR cases, responses, carrier actions and final outcomes. It illustrates reason/payment filters and a control-versus-treatment experiment.

## Problem hypothesis
RTO is an outcome, not the root cause. For some failed deliveries, a timely, reason-specific customer conversation and a supported logistics action may resolve an address or availability issue. The hypothesis to validate is that coordinated recovery and reliable outcome attribution improve delivery success compared with the existing workflow. The mere use of WhatsApp or voice is not presented as novel.

## North Star
Eligible shipped-order RTO rate = eligible shipments returned to origin / eligible shipped orders with mature outcomes × 100. Keep eligibility definitions consistent, use mature cohorts, and report pre-dispatch cancellations separately. A submitted carrier request is not carrier acceptance or a successful recovery.

## Pilot hypothesis
Target a +5 percentage-point improvement in successful delivery after NDR versus a comparable control group. This is an experiment hypothesis, not a measured result or guaranteed forecast. Validate baseline, sample size, test duration and cohort maturity before making a commitment.

Supporting metrics: median time to valid next action, customer response rate, valid carrier action acceptance, outcome-linkage coverage and incremental lift versus control. Guardrails: complaints, opt-outs, invalid/duplicate actions, address validation errors, API failures and human escalation load.

## Six-month roadmap
1. Discover, baseline RTO causes/costs, and validate carrier events/actions.
2. Build one-provider NDR ingestion, order matching and WhatsApp flows.
3. Add supported carrier actions, acknowledgements, retries and human fallback.
4. Link interventions to mature outcomes and run a controlled pilot.
5. Test voice only for eligible unresolved cases if it adds incremental lift.
6. Expand carrier coverage only after reliable actions, credible lift and positive economics.

## Important limitations
This is a static front-end demo using fictional data. It does not connect to Shopify, WhatsApp, voice providers or courier APIs; it sends no messages and makes no real carrier requests. All dashboard figures are illustrative. Validate carrier capabilities, event quality, data permissions and compliance before production.

## Publish with GitHub Pages
In repository Settings → Pages, choose Deploy from a branch, select main and /(root), then save. GitHub will show the published URL once deployment finishes.
