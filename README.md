# Nxtgen Management App

Mobile-first white/blue browser-local business management demo.

## Included demo modules
- Billing and printable invoice preview
- Products and stock in/out with low-stock warnings, purchase cost and supplier fields
- Customer notes, purchase count and outstanding balance summaries
- Expense recording and estimated invoice-minus-expenses profit
- CSV export of invoices, customers, orders, expenses and category records
- Payment reminder composer with copy and WhatsApp hand-off
- Category-specific records for restaurant/hotel, clothing, medical, coaching, cafe/bakery, grocery, electronics and retail
- Rule-based Nxtgen AI Insights demo (not connected to an AI model)
- Business name and uploaded logo stored in browser-local storage

## Publish with GitHub Pages
Upload `index.html` to the repository root, commit it, then select Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Demo limitations
All records are stored in the current browser's local storage. They are not shared across devices or accounts. This is not production-ready authentication, cloud sync, payment processing, accounting, or verified GST/legal invoice software. AI insights are local rule-based summaries and do not call an AI service. WhatsApp reminders are prepared for manual review; they are not sent automatically.
