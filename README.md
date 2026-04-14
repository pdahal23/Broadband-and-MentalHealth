# Broadband Expansion and Mental Health Outcomes
**Pragati Dahal · Virginia Tech · Work in Progress**

## Overview
Does broader access to high-speed internet improve or harm mental health? The net effect is theoretically ambiguous: broadband may improve mental health through telehealth access and health information, but may also worsen it through increased screen time and social displacement. This paper estimates the causal effect of broadband expansion on county-level mental health outcomes in the United States.

## Identification Strategy
We exploit staggered adoption of higher-speed broadband thresholds across U.S. counties in a difference-in-differences framework. We implement the Callaway–Sant'Anna (2021) estimator to address heterogeneous treatment effects across cohorts, and complement this with causal forest methods to characterize treatment effect heterogeneity.

## Data
| Source | Variables | Coverage |
|--------|-----------|----------|
| FCC Form 477 | Broadband availability by technology and speed tier | 2008–2022 |
| County Health Rankings | Poor mental health days, frequent mental distress | 2010–2024 |
| CDC PLACES | Depression prevalence, mental health outcomes | 2016–2023 |
| ACS (5-year) | Demographics, income, education, rurality | 2008–2022 |

*Raw data are not included in this repository. All sources are publicly available. See `/data/README.md` for download instructions.*

## Repository Structure
## Status
- ✅ Panel construction (FCC × CHR × PLACES × ACS)
- ✅ Treatment variable definition
- 🔄 Callaway–Sant'Anna estimation (in progress)
- ⬜ Causal forest heterogeneity analysis
- ⬜ Paper draft

## Contact
Pragati Dahal — pdahal23@vt.edu · pdahal23.github.io
