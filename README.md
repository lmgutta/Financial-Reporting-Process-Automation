# Financial Reporting & Process Automation System

**Store-by-store financial visibility for a multi-store retail business, built without an ERP**

> **[Open the live system →](https://script.google.com/macros/s/AKfycbzwI_J2uqmOLrd8OHRgPB8k0FgO0yo8UcFbDgYQBNBJE2H8YEmiSD2M4YctMBAIfy7RdQ/exec)**
>
> *All data shown is synthetic. No real customer, transaction or company data is included.*

---

## TL;DR

A multi-store retailer had POS data but no quick way to turn it into decisions. This system converts raw POS exports into six management reports that managers open from a link and filter themselves.

- **What it answers:** who owes money, which stores are growing or slipping, how much cash came in, how customers pay, and where each store is heading.
- **Who it's for:** store and regional managers, without needing access to the underlying spreadsheet.
- **How it works:** choose a report, filter by store, month, year and payment type, and read the entire business or each store separately.
- **Why it matters:** it replaces slow, manual report preparation with a repeatable process managers run themselves, while a full ERP is out of reach.

---

## Table of Contents

1. [The Problem](#the-problem)
2. [What Managers Can Do With It](#what-managers-can-do-with-it)
3. [The Six Reports](#the-six-reports)
4. [A Typical Review](#a-typical-review)
5. [What Changes](#what-changes)
6. [How the Reports Stay Trustworthy](#how-the-reports-stay-trustworthy)
7. [Screenshots](#screenshots)
8. [Try It](#try-it)
9. [Limits of This Version](#limits-of-this-version)
10. [Why a Bridge Tool](#why-a-bridge-tool)
11. [Under the Hood](#under-the-hood)
12. [Background](#background)

---

## The Problem

The business ran several retail stores on a basic POS with no central financial reporting.

Store managers could export transactions, but the questions that mattered took hours of manual work to answer:

- **Who owes us money, and how much?**
- **Which stores are growing, and which are slipping?**
- **How much cash have we actually collected?**
- **How are customers paying, and is that changing?**
- **How does this month compare with the same period before?**
- **What is likely to happen next month?**

The data was there. Getting answers meant a request to someone, a wait, and often a report that was already out of date.

---

## What Managers Can Do With It

| Manager's question | Where they find the answer |
|---|---|
| How is the business doing overall? | Financial overview |
| Who should I chase for payment? | Overdue parties |
| Is this store growing or declining? | Store trend |
| How does this store take payment? | Store performance |
| Where is our cash coming from? | Cash flow and banking |
| Are customers shifting how they pay? | Payment types |

**Self-service.** Managers open a link, choose a report and narrow it by **store, month, year and payment type**. They don't wait for anyone to build a report or need access to the underlying spreadsheet.

**Business first, then store.** Every report opens on the **entire business** and says so clearly, so nobody mistakes a company-wide figure for one store. One tick switches to each store separately.

---

## The Six Reports

### Financial Overview
*How much did we sell, how much have we collected, and how much is still owed?*
Revenue, cash received, outstanding balances, average sale size and collection rate.

### Overdue Parties
*Who do we need to chase?*
The **top 15 customers per store** with balances past their due date, largest first. Each store manager sees their own list, not a company-wide one they can't act on.

### Store Trend
*Where is each store heading?*
Six months of sales and transaction counts, plus a **projection for next month and a rolling three-month average**, drawn separately so forecasts are never mistaken for actuals.

### Store Performance
*How are customers paying at this store?*
Monthly sales split by payment type.

### Cash Flow and Banking
*Where is our money?*
Cash, bank, card, credit note and outstanding credit, month by month.

### Payment Types
*Is customer payment behaviour changing?*
Monthly sales for each payment type, store by store.

---

## A Typical Review

A regional manager's Monday morning:

1. **Financial overview.** Collection rate has dipped, so outstanding balances are growing.
2. **Overdue parties.** Filter to the store with the largest balance. The top customers are listed, so the follow-up calls are clear.
3. **Store trend.** The same store's sales are flat and its projection points down, which is worth a conversation.
4. **Payment types.** Credit sales at that store have risen against cash, and that explains the collection problem.

Four views. No spreadsheet manipulation, no request to anyone.

---

## What Changes

The reporting process is the same in spirit, but it takes fewer steps.

| | **Previously** | **Now** |
|---|---|---|
| **Getting a report** | Prepared by request from a POS export | Available on demand from a link |
| **Following up on a question** | Often needs a new pass through the data | Change a filter |
| **Finding overdue customers** | Cross-referenced by hand | Listed and ranked by store |
| **Comparing periods** | Rebuilt for each review | Rolling 12-month view |
| **Looking ahead** | Judgement from experience | Judgement backed by a projection |
| **Adding a store or month** | Formulas and charts adjusted by hand | Included automatically |

The system doesn't replace management judgement. It removes the preparation work that came before it.

---

## How the Reports Stay Trustworthy

A reporting system is only useful if managers trust the numbers, so the rules are deliberately simple and consistent.

- **One definition everywhere.** Payment type, month and year are worked out once, so every report agrees with every other.
- **Bad rows are counted, not hidden.** Any record missing a store, date or payment type is excluded from every report, and the home page shows how many were left out.
- **Overdue means overdue.** Only balances whose due date has already passed are counted.
- **Months stay in order.** Reports follow the actual transaction date, so months never appear alphabetically (April, August, December, February…).
- **Exact filters.** Choosing "Credit" shows Credit and nothing else.
- **Rolling 12 months.** Charts stay readable as the business grows.

---

## Screenshots
<img width="2880" height="1460" alt="image" src="https://github.com/user-attachments/assets/97b40690-697e-402e-84ec-2077460f68bd" />
<img width="2486" height="898" alt="image" src="https://github.com/user-attachments/assets/b6792ab8-530b-476e-9400-a6e6f298de66" />
<img width="2484" height="1400" alt="image" src="https://github.com/user-attachments/assets/1bdd43d9-e653-415b-9c4e-87f39878094f" />
<img width="2482" height="1394" alt="image" src="https://github.com/user-attachments/assets/48c87ebb-6fed-4955-930b-04d6b5e216ed" />
<img width="2484" height="1404" alt="image" src="https://github.com/user-attachments/assets/d621cc09-f432-419b-9973-d27353978fba" />
<img width="2486" height="1024" alt="image" src="https://github.com/user-attachments/assets/0c873ad3-f013-476e-9334-1c01c9ace49f" />
<img width="2468" height="1028" alt="image" src="https://github.com/user-attachments/assets/39243cfa-4caf-43f6-b4f6-8bc752d99b1c" />

---

## Try It

The published version uses synthetic data.

1. **[Open the system →](https://script.google.com/macros/s/AKfycbzwI_J2uqmOLrd8OHRgPB8k0FgO0yo8UcFbDgYQBNBJE2H8YEmiSD2M4YctMBAIfy7RdQ/exec)**
2. Choose **Generate random data** and pick the number of stores, months and transactions.
3. Open any report and try the filters.
4. Tick **Show each store separately** to compare stores.

In real use, managers choose **Import POS data** and paste an export. Existing invoices are updated and new ones added, so re-importing never creates duplicates.

---

## Limits of This Version

- **Synthetic data only.** No real business information is included.
- **A bridge, not an ERP.** It gives useful visibility now. It isn't designed to replace an integrated financial platform at scale.
- **Larger data loads more slowly.** It suits a growing multi-store business, not unlimited volume.
- **Open access.** Anyone with the link can view it. Add access controls before using real business data.
- **Dates are read as day/month/year.**

---

## Why a Bridge Tool

Many growing businesses wait years for an ERP they can't yet afford. In the meantime, decisions are made on gut feel or on reports that arrive too late.

This system takes the opposite approach. It provides useful visibility **today**, on tools the business already has, and it keeps the data structure and reporting logic organised so the business can move to a fuller system **later** without starting over.

> **The aim is not to build a dashboard. It is to replace a slow, manual reporting habit with a repeatable process that managers run themselves.**

---

## Under the Hood

A short note for the curious. The system runs as a web page on Google Sheets and Google Apps Script. The spreadsheet holds only the transaction data, and all filtering, calculation and charting happens in the page. Free, familiar tools mean the business owns and understands what it runs on.

---

## Background

Built independently after spotting a financial and operational reporting gap while working in operations at a multi-store retail business.

The published version was rebuilt on synthetic data to show the process design and reporting approach without exposing any proprietary information.
