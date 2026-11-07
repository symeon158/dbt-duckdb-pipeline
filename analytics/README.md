# analytics

The dbt project for this pipeline. See the [main README](../README.md) for setup, how to run it, and the full data catalog of sources, models, columns and tests.

Run dbt commands from this folder, since the database and parquet paths in the profile and `sources.yml` are relative to it:

```bash
uv run dbt build
```
