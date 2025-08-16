# PATCH v13 — Bold money only
- **Only** the money balances are bold (labels + numbers): EQUITY, CASH, BP, DAYPNL.
- No colors in trading logs (`[TOP]`, `[ENTRY]`, etc.) so the balances stand out.
- `COLOR_DAY_PNL=True` keeps dayPnL green/red **but still bold**; set to `False` to remove color too.
- Keeps all logic from v12 (extended-hours entries, regular-hours exits, rate limiter, stop-dup fix, continuous loop, account summary).
