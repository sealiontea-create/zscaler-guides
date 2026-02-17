# ZS Adoption Toolkit

**Created by Clint Olds, Technical Success Manager**

Interactive customer guides for maximizing the value of your Zscaler platform investment.

**Live Site:** [https://sealiontea-create.github.io/zscaler-guides/](https://sealiontea-create.github.io/zscaler-guides/)

> Unofficial customer guide. Not affiliated with or endorsed by Zscaler, Inc.

## Guides

### 1. Resilience Assessment (Start Here)
Every Zscaler customer needs resilience configured. Covers blackout, brownout, and catastrophic failure scenarios with an interactive readiness checklist and step-by-step setup instructions.

- **Tabs:** Overview, Failure Scenarios, Readiness Checklist, Deployment Plan, Get Started, Objections
- **Interactive:** 14-item checklist with progress tracking (persisted in localStorage)
- **Applies to:** ZIA + ZPA (Business Edition and above)

### 2. DLP Adoption Guide
A practical MVP approach to data loss prevention — start with visibility, grow into protection. Includes engine guide, phased deployment plan, and step-by-step configuration.

- **Tabs:** Why DLP, How It Works, MVP Program, Engine Guide, Get Started, Objections
- **Key concept:** 4-phase rollout (Monitor → Analyze → Caution → Enforce)
- **Applies to:** ZIA (DLP license required)

### 3. Cloud Browser Isolation (CBI)
How isolation protects against phishing, zero-days, and BYOD risks. Features interactive threat scenarios showing before/after with CBI enabled.

- **Tabs:** Threat Scenarios, Key Capabilities, Get Started
- **Interactive:** Threat scenario cards with toggle to show CBI protection
- **Applies to:** ZIA (CBI license required)

## Structure

```
Zscaler Customer Guides/
  index.html                  # Landing page / toolkit hub
  Resilience-Assessment.html  # Guide 1
  DLP-Adoption-Guide.html     # Guide 2
  CBI-Customer-Guide.html     # Guide 3
```

Each guide is a single self-contained HTML file with inline CSS and JavaScript. No build tools, no dependencies, no frameworks — just open in a browser.

## Features

- Self-contained HTML files (no build step, no dependencies)
- Responsive design (mobile-friendly)
- Print-optimized CSS (@media print)
- Tab-based navigation within each guide
- Home navigation back to toolkit landing page
- Step-by-step "Get Started" setup instructions with admin portal navigation paths
- Reference links to help.zscaler.com documentation
- Interactive elements (checklists, expandable objection handlers, threat scenario toggles)

## Hosting

Hosted on GitHub Pages from the `main` branch.

### Deploy Updates
```bash
git add -A
git commit -m "description of changes"
git push
```

Changes go live within a few minutes after push.

## License

Copyright (c) 2026 Clint Olds. All rights reserved.
