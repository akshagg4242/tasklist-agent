# Task List Agent Setup Guide

## Prerequisites

- n8n installed
- Google account
- Google Sheets

---

## Step 1 — Import Workflow

Open n8n.

Select:

Import Workflow

Choose:

workflow/tasklist-agent-workflow.json

---

## Step 2 — Configure Credentials

Set up:

- Google Sheets credentials
- Any webhook credentials (if applicable)

Save changes.

---

## Step 3 — Create Task Sheet

Create a Google Sheet.

Suggested columns:

- Task
- Status
- Priority
- Deadline
- Created At

---

## Step 4 — Connect Sheet

Update the Google Sheets node with:

- Spreadsheet ID
- Sheet Name

Save workflow.

---

## Step 5 — Test Workflow

Example Input:

Create task:
Prepare monthly inventory report
Priority: High
Deadline: 30 June

Expected Result:

A new row is added to the Google Sheet.

---

## Step 6 — Verify Execution

Open:

Executions

Confirm successful workflow execution.

---

## Troubleshooting

Google Sheets not updating:
- Verify credentials
- Verify spreadsheet permissions

Workflow not running:
- Check node configuration
- Review execution logs

---

## Status

Workflow imported and tested successfully.
