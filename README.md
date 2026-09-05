# Money Manager — Final Corrected Package

## Held for Others accounting rule
When a Held for Others **Receive / Hold** entry is recorded, the amount is treated as already included in the selected Bank / Cash / Easypaisa balance. The Hold entry therefore **does not add the amount to the account again**. It only increases the Held for Others liability and reduces Mature by that amount.

When a Held for Others **Return / Release** entry is recorded, the money actually leaves the selected account, so the account balance decreases and the Held liability decreases by the same amount.

Example:
- Bank opening/current balance: Rs 730,312
- Held for Others received and already included in that balance: Rs 38,574
- Total Accounts: Rs 730,312
- Held for Others: Rs 38,574
- Mature: Rs 691,738

A normal Income entry remains a real inflow and increases the selected account.

## Calculator
- 1 2 3 / 4 5 6 / 7 8 9 / C 0 . with + − × ÷
- Backspace button is `←`
- Live calculation and result
- Works in Income, Expense, Transfer and Adjust

## Package files
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
