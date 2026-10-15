# Nxtgen Management App — GitHub Pages

## Publish
1. Extract this ZIP.
2. Upload `index.html` and `README.md` to the root of your GitHub repository.
3. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, choose your main branch and `/ (root)`, then save.

## Upgrade included
- Cash survival estimate using owner-entered starting cash, outstanding invoices, and expenses dated within the selected planning horizon.
- Smart reorder coach based on product quantity and low-stock threshold; purchase orders are drafts only.
- Profit leak radar using recorded invoice totals minus recorded expenses, with missing-cost warnings.
- Customer comeback radar for customers whose latest recorded invoice is at least 30 days old; message drafts only.
- One-tap dated day-closing snapshot stored locally in the browser.
- Duplicate invoice warning based on same customer, date, and total; owner confirms before saving.

## Important limits
This is a standalone client-side demo. Records and closing snapshots are stored in browser local storage; there is no account login, cloud sync, server backup, paid AI API, automatic purchasing, or automatic message sending. Cash estimates assume outstanding invoices are collected during the selected horizon and are not bank balances. Estimated profit is invoice totals minus recorded expenses and excludes unrecorded costs, tax, refunds, and accounting adjustments. Review every draft before acting.
