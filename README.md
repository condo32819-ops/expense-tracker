# Expense Tracker
Bare-bones, offline-friendly expense tracker (COP/USD → USD totals; Food, Entertainment, Lodging, Uber, Misc). Open https://condo32819-ops.github.io/expense-tracker/ on iPhone Safari → Share → Add to Home Screen, or Chrome on Android → ⋮ → Install app. Data is saved on the phone first.

Optional sync: tap "⇅ Sync" → Create sync code on one phone, Enter sync code on the other. Data is stored at textdb.online under a random key (the code); anyone with the code can read it. Entries merge by id; deletes are tombstones.
