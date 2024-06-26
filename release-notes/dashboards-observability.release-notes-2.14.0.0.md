## Version 2.14.0 Release Notes

Compatible with OpenSearch and OpenSearch Dashboards version 2.14.0

### Features
* Add skipping index and saved queries for WAF integration ([#1750](https://github.com/opensearch-project/dashboards-observability/pull/1750))
* Add multi-checkpoint support to integrations ([#1742](https://github.com/opensearch-project/dashboards-observability/pull/1742))
* Enhance Explorer to use describe command ([#1736](https://github.com/opensearch-project/dashboards-observability/pull/1736))
* update vpc flow with flint-s3 based DDL assets and dashboard ([#1721](https://github.com/opensearch-project/dashboards-observability/pull/1721))
* Add default refresh interval for all the integrations and correct the version on `main` ([#1717](https://github.com/opensearch-project/dashboards-observability/pull/1717))
* More example queries for S3-based integrations ([#1714](https://github.com/opensearch-project/dashboards-observability/pull/1714))
* Implement saved query substitution for S3 integrations ([#1711](https://github.com/opensearch-project/dashboards-observability/pull/1711))
* update cloud trail integration with flint-s3 based DDL assets and das… ([#1707](https://github.com/opensearch-project/dashboards-observability/pull/1707))
* [Integrations] Add integration of S3 Access log ([#1697](https://github.com/opensearch-project/dashboards-observability/pull/1697))
* Update pattern for multiple mview suffixes ([#1693](https://github.com/opensearch-project/dashboards-observability/pull/1693))
* HAProxy Flint Integration ([#1692](https://github.com/opensearch-project/dashboards-observability/pull/1692))
* Add CloudFront queries for integrations and integration table bug fix ([#1687](https://github.com/opensearch-project/dashboards-observability/pull/1687))
* Add integration of WAF log ([#1685](https://github.com/opensearch-project/dashboards-observability/pull/1685))
* Improve on ELB integration assets ([#1682](https://github.com/opensearch-project/dashboards-observability/pull/1682))
* Add Flint queries for Apache Access integration ([#1681](https://github.com/opensearch-project/dashboards-observability/pull/1681))
* Add observability-search link rendering for integrations ([#1642](https://github.com/opensearch-project/dashboards-observability/pull/1642))
* Flint Datasource Cypress testing for tables ([#1610](https://github.com/opensearch-project/dashboards-observability/pull/1610))
* Update loading state for tables fields in create acceleration flyout ([#1576](https://github.com/opensearch-project/dashboards-observability/pull/1576))
* add info callout for s3 datasources ([#1575](https://github.com/opensearch-project/dashboards-observability/pull/1575))
* Flint datasource 2.13 bug bash fix ([#1574](https://github.com/opensearch-project/dashboards-observability/pull/1574))
* Fixed small bugs in explorer ([#1559](https://github.com/opensearch-project/dashboards-observability/pull/1559))

### Bug Fixes
* update live mv table name ([#1725](https://github.com/opensearch-project/dashboards-observability/pull/1725))
* changes loading configuration for Explorer default ([#1720](https://github.com/opensearch-project/dashboards-observability/pull/1720))
* Remove auto refresh option in create acceleration flyout ([#1716](https://github.com/opensearch-project/dashboards-observability/pull/1716))
* update mv name to include double "_" ([#1712](https://github.com/opensearch-project/dashboards-observability/pull/1712))
* Bugfix: Use workflows option in selection ([#1704](https://github.com/opensearch-project/dashboards-observability/pull/1704))
* fix small issues within explorer search bar and sample query ([#1683](https://github.com/opensearch-project/dashboards-observability/pull/1683))
* (query assist) update styles for callout and combo box ([#1675](https://github.com/opensearch-project/dashboards-observability/pull/1675))
* Convert cache to session storage ([#1669](https://github.com/opensearch-project/dashboards-observability/pull/1669))
* Correctly Utilize Cache in Tables Flyout ([#1662](https://github.com/opensearch-project/dashboards-observability/pull/1662))
* Bug Fix for Undefined Association ([#1658](https://github.com/opensearch-project/dashboards-observability/pull/1658))
* prevent logged out datasources call ([#1653](https://github.com/opensearch-project/dashboards-observability/pull/1653))
* Update intercept to check logout request ([#1650](https://github.com/opensearch-project/dashboards-observability/pull/1650))
* Fix integration flyout successes ([#1647](https://github.com/opensearch-project/dashboards-observability/pull/1647))
* Clear callout in query assist ([#1646](https://github.com/opensearch-project/dashboards-observability/pull/1646))
* [BUGFIX] Fix integration data reading double escape ([#1644](https://github.com/opensearch-project/dashboards-observability/pull/1644))
* Clear cache on any 401 response errors ([#1634](https://github.com/opensearch-project/dashboards-observability/pull/1634))
* Updating catch for guardrails ([#1631](https://github.com/opensearch-project/dashboards-observability/pull/1631))
* Updating snapshot to fix build ([#1627](https://github.com/opensearch-project/dashboards-observability/pull/1627))
* Bug fixes and UI updates for datasources ([#1618](https://github.com/opensearch-project/dashboards-observability/pull/1618))
* Create acceleration flyout bug fixes ([#1617](https://github.com/opensearch-project/dashboards-observability/pull/1617))
* Fix DSL router, update UI for query assist ([#1612](https://github.com/opensearch-project/dashboards-observability/pull/1612))
* Fixed bugs in explorer redirection ([#1609](https://github.com/opensearch-project/dashboards-observability/pull/1609))
* Sanitize create acceleration queries and direct queries ([#1605](https://github.com/opensearch-project/dashboards-observability/pull/1605))
* Fix create acceleration bugs ([#1599](https://github.com/opensearch-project/dashboards-observability/pull/1599))
* Updating usePolling to cleanup after unmount ([#1598](https://github.com/opensearch-project/dashboards-observability/pull/1598))
* Enable integration install flyout for other install buttons ([#1596](https://github.com/opensearch-project/dashboards-observability/pull/1596))
* Disable close button when integration is being installed ([#1591](https://github.com/opensearch-project/dashboards-observability/pull/1591))

### Infrastructure
* Add workflow to build and install binary to catch run time issues ([#1467](https://github.com/opensearch-project/dashboards-observability/pull/1467))

### Documentation
* Add basic developer docs for integration setup and config ([#1613](https://github.com/opensearch-project/dashboards-observability/pull/1613))
* Change query access messaging ([#1224](https://github.com/opensearch-project/dashboards-observability/pull/1224))

### Maintenance
* Refactor integrations setup for easier separation of different setup options ([#1741](https://github.com/opensearch-project/dashboards-observability/pull/1741))
* Reformatting integration queries ([#1726](https://github.com/opensearch-project/dashboards-observability/pull/1726))
* Increment version to 2.14.0.0 ([#1673](https://github.com/opensearch-project/dashboards-observability/pull/1673))
* Enable query assist by default ([#1640](https://github.com/opensearch-project/dashboards-observability/pull/1640))
* Update ag-grid dependency to 31 ([#1604](https://github.com/opensearch-project/dashboards-observability/pull/1604))
* Fix datagrid snapshots for 2.x ([#1590](https://github.com/opensearch-project/dashboards-observability/pull/1590))
