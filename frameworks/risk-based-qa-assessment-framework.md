# Risk-Based QA Assessment Framework

## Purpose
This framework explains how I approach QA assessments by focusing on risk rather than raw test coverage.

The goal is to direct effort where failures are most likely and most costly.

## Core Risk Dimensions

### Business Impact
- What happens if this fails?
- Who is affected?
- Is the impact visible or silent?

### Change Frequency
- How often does this area change?
- Are changes usually small or structural?

### Data Sensitivity
- Is sensitive or irreversible data involved?
- Are compliance or audit expectations present?

### Integration Exposure
- Does this depend on external systems?
- How tolerant is the system to failures?

## Assessment Principles
- Not everything needs to be tested equally
- Early clarity prevents over-engineering
- Some risks are acceptable and intentional
- Testing decisions should reflect business priorities

## Outcome of the Framework
- Clear testing priorities
- Reduced unnecessary automation
- Improved release confidence
- Better conversations between engineering and business

This framework is deliberately lightweight and adaptable across domains.