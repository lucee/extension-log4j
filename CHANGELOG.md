# Changelog

## 1.0.0.1-BETA

- [LDEV-6810](https://luceeserver.atlassian.net/browse/LDEV-6810) — automatic version: the version is built from `extension.version.base`, a build number and a qualifier, every push to the default branch publishes the next build (highest of git tags, Maven Central and Central snapshots + 1) to Maven Central and as a GitHub release, and a manual run can publish an ALPHA, BETA, RC, SNAPSHOT or final build. 1.0.0.0-BETA was already on Maven Central, so the first automatic version is 1.0.0.1-BETA

## 1.0.0.0-BETA

- [LDEV-6626](https://luceeserver.atlassian.net/browse/LDEV-6626) — first BETA, published to Maven Central and as a GitHub pre-release with the .lex files, tested with the Lucee 9 versions from `LUCEE_TEST_VERSIONS_9`

## 1.0.0.0-ALPHA

- [LDEV-6626](https://luceeserver.atlassian.net/browse/LDEV-6626) — initial version, the Log4j based log engine moved out of the Lucee core, registered with the manifest attribute `log-engine`
