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

---

## 7. Dashboard Structure

The dashboard is organized into three main layers:

### 1. Acquisition Layer
- Users
- Sessions
- New vs Returning Users

### 2. Engagement Layer
- Page Views
- Session Duration
- User interaction metrics

### 3. Conversion Layer
- Purchases / Conversions
- Revenue
- ROAS (if applicable)

---

## 8. Notes

- This is a demo dataset and does not represent real business data
- It is ideal for learning, portfolio building, and analytics practice
- No tracking implementation was required

---

## 9. Tools Used

- Google Analytics 4 (Google Merchandise Store Demo Account)
- Looker Studio
