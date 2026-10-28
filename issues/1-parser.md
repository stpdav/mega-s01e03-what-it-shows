**Reports covered: 374** (of the 412 unique reports merged into #4471)

The shared parser reads every date month first. Day-first tenants (11 of them: harbour.dental, kettle.books, lantern.row, long.table, morrow.tax, nine.lanterns, ridge.clinic, stone.and.sons, plus alder.physio, copper.studio and pale.harbour when the report did not come through a form) see months and days flipped, e.g. "4 March turned into 3 April".

- First seen 2026-04-01, last seen 2026-10-04
- Cause is found from the tenant (locale), not from intake's browser guess
- #4471 closed this as FIXED (`fix(dates): parse dd/mm for eu locales`)
