<div align="center">
  <img src="5164c31f-aa0e-4b7f-a5d1-6803acc0dd2b.png" alt="Nexus Insight Cards Logo" width="150"/>
  <h1>NexusInsightCards</h1>
  <p><strong>Advanced Smart KPI Grid Custom Visual for Microsoft Power BI</strong></p>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-Compatible-yellow?logo=powerbi" alt="Power BI Compatibility">
  <img src="https://img.shields.io/badge/License-Freemium-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Architecture-Enterprise_Grade-blue" alt="Architecture">
</p>

## 🚀 Overview
**NexusInsightCards** is an enterprise-grade custom visual for Microsoft Power BI. It transforms standard reporting into an actionable executive dashboard. By dynamically generating a CSS Grid of KPI cards based on input measures, it delivers high-density insights, trend analysis, and instant managerial alerts in a single, highly optimized, and visually stunning component.

## 📊 Visual Preview
*Executive view of growth, profitability, discount pressure, and customer sentiment.*

<p align="center">
  <img src="image_853a03.jpg" alt="Nexus BI Dashboard Preview" width="100%" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</p>

## ✨ Key Technical Features
- **Dynamic Formatting & Units:** Full support for DAX format strings (`formatStringMeasure`) and dynamic unit labels (`unitMeasure`). Each card can independently display $, %, or quantity based on the data.
- **5 Built-in Sparkline Types:** Embed immediate trend visualization using Line, Area, Bar, Progress Bar, or Gauge charts without cluttering the canvas.
- **Smart Alert Footers:** Automated, threshold-based intelligent text alerts (`insightText`) provide managers with split-second contextual insights.
- **Glanceable Variance Indicators:** Instant visual feedback (▲/▼) comparing performance against targets.
- **Rich Iconography library:** 13 built-in categorical icons (Finance, Logistics, Security, etc.) with customizable shadow effects for a polished UI.
- **Advanced Grid Layout:** Fully customizable CSS Grid architecture (columns, gap, padding) ensuring responsive layouts.
- **AppSource Ready:** Full compliance with Microsoft's accessibility standards, including High Contrast mode support and keyboard navigation.

## ⚙️ Data Roles Configuration
Map your Power BI fields as follows to unlock the visual's full potential:
- **KPI Category:** The grouping dimension used to generate individual cards.
- **Data Field (Primary Measure):** The primary numeric value to be displayed.
- **Target Value:** The comparison metric used for variance and YoY calculations.
- **Trend Axis:** The categorical/date axis required for rendering sparklines.
- **Reference Tooltip & Formatting:** Optional roles for dynamic text (`insightText`), custom DAX formats, and dynamic border colors.

## 📦 Installation
1. Download the latest `.pbiviz` file from the [Releases](../../releases) section.
2. Open **Power BI Desktop**.
3. In the **Visualizations** pane, click the three dots (`...`) and select **Import a visual from a file**.
4. Import the `NexusInsightCards_v1.0.0.pbiviz` visual and start building your executive views.

## 💎 Licensing & 30-Day Demo Trial
The visual operates in a **Freemium** model (displays up to 3 cards for free). To unlock the full premium experience and evaluate the visual for 30 days, apply the following demo key in the visual's **Format Pane -> License & Activation**:

> **Demo Key:** `NEXUS-eyJjbGllbnQiOiJHaXRIdWJEZW1vIiwiZXhwIjoiMjAyNi0wOC0zMCJ9-114F23C`
*(Valid until August 30, 2026)*

For **Enterprise Activation Keys**, custom feature requests, or support, please reach out to our team at:
📫 **[info@nexusinsightcards.com](mailto:info@nexusinsightcards.com)**
