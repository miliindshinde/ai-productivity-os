# ⚙️ Make.com

**Category:** Automation (Connecting Your Apps)
**Free Plan:** Yes — 1,000 operations per month
**Website:** [make.com](https://www.make.com)

---

## What Is Make.com?

Make.com is a visual automation tool that connects your apps so they can talk to each other automatically — without you having to copy and paste anything by hand.

It is the **Hands** layer in the 3-Tool System. Once you set up a Make "scenario" (their word for an automation), it runs in the background every day without you touching it.

**Simple example:** Every time you star an email in Gmail, Make automatically saves a summary of that email into a new row in your Notion database.

---

## Who Should Use It?

- Anyone doing repetitive copy-paste work between apps
- Students and freelancers who want to save time on admin tasks
- People who have tried Zapier and want more power and flexibility (Make is more visual and has a better free plan)

---

## Make.com vs. Zapier

| | Make.com | Zapier |
|---|---|---|
| Free plan | 1,000 ops/month | 100 tasks/month |
| Visual builder | Yes (drag-and-drop map) | No (step-by-step list) |
| Learning curve | Slightly steeper | Easier for beginners |
| Advanced logic | Yes (filters, routers, loops) | Limited on free plan |
| Best for | Power users and visual thinkers | Beginners who want quick wins |

**Verdict:** Start with Make.com if you want the best free plan and more flexibility. Use Zapier if you just want something working in 10 minutes.

---

## Key Concepts

### Scenarios
A "scenario" is a single automation workflow. Each scenario has a **trigger** (the event that starts it) and one or more **actions** (what happens as a result).

### Modules
Modules are the individual steps inside a scenario. Each module is a connection to an app (Gmail, Notion, Google Sheets, Slack, etc.).

### Operations
Every time a module runs, it uses one "operation." The free plan gives you 1,000 operations per month — enough for 30+ daily automations.

### Scheduling
Scenarios can run immediately when a trigger fires (like a new email arriving) or on a schedule (every morning at 8am, every hour, etc.).

---

## 3 Starter Automations to Build First

### Automation 1: Save Starred Emails to Notion
**Trigger:** A new email is starred in Gmail
**Action:** Create a new page in your Notion "Inbox" database with the email subject, sender, and body

**Why it's useful:** You will never lose an important email again. Your Notion becomes the single place to act on things.

### Automation 2: Save AI Outputs Automatically
**Trigger:** You fill out a Google Form with a question and an AI answer
**Action:** The form response is saved as a new row in a Notion table

**Why it's useful:** Build a personal library of your best AI prompts and answers over time.

### Automation 3: Daily Briefing to Yourself
**Trigger:** Every morning at 7am
**Action:** Make sends you an email (or a Slack message) with a summary of your tasks due today from Notion

**Why it's useful:** You get a clear daily agenda without having to open Notion every morning.

---

## How to Build Your First Scenario (Step by Step)

**Step 1:** Sign up at [make.com](https://www.make.com) — use your Google account for speed.

**Step 2:** Click **"Create a new scenario"** from your dashboard.

**Step 3:** Click the **"+"** button to add your first module. Search for the app you want to watch (e.g., Gmail).

**Step 4:** Choose your **trigger** event (e.g., "Watch Emails" → filter for starred emails).

**Step 5:** Connect your Google account when prompted and grant permissions.

**Step 6:** Add a second module by clicking the small circle after the first one. Search for Notion.

**Step 7:** Choose the **action** (e.g., "Create a Page") and map the email fields (subject → page title, body → page content).

**Step 8:** Click **"Run once"** to test. If it works, click **"Scheduling"** to turn it on permanently.

---

## Tips for Getting More Out of Your Free Plan

- Use **filters** to make automations selective (only run if the email contains the word "invoice," for example)
- Chain multiple actions in one scenario instead of building separate scenarios — this saves operations
- Set scenarios to run every 15 minutes instead of instantly to use fewer operations
- Archive or delete old scenarios you no longer use

---

## Common Mistakes to Avoid

- **Building complex automations first.** Start with a simple two-step scenario and get it working before adding more steps.
- **Skipping the test run.** Always click "Run once" before activating a scenario. It shows you exactly what data will flow through.
- **Connecting the wrong account.** Make sure you authorize the correct Google/Notion account, especially if you have multiple.
- **Forgetting to turn it on.** After testing, flip the scheduling toggle to **ON** — otherwise the scenario never runs automatically.

---

## Connecting to the Full 3-Tool Stack

Make.com is the bridge between your AI Brain (Gemini/Claude/ChatGPT) and your Memory (Notion):

```
[Your Input or Trigger] → [Make.com] → [Notion]
       (Gmail, Forms,         (routes and      (stores, organizes,
        Calendars, etc.)       transforms)       retrieves)
```

See the [Notion guide](notion.md) for how to set up your Notion workspace to receive automated data.
