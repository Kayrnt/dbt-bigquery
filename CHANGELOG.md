# dbt-bigquery Changelog

- This file provides a full account of all changes to `dbt-bigquery`.
- Changes are listed under the (pre)release in which they first appear. Subsequent releases include changes from previous releases.
- "Breaking changes" listed under a version may require action from end users or external maintainers when upgrading to that version.
- Do not edit this file directly. This file is auto-generated using [changie](https://github.com/miniscruff/changie). For details on how to document a change, see [the contributing guide](https://github.com/dbt-labs/dbt-bigquery/blob/main/CONTRIBUTING.md#adding-changelog-entry)

## dbt-bigquery 1.3.0-b1 - August 04, 2022
### Features
- Implement `create_schema` via SQL, instead of Python method, allowing users to override if desired. drop_schema remains a Python method for the time being.  ([#182](https://github.com/dbt-labs/dbt-bigquery/issues/182), [#183](https://github.com/dbt-labs/dbt-bigquery/pull/183))
- Added table and incrementail materializations for python models via DataProc. ([#209](https://github.com/dbt-labs/dbt-bigquery/issues/209), [#226](https://github.com/dbt-labs/dbt-bigquery/pull/226))
### Under the Hood
- Implement minimal changes to support dbt Core incremental materialization refactor. ([#232](https://github.com/dbt-labs/dbt-bigquery/issues/232), [#223](https://github.com/dbt-labs/dbt-bigquery/pull/223))

## Previous Releases
For information on prior major and minor releases, see their changelogs:
- [1.2](https://github.com/dbt-labs/dbt-bigquery/blob/1.2.latest/CHANGELOG.md)
- [1.1](https://github.com/dbt-labs/dbt-bigquery/blob/1.1.latest/CHANGELOG.md)
- [1.0](https://github.com/dbt-labs/dbt-bigquery/blob/1.0.latest/CHANGELOG.md)
