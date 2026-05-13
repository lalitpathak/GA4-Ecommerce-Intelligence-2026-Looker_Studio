# 📊 Google Analytics (GA4) Setup Notes

This document explains how Google Analytics 4 (GA4) was configured for the Digital Marketing Analytics Dashboard project.

---

# 🎯 Objective

To collect website interaction data including:
- User behavior
- Traffic sources
- Engagement metrics
- Conversion tracking
- Revenue performance (demo data)

---

# 🧩 Step 1: Create GA4 Account

1. Go to Google Analytics:
   https://analytics.google.com
2. Click **Start Measuring**
3. Create account:
   - Account Name: Digital Marketing Analytics Project
4. Create Property:
   - Property Name: Marketing Dashboard 2026
   - Time zone: Ireland (or user region)
   - Currency: EUR or USD

---

# 🌐 Step 2: Create Web Data Stream

1. Select **Web**
2. Enter:
   - Website Name: Demo Marketing Site
   - Website URL: (GitHub Pages or test URL)
3. Copy Measurement ID:
   - Format: G-XXXXXXXXXX

---

# Google Analytics 4 Setup Notes

This project uses a standard GA4 demo ecommerce dataset provided by Google for learning and analytics practice.

---

## 1. Data Source

The dataset used is:

- Google Merchandise Store (GA4 Demo Account)
- Provided by Google as a preconfigured ecommerce analytics dataset

This dataset contains real-like ecommerce behavior data including:
- User traffic
- Engagement events
- Ecommerce transactions
- Marketing channel data

---

## 2. Data Nature

- This is a **demo GA4 property**
- No manual tracking setup was required
- Data is pre-populated and maintained by Google
- Used for analytics learning and dashboard development

---

## 3. Key Events (Conversions)

The dataset already includes standard ecommerce events such as:

- view_item
- add_to_cart
- begin_checkout
- purchase

These events are used in GA4 as conversion actions when marked accordingly.

---

## 4. Metrics Used in Analysis

The following GA4 metrics were used in Looker Studio:

- Users
- New Users
- Sessions
- Views
- Engagement metrics (time / engagement rate)
- Conversions (key events)
- Revenue (ecommerce transactions)
- Cost-related metrics (if available via ads integration)

---

## 5. Dimensions Used

Key dimensions used in reporting:

- Source / Medium
- Default Channel Group
- Campaign
- Landing Page
- Device Category
- New vs Returning Users

---

## 6. Looker Studio Connection

The GA4 demo property was connected to Looker Studio using the native GA4 connector:

Steps:
1. Open Looker Studio
2. Create new report
3. Select Google Analytics connector
4. Choose Google Merchandise Store (GA4 Demo Property)
5. Build dashboards using selected metrics and dimensions
