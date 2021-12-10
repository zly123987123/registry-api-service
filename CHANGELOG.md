# Changelog

## [0.4.1](https://github.com/NASA-PDS/registry-api-service/tree/0.4.1) (2021-12-10)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.4.0...0.4.1)

**Requirements:**

- As a developer, I was to be able to use AWS Secrets Manager with registry api service [\#52](https://github.com/NASA-PDS/registry-api-service/issues/52)

**Improvements:**

- Support for node-specific routing in API paths [\#81](https://github.com/NASA-PDS/registry-api-service/issues/81)
- Add aws cost tagging and secret/parameter creation to ECS terraform script [\#78](https://github.com/NASA-PDS/registry-api-service/issues/78)

**Defects:**

- Registry API Service doesn't build anymore [\#91](https://github.com/NASA-PDS/registry-api-service/issues/91) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- service is not handling value of ES login correctly [\#87](https://github.com/NASA-PDS/registry-api-service/issues/87) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- AWS target groups created in terraform do not have intended targets [\#85](https://github.com/NASA-PDS/registry-api-service/issues/85) [[s.medium](https://github.com/NASA-PDS/registry-api-service/labels/s.medium)]

**Other closed issues:**

- Work w/ SAs to define production deployment strategy in AWS [\#22](https://github.com/NASA-PDS/registry-api-service/issues/22)

## [v0.4.0](https://github.com/NASA-PDS/registry-api-service/tree/v0.4.0) (2021-09-30)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.4.0-SNAPSHOT...v0.4.0)

**Requirements:**

- As a user, I want  to get a 404 error when I attempt to request a resource which does not exists [\#33](https://github.com/NASA-PDS/registry-api-service/issues/33)
- As a developer, I want to utilize ElasticSearch performance robustness for API response time requirements. [\#13](https://github.com/NASA-PDS/registry-api-service/issues/13)

**Defects:**

- As a paginator, I want endpoints to consistently return no results when I page to the end of results [\#69](https://github.com/NASA-PDS/registry-api-service/issues/69) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- Fix broken build per pds4+json PR merge [\#68](https://github.com/NASA-PDS/registry-api-service/issues/68) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- API unable to handle products with multiple file areas [\#62](https://github.com/NASA-PDS/registry-api-service/issues/62) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- If Elasticsearch is down on API server startup, it starts, but doesn't accept connections [\#53](https://github.com/NASA-PDS/registry-api-service/issues/53) [[s.medium](https://github.com/NASA-PDS/registry-api-service/labels/s.medium)]
- The end point /bundles/{lidvid}/products does not fully work [\#36](https://github.com/NASA-PDS/registry-api-service/issues/36) [[s.medium](https://github.com/NASA-PDS/registry-api-service/labels/s.medium)]

**Other closed issues:**

- Implement populating `hits` value in registry-api-service [\#31](https://github.com/NASA-PDS/registry-api-service/issues/31)

## [v0.4.0-SNAPSHOT](https://github.com/NASA-PDS/registry-api-service/tree/v0.4.0-SNAPSHOT) (2021-08-11)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.3.2...v0.4.0-SNAPSHOT)

## [v0.3.2](https://github.com/NASA-PDS/registry-api-service/tree/v0.3.2) (2021-07-27)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.3.1...v0.3.2)

**Defects:**

- Default / XML output format doesn't work with JDK 11 [\#54](https://github.com/NASA-PDS/registry-api-service/issues/54) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- blob is returned in product results if fields to return are not specified [\#51](https://github.com/NASA-PDS/registry-api-service/issues/51)

## [v0.3.1](https://github.com/NASA-PDS/registry-api-service/tree/v0.3.1) (2021-06-24)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.3.0...v0.3.1)

**Requirements:**

- As a user, I want to have a complete default fields \(for now at least\) [\#47](https://github.com/NASA-PDS/registry-api-service/issues/47)

## [v0.3.0](https://github.com/NASA-PDS/registry-api-service/tree/v0.3.0) (2021-06-23)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.2.0...v0.3.0)

**Requirements:**

- As a user, I want the end-point /api to redirect to the API documentation [\#39](https://github.com/NASA-PDS/registry-api-service/issues/39)
- As a SA, I want to deploy the API behind a proxy  [\#10](https://github.com/NASA-PDS/registry-api-service/issues/10)

**Defects:**

- As an API caller, I expect MD5s and file reference URLs to have real values and not the string "null" [\#43](https://github.com/NASA-PDS/registry-api-service/issues/43) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- XML and PDS4+XML Response Formats are invalid [\#27](https://github.com/NASA-PDS/registry-api-service/issues/27) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]
- error 500 on GET /collections/:lidvid:/products [\#17](https://github.com/NASA-PDS/registry-api-service/issues/17) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]

## [v0.2.0](https://github.com/NASA-PDS/registry-api-service/tree/v0.2.0) (2021-05-26)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.1.1...v0.2.0)

## [v0.1.1](https://github.com/NASA-PDS/registry-api-service/tree/v0.1.1) (2021-05-25)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.1.0...v0.1.1)

**Requirements:**

- As a node operators, I want to deploy the Registry API Service with the PDS Registry. [\#14](https://github.com/NASA-PDS/registry-api-service/issues/14)

**Defects:**

- API server crashes with OutOfMemoryError if invalid query is used [\#16](https://github.com/NASA-PDS/registry-api-service/issues/16) [[s.high](https://github.com/NASA-PDS/registry-api-service/labels/s.high)]

**Other closed issues:**

- As a developer, I don't want unused classes to stay in the code [\#28](https://github.com/NASA-PDS/registry-api-service/issues/28)
- Employ budget alerts and if possible, rate/egress limits on AWS services [\#21](https://github.com/NASA-PDS/registry-api-service/issues/21)

## [v0.1.0](https://github.com/NASA-PDS/registry-api-service/tree/v0.1.0) (2021-04-07)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.0.2...v0.1.0)

**Improvements:**

- Implement a lid resolver [\#4](https://github.com/NASA-PDS/registry-api-service/issues/4)
- implement the start/limit efficiently [\#3](https://github.com/NASA-PDS/registry-api-service/issues/3)
- Manage relationships bundle-collection-product in API [\#2](https://github.com/NASA-PDS/registry-api-service/issues/2)

## [v0.0.2](https://github.com/NASA-PDS/registry-api-service/tree/v0.0.2) (2021-02-03)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/v0.0.1...v0.0.2)

## [v0.0.1](https://github.com/NASA-PDS/registry-api-service/tree/v0.0.1) (2020-12-21)

[Full Changelog](https://github.com/NASA-PDS/registry-api-service/compare/66b22b0ede8c41921a37521433fa15a57f33513d...v0.0.1)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
