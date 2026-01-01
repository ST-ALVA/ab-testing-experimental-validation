👉 For a quick, no-setup review of full analysis, download **`ab_testing_experimental_validation.html`**

## Executive Summary

This case study evaluates an A/B test designed to measure the impact of a new recommendation system on user conversion.

Contrary to expectations, the treatment group performed **significantly worse** than the control, showing an approximate **13% decrease in conversion**. Statistical testing confirmed this difference as significant.

Further analysis revealed important limitations in experimental design, including uneven group sizes and strong seasonal effects, which reduce confidence in causal interpretation.

Based on these findings, the most responsible data-driven decision was **not to deploy** the new recommendation system—highlighting the importance of experimental validity over forcing positive outcomes.

# A/B Testing Case Study — Experimental Validation & Decision-Making

This project analyzes a real-world A/B test (`recommender_system_test`) designed to evaluate whether a new recommendation system improves user conversion across the purchase funnel.

The analysis prioritizes **experimental validity and statistical rigor**, demonstrating how data can support a **decision not to deploy** when results are unreliable or negative.

---

## 📌 Project Context

- **Experiment:** A/B test (Control vs. New Recommendation System)
- **Goal:** Achieve at least a **10% uplift in conversion** within 14 days
- **Product:** E-commerce platform with event-level user tracking
- **Focus:** Decision-making under imperfect experimental conditions

---

## 🔍 Methodology & Analytical Approach

- Validated experimental setup and data consistency
- Reconstructed conversion funnels with **multiple user journeys**
- Analyzed user engagement and event distributions
- Assessed temporal and seasonal effects (pre-holiday bias)
- Applied statistical hypothesis testing:
  - One-sided and two-sided Z-tests
  - Confidence intervals (score method)
  - Evaluation of statistical power and false positives

---

## 📊 Key Results

- The treatment group (**Group B**) showed **lower conversion** than control.
- **Observed lift:** −13.1%
- Statistical tests confirmed the difference is **significant**.
- Control users exhibited **higher engagement**, consistent with conversion outcomes.
- Seasonal effects and experimental limitations reduce result reliability.

---

## ✅ Decision

**Do not deploy the new recommendation system.**

This case highlights that **not acting** can be the most data-driven and responsible decision when experimental assumptions are violated.

---

## 🌐 Interactive Visualizations (Plotly)

This project includes **interactive Plotly visualizations** that enable deeper exploration of user behavior, funnel performance, and experimental outcomes across test groups.

**How to view correctly:**
- Download the file **`ab_testing_experimental_validation.html`**
- Open it locally in any modern web browser (Chrome, Firefox, Safari)

⚠️ **GitHub does not render Plotly interactivity** inside notebooks or HTML previews.  
For full interactivity (hover, zoom, tooltips, and dynamic filtering), the HTML file must be opened locally.

The visualization compliments the analytical narrative by providing an interactive view of funnel dynamics and conversion differences that support the A/B test conclusions.

---

## 🔍 Analytical Focus & Methods

This project emphasizes analytical judgment and experimental rigor over surface-level performance metrics:

- Experimental design validation under incomplete and imperfect data
- Funnel analysis across multiple user journeys
- Proportion-based hypothesis testing (Z-tests, confidence intervals)
- Assessment of statistical power and false-positive risk
- Data-driven decision-making under uncertainty, including when *not* to act