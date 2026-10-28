**Reports covered: 33** (of the 412 unique reports merged into #4471)

Tenants on the booking-v3 form (alder.physio, copper.studio, pale.harbour) are day-first, but the form prints `MM/DD/YYYY` under the date field. People type what the hint says, month first, and the form reads it their way. This is a different bug from the parser: fixing the parser does not fix it.

- First seen 2026-04-17, last seen 2026-09-22
- Intake tagged 15 of these 33 as `parser`
- #4471 closed this as WON'T FIX ("booking-v3 form retired"). These three tenants are still on booking-v3 in the tenant directory, so the claim needs checking.
