<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Proposal for Integrating Symphony Core App with Booqable at a Ski Rental Shop

**Overview**
To provide a seamless rental management experience and unify marketing, customer data, and operations, the ski rental shop will integrate Symphony Core App (SCA) as its CRM and marketing automation backbone with Booqable as its rental management system. This integration will enable automated lead capture from SCA into Booqable, real-time booking updates, follow-up campaigns, and consolidated reporting.

***

## 1. Core Components

1. Symphony Core App Account
    - Marketing automation: funnels, SMS/email campaigns, calendars
    - CRM: contact management, tags, pipelines
2. Booqable Account
    - Rental management: inventory, bookings, contracts
    - Mobile app: iPad/phone order management
    - API access: API key, webhook endpoints
3. No-Code Integration Platform
    - Preferred: Latenode (or Make.com/Zapier) to orchestrate workflows

***

## 2. High-Level Setup

1. Custom Fields \& Forms
    - Create SCA custom fields to capture rental-specific data (gear type, dates, extras)
    - Build a booking form on an SCA landing page that embeds Booqable availability widget or collects data for API submission
2. Contact Tagging \& Pipelines
    - Define rental inquiry pipeline stages (Requested, Confirmed, Picked Up, Returned)
    - Use tags/triggers to drive automated SMS/email reminders
3. Calendars \& Scheduling
    - Sync Booqable booking calendar with SCA calendars to display availability for upsells/services (e.g., lessons, demos)

***

## 3. Booqable Configuration

1. Inventory \& Pricing
    - Set up ski, boot, and accessory inventory with buffer times and seasonal pricing
    - Configure product bundles (e.g., ski package with poles and helmet)
2. Website Integration
    - Embed Booqable's date picker and product widgets into SCA-hosted pages or custom site
3. Mobile App Deployment
    - Install Booqable iOS/Android app on iPads or smartphones for counter staff
    - Grant user roles and permissions for on-floor rental management
4. API \& Webhooks
    - Generate API key in Booqable dashboard
    - Configure webhooks for booking creation, cancellation, and return events

***

## 4. Integration Workflows

Using Latenode or Make.com:

1. Lead → Rental Inquiry
    - Trigger: New SCA form submission marked "rental inquiry"
    - Action: Create customer record and draft booking in Booqable via API
2. Booking Confirmation
    - Trigger: Booqable webhook on "booking confirmed"
    - Action: Update SCA contact status, add booking details to custom fields, send confirmation SMS/email
3. Reminder Sequence
    - Trigger: Tag added for "Confirmed" stage
    - Action: Automated reminders before pickup and return via SCA campaigns
4. Post-Rental Follow-Up
    - Trigger: Booqable webhook on "booking returned"
    - Action: Tag contact as "Completed," send satisfaction survey and upsell offers

***

## 5. Why We Recommend Booqable Over Alternatives

**Booqable** stands out as the optimal choice for integration with Symphony Core App:

- **Native API \& Webhooks**: Robust REST API enables seamless two-way data sync with SCA
- **No-Code Integration Ready**: Pre-built connectors available through Latenode and Make.com
- **Mobile-First Operations**: Native iOS/Android app with barcode scanning for in-store management
- **Proven Scale**: Powers 7,500+ rental businesses with comprehensive feature set

**Alternative Considerations:**

- **Rentrax**: Solid rental management but limited API documentation and no pre-built SCA connectors, requiring custom development
- **TWICE**: Strong for circular commerce but API-first architecture demands more technical setup without established SCA integration paths

Booqable's combination of feature depth, integration readiness, and mobile capabilities makes it the most efficient path to a unified SCA-rental ecosystem.

***

## 6. Timeline \& Resources

- Week 1: System integration study, SCA form and pipeline setup
- Week 2: Booqable inventory configuration, API/webhook provisioning
- Week 3: Integration workflows in Latenode, embed widgets on SCA pages
- Week 4: Testing, staff training on mobile app, go-live

**Team:**

- Project Manager (10 hrs)
- Symphony Core App Specialist (20 hrs)
- Booqable Specialist (20 hrs)
- No-Code Developer (Latenode) (20 hrs)

***

## 7. Investment Estimate

| Item | Hours | Total |
| :-- | --: | --: |
| Requirements \& Planning | 10 | \$1,500 |
| SCA Setup (Forms, Pipelines) | 20 | \$3,000 |
| Booqable Configuration | 20 | \$3,000 |
| Integration Workflows | 20 | \$3,000 |
| Testing \& Training | 10 | \$1,500 |
| **Subtotal** |  | **\$12,000** |
| Contingency (10%) |  | \$1,200 |
| **Total Estimated Investment** |  | **\$13,200** |


***

## 8. Complimentary System Integration Study

**For Rotary Ski Customers:**
Symphony Core will conduct a comprehensive system integration study at **no charge** to analyze your current workflows, identify integration touchpoints, and develop a customized implementation roadmap.

**For Non-Rotary Ski Customers:**
This detailed system study represents a **\$500 value** and includes:

- Current system audit and workflow mapping
- Integration feasibility analysis
- Custom feature requirements assessment
- Detailed implementation timeline
- Updated proposal with precise scope and investment

**Next Steps:**
Upon completion of the system integration study, Symphony Core will provide an updated proposal that incorporates your specific operational requirements, ensuring the final integration delivers maximum value and operational efficiency.

**Recommendation:** This integration enables the ski rental shop to centralize customer communication, avoid double bookings, and streamline both marketing and operations under a single, automated ecosystem.

