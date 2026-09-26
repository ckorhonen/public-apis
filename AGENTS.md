# Repository agent guide

## Repository workflow and completion

This curated API table has Python validators under `scripts/`. Follow `CONTRIBUTING.md` for eligibility, wording, and API/Auth/HTTPS/CORS/Postman fields. Install `scripts/requirements.txt` into a disposable environment. CI runs `python scripts/validate/format.py README.md` and `python scripts/validate/links.py README.md --only_duplicate_links_checker`.

The full links validator contacts endpoints; duplicate-only validation is narrower. Select checks for changed data and separate unreachable links from format defects. Do not create accounts, obtain credentials, invoke paid APIs, or run the PR helper as editorial validation. There is no application build/server.

Continue the authorized change through relevant validation and repair of failures it causes; preserve unrelated work. Report checks actually run, commands only inspected, and exact missing prerequisites. Ask only when a material decision, missing authorization, or required input blocks progress; continue independent reversible work. Existing mandatory contribution and validation gates still apply.
