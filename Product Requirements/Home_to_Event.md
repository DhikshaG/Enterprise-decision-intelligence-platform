## Purpose

Enable plant leadership to move from a **summary metric to the events contributing to it**, with relevant filters applied automatically.

## Clickable Logic

**Home → Metric / Insight → Events → Filtered Evidence → Event Investigation**

| Home Element | User Action | Events View |
|---|---|---|
| **Total Events** | Click KPI | All Events |
| **High-Impact Events** | Click KPI | Business Impact = High |
| **Open Events** | Click KPI | Status = Open |
| **Business Impact** | Click KPI | Events contributing to total impact |
| **Impact by Area** | Click area | Events contributing to selected area |
| **Events by Type** | Click event type | Events of selected type |
| **Trend** | Select period | Events within selected period |

## Design Principle

> **Home presents the signal. Events presents the evidence.**

Every clickable element carries its **context into Events**, so the user does not need to recreate the analysis manually.

## User Journey

**Home**

→ **Select signal**

→ **Events with filters applied**

→ **Review contributing events**

→ **Investigate selected event**

→ **Decision Context**

→ **Action**

## Visual

[Home → Events — Clickable Navigation](./Home_to_Events.png)
