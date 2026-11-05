# M.Express

M.Express gives clients immediate access to their refundable holding deposits, charging a 5% fee, and recovers the full amount from the company holding the deposit once it's released. This repo covers the extension of that model to vehicle hire deposits — bookings with Avis, Europcar, Hertz and similar asset partners.

## Contents

- **[`docs/`](docs)** — the policy and compliance framework:
  - `MExpress_South_Africa_Requirements_and_Compliance.pdf` — regulatory checklist (CIPC, NCR, FICA, POPIA, SARB, SARS)
  - `MExpress_Deposit_Payout_and_Reimbursement_System.pdf` — the base deposit payout and reimbursement model
  - `MExpress_Car_Hire_Partner_Integration.pdf` — processes and policies for integrating with vehicle hire partners, prepared by TGW Group
- **[`index.html`](index.html)** — an interactive demo of a single claim moving between the three parties (car hire partner, M.Express, client) through submission, payout, vehicle return, deductions and reimbursement.

## Running the demo

Open `index.html` directly in a browser, or, once GitHub Pages is enabled on this repo (Settings → Pages → Deploy from a branch → `main` / `/ (root)`), it will be live at:

```
https://tgwgroup-design.github.io/MExpress/
```
