# snowflake-semantic-models

Downstream repo for Project Compass. Don't edit files here directly — this
repo (optionally) receives a copy of what gets deployed to Snowflake, pushed
automatically by `ossie-semantic-contracts`'s `deploy.yml` workflow, purely
as a version-controlled record of what's live.

The actual deployment happens straight from `ossie-semantic-contracts` into
your Snowflake account (Step 10) — this repo is history/audit, not the
trigger point. Source of truth for the semantic model is the OSSIE YAML in
`ossie-semantic-contracts`.
