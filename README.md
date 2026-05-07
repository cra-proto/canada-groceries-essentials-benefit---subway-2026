# Canada Groceries and Essentials Benefit - Subway

*description of the project*

**Timeframe** 2026-04-23 - 2026-07-30

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/canada-groceries-essentials-benefit---subway-2026](https://cra-test-arc.canada.ca/canada-groceries-essentials-benefit---subway-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-05-07

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Canada Groceries and Essentials Benefit)
    node5(Who is eligible)
    node6(How much you can get)
    node7(How to get the credit)
    node8(Payment dates)
    node9(Reasons for stopped or changed payments)
    node10(GST/HST credit)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node4 --> node6
    node4 --> node7
    node4 --> node8
    node4 --> node9
    node3 --> node10
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/child-and-family-benefits.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/canada-groceries-essentials-benefit.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/gst-hst-credit/who-eligible.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/gst-hst-credit/how-much.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/gst-hst-credit/get-credit.html" _blank
    click node8 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/gst-hst-credit/payment-dates.html" _blank
    click node9 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/gst-hst-credit/payments-stop-change.html" _blank
    click node10 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/gst-hst-credit.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9 inscope
    classDef ismoved fill:#eab308,color:#000
    class node5,node6,node7,node8,node9 ismoved
```
