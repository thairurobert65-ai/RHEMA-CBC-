# Rhema CBC Revision: offline app edition

- `www/` is the app (works offline once installed). Free questions: 5 per subject. Premium is unlocked with a code tied to the learner's phone.
- `codegen.html` is YOUR private code maker. Never put it online or share it. It contains the secret that makes codes valid.
- Before using: open `www/index.html` in a text editor and change `wa:'2547XXXXXXXX'` to your WhatsApp number (format 2547..., no plus sign).

## How a sale works
1. Learner pays Paybill 400200, account 01102499700001.
2. In the app they type the M-Pesa receipt code and tap "Send on WhatsApp". You receive their receipt code and 6-character ID.
3. Check the receipt and amount against your Equity statement.
4. Open `codegen.html`, enter the ID, choose the plan, tap Make code, and send the message back.
5. The learner enters the code under "Got your access code?". It works only on that phone, and expires after 30 or 90 days.

If a learner clears the app data or changes phones, they get a new ID and need a new code.
