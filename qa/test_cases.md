## CASE-UI-001 — Login success
Steps: open -> type standard_user/secret_sauce -> Login
Expected: page title "Products".

## CASE-UI-002 — Locked out user blocked
Steps: login with locked_out_user/secret_sauce
Expected: error contains "locked out".
