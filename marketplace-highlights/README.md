# Marketplace Highlights — Ready to Upload

These 6 images are pre-cropped to Atlassian Marketplace's exact requirements for
the **Highlights** section of your app listing.

> Marketplace 解锁后（"Pending approval" 黄条消失），按以下顺序上传到
> **Manage app → Edit listing details → Highlights**。
> 每个 Highlight 需要 1 张大图 (1840×900) + 1 张裁剪图 (580×330) + 标题 + 摘要 + caption。

---

## Highlight 1 — Project Health Dashboard

| Field | Value |
|---|---|
| Big image (1840×900) | `01-project-health-1840x900.png` |
| Small image (580×330) | `01-project-health-580x330.png` |
| **Title** | `One-glance project health` |
| **Summary** | `Total · Overdue · Unassigned · Completed — every KPI your stand-up needs, on a single dark-themed scorecard.` |
| **Caption** | `Status distribution, workload summary, and severity breakdown rendered in real time from your Jira data.` |

---

## Highlight 2 — Risk Analysis · Ishikawa

| Field | Value |
|---|---|
| Big image (1840×900) | `02-risk-analysis-ishikawa-1840x900.png` |
| Small image (580×330) | `02-risk-analysis-ishikawa-580x330.png` |
| **Title** | `Boardroom-grade risk fishbone` |
| **Summary** | `Auto-categorize risk signals across People, Process, Quality, and Schedule — backed by issue patterns from your backlog.` |
| **Caption** | `Top risk contributors are surfaced explicitly so you can take action before retros reveal them the hard way.` |

---

## Highlight 3 — Releases & Activity

| Field | Value |
|---|---|
| Big image (1840×900) | `03-recent-activity-1840x900.png` |
| Small image (580×330) | `03-recent-activity-580x330.png` |
| **Title** | `Live activity & release cadence` |
| **Summary** | `Recent ticket flow, sprint scope vs completion, and 14-day issue trends — refreshed every time someone touches Jira.` |
| **Caption** | `Stay current on what just happened and where the release is heading without leaving the dashboard.` |

---

## How they were generated

All images cropped from the source screenshots in `../image/` using `sips`:

1. Resize to fit either width 1840 or height 900 (whichever crops less)
2. Center-crop to exact target size

If you need to regenerate, see the script in the project's git history.

## Source mapping

| Highlight | Source file (in `../image/`) |
|---|---|
| 01 Project Health | `dashboard1.png` (2594×1552) |
| 02 Risk Analysis  | `project-risk-ishikawa.png` (2614×1416) |
| 03 Activity       | `dashboard2.png` (2590×1618) |
