# dss-ledger

Feedback ledger for the Alpha data source skills. Each skill wraps one data source in an honesty layer (dictionary + enablement + a public front door) so a cold agent can build real business cases against the wire. The four skills are **rebl3**, **red2**, **aerie**, and **redshift**. Their front doors live at `https://data-source-skills.vercel.app/{rebl3,red2,aerie,redshift}/skill`. File defects and asks here as issues, one label per skill. Standing rule: issue bodies carry field **names** never data **values** — describe the shape of the problem, never paste a person-identifying record. Reports filed here may graduate into the skills' cold-agent eval cases.

## Filing

Use **New issue** and pick the form for your source (rebl3, red2, aerie, redshift) or the cross-system form for seam items. Each form auto-applies its source label and a `[source]` title prefix, so nothing lands unlabeled. Freeform (blank) issues are allowed too — if you file one, add the source label yourself so the right monitor sees it.

## Monitors

Each source is a clean filter axis — the label is the thread key. Subscribe to one source by its label filter; every label view also has an Atom feed (append `.atom` to the search URL) for subscription.

- **rebl3** — [open issues](https://github.com/trilogy-group/dss-ledger/issues?q=is:open+label:rebl3) · `gh issue list -R trilogy-group/dss-ledger --label rebl3 --state open`
- **red2** — [open issues](https://github.com/trilogy-group/dss-ledger/issues?q=is:open+label:red2) · `gh issue list -R trilogy-group/dss-ledger --label red2 --state open`
- **aerie** — [open issues](https://github.com/trilogy-group/dss-ledger/issues?q=is:open+label:aerie) · `gh issue list -R trilogy-group/dss-ledger --label aerie --state open`
- **redshift** — [open issues](https://github.com/trilogy-group/dss-ledger/issues?q=is:open+label:redshift) · `gh issue list -R trilogy-group/dss-ledger --label redshift --state open`
- **cross-system** — [open issues](https://github.com/trilogy-group/dss-ledger/issues?q=is:open+label:feedback) · `gh issue list -R trilogy-group/dss-ledger --label feedback --state open`
