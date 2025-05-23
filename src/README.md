# AI Integration to add memos to uncategorized YNAB Transactions


1. Pull uncategorized transaction data from YNAB API
2. Ask AI to write quick memo on its opinin on which budget category to take from, structure response as json
3. Check json output, POST to YNAB API to update memos