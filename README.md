# n8n Portfolio

## Week 1 — Foundations

### Workflow 1 — HTTP Request + Batching
What it does : fetches 10 users from an API and processes them in batches of 2
Nodes used : Manual Trigger, HTTP Request, Loop Over Items, Edit Fields

### Workflow 2 — Webhook Router
What it does : receives events and routes them to 3 different branches
Nodes used : Webhook, If, Edit Fields

### Workflow 3 — Error Handling
What it does : detects API failures and alerts with the error type
Nodes used : Manual Trigger, HTTP Request, If, Edit Fields
