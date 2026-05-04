# B2B SaaS Web Application – QA Risk Assessment

## Context
This case study represents a B2B SaaS web application developed by a small, fast-moving team with frequent releases.

The product is actively evolving and prioritizes speed and customer feedback.

## Key Assumptions
- Releases happen frequently, sometimes weekly or more
- Developers perform most functional testing
- QA activities are lightweight or inconsistent
- Product stability directly affects customer retention

## Business-Critical User Flows
- User onboarding and account setup
- Core feature usage tied to customer value
- Configuration changes and saved preferences
- Billing or subscription-related actions

Failures in these areas are highly visible to customers.

## Key Risk Areas Identified

### Change-Related Risks
- Insufficient regression coverage across releases
- Assumptions breaking due to partial feature changes
- Inconsistent environments affecting testing validity

### Integration Risks
- Third-party services (payments, notifications, analytics)
- API contract changes without full impact awareness
- Failure handling and retry logic

### Process Risks
- No clear release readiness criteria
- Reliance on “it worked last time”
- Limited documentation of expected behavior

## Testing Focus Recommendations
- Identify a small, stable regression set covering core flows
- Focus on exploratory testing around changed areas
- Use lightweight automation selectively for high-confidence flows
- Avoid broad test case documentation with low signal value

## Release Readiness Signals
- Explicit list of what changed since last release
- Validation of customer-facing flows
- Quick rollback capability
- Known risks clearly acknowledged by the team

The objective is fast learning without reckless releases.