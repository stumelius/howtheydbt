# How They dbt
[![Contributions Welcome!](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

> A curated collection of publicly available resources on how data-driven organizations around the world utilize [dbt](https://www.getdbt.com/)

## Introduction

Inspired by [howtheytest](https://github.com/abhivaikar/howtheytest) and [howtheysre](https://github.com/upgundecha/howtheysre), __How They dbt__ is a curated knowledge repository of dbt best practices adopted by data-driven organizations around the world.

Many companies regularly come forward and share their best practices and techniques various public platforms like blogs, conferences & other events. These dispersed resources are gathered and curated in this repository.

### Topics

* Model organization
* Testing
* Continuous integration & running dbt in production

## Organizations & how they use dbt


<details>
  <summary>Dagster</summary>

#### Resources

* [Dagster and dbt: Better Together](https://dagster.io/blog/dagster-dbt)
* [dbt Examples](https://docs.dagster.io/examples/dbt_example)
* Identifying model deprecation and optimization candidates + exposure updates: [Good Data at Good Eggs: Using Dagster to manage the data platform](https://dagster.io/blog/good-eggs-3)
* [Orchestrating dbt with Dagster (video)](https://www.getdbt.com/coalesce/agenda/orchestrating-dbt-with-dagster)

</details>

<details>
  <summary>Fishtown Analytics</summary>

#### Resources

* [dbt Best practices](https://docs.getdbt.com/docs/guides/best-practices/)
* [How we structure our dbt projects](https://discourse.getdbt.com/t/how-we-structure-our-dbt-projects/355)
* [dbt coding conventions](https://github.com/fishtown-analytics/corp/blob/master/dbt_coding_conventions.md)
* [Your Essential dbt Project Checklist](https://discourse.getdbt.com/t/your-essential-dbt-project-checklist/1377)
* [Representing non-SQL models in a dbt DAG](https://discourse.getdbt.com/t/representing-non-sql-models-in-a-dbt-dag/2083)
* [dbt example projects](https://docs.getdbt.com/faqs/example-projects/)
* [Running dbt in Production](https://docs.getdbt.com/docs/running-a-dbt-project/running-dbt-in-production/)
* [Enabling CI in dbt Cloud](https://docs.getdbt.com/docs/dbt-cloud/using-dbt-cloud/cloud-enabling-continuous-integration-with-github/)

</details>

<details>
  <summary>GitLab</summary>

#### Resources

* [GitLab dbt docs](https://dbt.gitlabdata.com/#!/overview)
* [GitLab Data Team Handbook - dbt Guide](https://about.gitlab.com/handbook/business-ops/data-team/platform/dbt-guide/)

</details>

<details>
  <summary>Snaptravel</summary>

#### Resources

* [How to structure a data team (Coalesce 2020)](https://youtu.be/qldh7QeeLu8)

</details>

---
## Blog posts

* [Practical tips to get the best out of Data Build Tool (dbt) — Part 1](https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-building-tool-dbt-part-1-8cfa21ef97c5)
* [Practical tips to get the best out of Data Build Tool (dbt) — Part 2](https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-build-tool-dbt-part-2-a3581c76723c)
* [One analyst's guide for going from good to great](https://blog.getdbt.com/one-analysts-guide-for-going-from-good-to-great/)

---
## Ecosystem

dbt packages make up a significant portion of the dbt ecosystem and there's an existing list of packages in the [dbt hub](https://hub.getdbt.com/). This section focuses on adapters and other tools, such as CLIs and linters, related to dbt development.

### dbt adapters
Adapters that are not listed in the [list of Fishtown and community supported adapters](https://docs.getdbt.com/docs/available-adapters/):

* [dbt-athena - AWS Athena adapter](https://github.com/Tomme/dbt-athena)

### dbt tools
* [dbt-helper - A helper tool for dbt development and data warehouse management](https://github.com/mikekaminsky/dbt-helper)
* [pre-commit-dbt - Pre-commit hooks to ensure the quality of your dbt projects](https://github.com/offbi/pre-commit-dbt)
* [dbt-sugar - A tool for measuring test and documentation coverage of your dbt projects](https://github.com/bitpicky/dbt-sugar)
* [dbt-container-skeleton - Easily set up a containerized dbt developer environment](https://github.com/gnilrets/dbt-container-skeleton)
* [dbt-ipy - Run dbt commands inside a IPython session (Jupyter notebook)](https://github.com/jmriego/dbt-ipy)
* [dbt-profiler - A tool for profiling dbt relations](https://github.com/data-mie/dbt-profiler)
* [dbt-datamocktool - A simple package for unit testing dbt projects](https://github.com/mjirv/dbt-datamocktool)

### Related tools
* [SQLFluff - A SQL linter and auto-formatter](https://github.com/sqlfluff/sqlfluff)
* [dtspec - Run unit-test style tests for data transformations, includes dbt-specific CLI](https://github.com/inside-track/dtspec)


## Contributors

<a href="https://github.com/smomni/howtheydbt/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=smomni/howtheydbt" />
</a>

## Contribution

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
