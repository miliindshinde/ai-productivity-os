# ⚙️ Make.com: The Visual Automation Tool for Power Users
*Last verified: March 2026. Review recommended every 90 days.*

### 1. Tool Overview
Make.com is a visual automation tool that connects your apps so they can pass information automatically — without you copying and pasting by hand. You build "scenarios" (automated workflows) by dragging and dropping app modules onto a canvas, connecting them like a flowchart. It is the Hands layer in the 3-Tool System: once a scenario is running, it works silently in the background every day. Compared to Zapier, Make.com offers a better free plan (1,000 operations/month vs. Zapier's 100 tasks), a more visual interface, and more advanced logic for free — at the cost of a slightly steeper learning curve.

### 2. Persona Use Cases
* **Student:** Automatically save every starred email from your professors or advisors as a new page in your Notion workspace — so important instructions never get buried.
* **Freelancer:** When a new client fills out your intake form, Make.com automatically creates a new row in Airtable, sends a welcome email via Gmail, and creates a project folder in Google Drive — all in one scenario.
* **Creator:** Every time you publish a new video or post, Make.com automatically logs it in your content calendar and sends a summary to your Slack — so your records stay current without manual entry.
* **Working Professional:** Get a daily digest email every morning at 8am summarizing all your unread high-priority emails — so you start the day knowing exactly what needs your attention.

### 3. Starter Scenario Ideas (Copy & Adapt)
* **Save Starred Emails to Notion:** Trigger: New starred email in Gmail → Action: Create a new Notion page with the email subject, sender, and body.
* **New Client Onboarding:** Trigger: New form submission (Typeform/Google Forms) → Actions: Add row to Airtable + Send Gmail welcome email.
* **Daily Morning Briefing:** Trigger: Every day at 7:30am → Action: Send yourself an email listing all Notion tasks due today.

### 4. Decision Matrix (2026)
| Feature | Make.com | Zapier | IFTTT | n8n |
| :--- | :--- | :--- | :--- | :--- |
| **Best For** | Power users, visual thinkers | Beginners, quick setup | Simple phone/home rules | Developers, self-hosting |
| **Free Plan** | 1,000 ops/month | 100 tasks/month | Unlimited (3 applets) | Self-hosted free |
| **Visual Builder** | Yes (drag-and-drop map) | No (step-by-step list) | No | Yes |
| **Multi-Step Flows** | Yes (free) | Paid only | Limited | Yes (free) |
| **App Integrations** | 1,500+ | 7,000+ | 700+ | 400+ |
| **Avoid If** | You want the simplest possible start | You need 7,000+ app integrations | You need business-grade power | You don't want to manage a server |

### 5. Known Failure Modes
* **Scenario Silent Failures:** If a connected app's API changes or your credentials expire, scenarios fail silently. Make.com sends an email notification, but only if you have email alerts turned on. Enable them immediately after setup.
* **Operation Count Confusion:** Every module that runs consumes one "operation." A scenario with 3 modules running 50 times uses 150 operations — easy to miscalculate on the free plan. Monitor your operation count in the dashboard.
* **The "Skipped Bundles" Trap:** If your scenario has a filter and no data passes the filter, Make.com counts those as "skipped" — but they still count toward your monthly operations on some plan tiers.
* **Testing vs. Live:** Running a scenario in "test" mode (one execution) uses the same operations as a real run. Don't over-test in production; use the scenario history to review past runs instead.

### 6. The Verification Protocol
To make sure your scenarios are running correctly:
1. **Always run once before activating:** Click "Run once" after building a new scenario. Check the execution log (the bubbles on each module) to confirm the right data flowed through.
2. **Set up error notifications:** In your profile Settings → Notifications, enable email alerts for scenario errors. This is the most important Make.com setting.
3. **Review the Operations Dashboard weekly:** Check your make.com dashboard to see how many operations each scenario uses. Kill or optimize any scenario that unexpectedly consumes large amounts.

### 7. How to Learn (Day 1 Path)
* **Step 1:** Sign up at [make.com](https://www.make.com) with your Google account. Click "Create a new scenario."
* **Step 2:** Click the "+" to add your first module. Search for Gmail, select "Watch Emails," and connect your Google account. Set the filter to "Starred emails only."
* **Step 3:** Add a second module: search for Notion, choose "Create a Page," and map the email Subject → Notion page title and Email Body → page content. Click "Run once" to test, then turn on Scheduling. You have built your first automation.

### 8. Real-World Case Study
**The Freelancer:** A freelance designer was manually copying new client inquiry emails into a spreadsheet to track follow-ups — a 10-minute task she did 5–10 times a week. She built one Make scenario: new Gmail inquiry → new Airtable row (with client name, email, project type, and date) → send herself a Slack reminder to follow up in 24 hours. She reclaimed over 40 minutes a week and her follow-up rate went from 60% to 100%.

### 9. Where It Fits in Your Workflow
* **The Full 3-Tool Stack:** Gmail/Forms (input) → Make.com (routes and transforms) → Notion/Airtable (stores and organizes).
* **The Content Pipeline:** Airtable (new row marked "Ready") → Make.com → Buffer (schedule social post) + Slack (notify team).
* **The Lead Capture Chain:** Typeform (new lead) → Make.com → Gmail (welcome email) + Airtable (new client row) + Google Drive (create project folder).
* **The Daily Briefing Chain:** Make.com (scheduled trigger at 7am) → Notion API (fetch today's tasks) → Gmail (send digest email).

### 10. Difficulty & Pricing (2026)
* **Difficulty:** Beginner to Intermediate.
* **Free:** 1,000 operations/month, unlimited scenarios, 15-minute scheduling intervals.
* **Core ($9/mo):** 10,000 operations/month, 1-minute scheduling, unlimited active scenarios.
* **Pro ($16/mo):** 10,000 operations/month, full execution history, custom variables, priority support.
* **Teams ($29/mo):** Shared team workspace, team management, advanced permissions.
*\*Pricing subject to change. Verify at make.com/en/pricing.*

### 11. Tags
#MakeCom #Automation #NoCode #Workflow #Beginner #Intermediate #AppConnector #Productivity

### 12. Review Cadence
*This guide is updated every 90 days to reflect new Make.com features and pricing changes.*
