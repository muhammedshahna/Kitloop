# KitLoop (Prototype v0.1)

A campus electronics component and kit lending library. Students borrow sensors, boards and kits by the day instead of buying parts they use once.

Prepared by Mohammed Shahna (24WU0104023), B.Tech 3rd Year, Ideation and Business Model Design (Entrepreneurship Track).

## Problem and value proposition

Project students buy components they use once, then wait days for delivery. KitLoop lets them get the right part the same day, pay per use, and return it. This prototype is the first working step of the concierge pilot described in the Business Model Canvas.

## Working features

1. **Rental request with live stock check.** The student enters name, roll number, item and days. The app shows the price (rent plus refundable deposit), reduces stock on confirmation, and issues a request ID with a due date. If an item is out of stock, the request is logged as demand instead of being lost.
2. **Return and inspection tracker.** Each open rental is listed with its due date and an overdue flag. On return, the operator marks it Tested OK, Damaged or Lost. Only items that pass go back on the shelf, and the deposit refund is calculated.

A small **Demand log** tab shows the pilot metrics (rentals, distinct students, on-time and undamaged rate, loss rate, repeat renters, stock-outs) and exports a CSV. These map to the thresholds in the validation plan.

## Run it

No install needed. Open `index.html` in any browser. Data is kept in the browser's localStorage.

To host it free: push the repo to GitHub, then Settings, Pages, deploy from the `main` branch root.

## Business Model Canvas mapping

| Prototype part | BMC blocks |
| --- | --- |
| Request and stock check | Value Proposition, Channels, Customer Relationships, Revenue Streams |
| Return and inspection | Key Activities, Cost Structure, Risk Management, Workflow and Supply Chain |
| Demand log | Key Resources, Customer Retention, Prototype Maturity |

## Limits (honest status)

- Sample catalogue and prices are placeholders until interviews fix the real list.
- Single device, no login, no payment integration. UPI is collected manually at handover.
- Pilot data has not been collected yet.

## Next steps

5+ interviews, then a 2-week shelf pilot with 10+ items.
