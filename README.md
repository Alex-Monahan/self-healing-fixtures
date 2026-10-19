# self-healing-fixtures

Upstream fixtures for the [self-healing pipelines](https://github.com/motherduckdb/labs/tree/heal/dev/projects/self-healing-pipelines)
experiment in `motherduckdb/labs`. The P3 pipeline reads this repo's issues through the GitHub REST
API and its CSV files from `raw.githubusercontent.com`. Test scenarios switch between file variants
to simulate upstream changes (a renamed column, re-sent records, null keys).

Issues here are test data. Some are deliberately hostile (prompt-injection text) and are treated as
data by the pipeline, never as instructions.
