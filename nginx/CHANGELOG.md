# CHANGELOG - nginx

## 3.12.0 / 2021-04-19

* [Added] Add runtime configuration validation. See [#8962](https://github.com/DataDog/integrations-core/pull/8962).

## 3.11.2 / 2021-03-07 / Agent 7.27.0

* [Fixed] Rename config spec example consumer option `default` to `display_default`. See [#8593](https://github.com/DataDog/integrations-core/pull/8593).
* [Fixed] Bump minimum base package version. See [#8443](https://github.com/DataDog/integrations-core/pull/8443).

## 3.11.1 / 2021-01-26 / Agent 7.26.0

* [Fixed] Lower log level for version metadata submission. See [#8448](https://github.com/DataDog/integrations-core/pull/8448).

## 3.11.0 / 2021-01-25

* [Added] Add support for nginx API v3. See [#8392](https://github.com/DataDog/integrations-core/pull/8392).

## 3.10.1 / 2020-11-16 / Agent 7.25.0

* [Fixed] Fix version metadata collection. See [#7972](https://github.com/DataDog/integrations-core/pull/7972).

## 3.10.0 / 2020-10-31 / Agent 7.24.0

* [Added] Add ability to dynamically get authentication information. See [#7660](https://github.com/DataDog/integrations-core/pull/7660).
* [Added] [doc] Add encoding in log config sample. See [#7708](https://github.com/DataDog/integrations-core/pull/7708).

## 3.9.0 / 2020-09-21 / Agent 7.23.0

* [Added] Add RequestsWrapper option to support UTF-8 for basic auth. See [#7441](https://github.com/DataDog/integrations-core/pull/7441).
* [Added] Option to disable stream api checking in Nginx Plus. See [#7241](https://github.com/DataDog/integrations-core/pull/7241). Thanks [szibis](https://github.com/szibis).
* [Fixed] Update proxy section in conf.yaml. See [#7336](https://github.com/DataDog/integrations-core/pull/7336).

## 3.8.1 / 2020-08-10 / Agent 7.22.0

* [Fixed] Update logs config service field to optional. See [#7209](https://github.com/DataDog/integrations-core/pull/7209).
* [Fixed] DOCS-838 Template wording. See [#7038](https://github.com/DataDog/integrations-core/pull/7038).
* [Fixed] Update ntlm_domain example. See [#7118](https://github.com/DataDog/integrations-core/pull/7118).

## 3.8.0 / 2020-06-29 / Agent 7.21.0

* [Added] Add note about warning concurrency. See [#6967](https://github.com/DataDog/integrations-core/pull/6967).
* [Added] Add config specs. See [#6797](https://github.com/DataDog/integrations-core/pull/6797).
* [Fixed] Fix template specs typos. See [#6912](https://github.com/DataDog/integrations-core/pull/6912).

## 3.7.0 / 2020-05-17 / Agent 7.20.0

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 3.6.1 / 2020-04-04 / Agent 7.19.0

* [Fixed] Remove logs sourcecategory. See [#6121](https://github.com/DataDog/integrations-core/pull/6121).

## 3.6.0 / 2020-01-13 / Agent 7.17.0

* [Added] Use lazy logging format. See [#5398](https://github.com/DataDog/integrations-core/pull/5398).
* [Added] Use lazy logging format. See [#5377](https://github.com/DataDog/integrations-core/pull/5377).
* [Fixed] Handle missing version. See [#5250](https://github.com/DataDog/integrations-core/pull/5250).

## 3.5.0 / 2019-12-02 / Agent 7.16.0

* [Added] Submit version metadata. See [#4736](https://github.com/DataDog/integrations-core/pull/4736).

## 3.4.0 / 2019-10-11 / Agent 6.15.0

* [Added] Add option to override KRB5CCNAME env var. See [#4578](https://github.com/DataDog/integrations-core/pull/4578).

## 3.3.0 / 2019-08-24 / Agent 6.14.0

* [Added] Add requests wrapper to Nginx. See [#4268](https://github.com/DataDog/integrations-core/pull/4268).

## 3.2.0 / 2019-05-14 / Agent 6.12.0

* [Added] Simplify JSON flattening for timestamps and bool. See [#3648](https://github.com/DataDog/integrations-core/pull/3648). Thanks [jd](https://github.com/jd).
* [Added] Adhere to code style. See [#3545](https://github.com/DataDog/integrations-core/pull/3545).

## 3.1.0 / 2019-01-04 / Agent 6.9.0

* [Added] Support Python 3. See [#2716][1].

## 3.0.0 / 2018-09-04 / Agent 6.5.0

* [Changed] Send correct count values for NGINX ever increasing counters. See [#2041][2].
* [Fixed] Add data files to the wheel package. See [#1727][3].

## 2.2.0 / 2018-06-04

* [Changed] Log warning, not exception, when trying to collect stream metrics. See [#1536][4].
* [Added] Add support for VTS module. See [#1295][5]. Thanks [mattjbray][6]

## 2.1.0 / 2018-05-11

* [FEATURE] Add custom tag support to service checks.

## 2.0.0 / 2018-03-23

* [IMPROVEMENT] Better process status output for good metric names. Breaking if using the badly named metrics in app. See [#1053][7]

## 1.2.0 / 2018-02-13

* [IMPROVEMENT] Make the check compatible with the new Plus API. [#1013][8]
* [DOC] Adding configuration for log collection in `conf.yaml`
* [FEATURE] allows the bypassing of proxy settings. See [#1051][9].

## 1.1.0 / 2017-07-18

* [BUGFIX] adds duplicate nginx.upstream.peers.response.*xx_count metrics with type count. [#559][10]

## 1.0.0 / 2017-03-22

* [FEATURE] adds nginx integration.

<!--- The following link definition list is generated by PimpMyChangelog --->
[1]: https://github.com/DataDog/integrations-core/pull/2716
[2]: https://github.com/DataDog/integrations-core/pull/2041
[3]: https://github.com/DataDog/integrations-core/pull/1727
[4]: https://github.com/DataDog/integrations-core/pull/1536
[5]: https://github.com/DataDog/integrations-core/pull/1295
[6]: https://github.com/mattjbray
[7]: https://github.com/DataDog/integrations-core/issues/1053
[8]: https://github.com/DataDog/integrations-core/issues/1013
[9]: https://github.com/DataDog/integrations-core/pull/1051
[10]: https://github.com/DataDog/integrations-core/issues/559
