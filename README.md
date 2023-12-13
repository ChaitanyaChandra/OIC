# OIC

### Integrations

* App driven orchestration
    * triggers based on event

* Scheduled orchestration
    * triggers based on schedule

* Triggers
    * inbound to the integration

* Invoke
    * outbound to the integration

> Integration Attributes

* Identifiers
    * unique across all Integrations
* Versions
    * 00-000-0000 ---> major-minor-patch
* Keywords
    * keywords acts as tags.
* Package
    * grouping the integrations

* Integration file Extension
    * `file.iar`

* Business Identifiers
    * type of unique identifier can be searchable  in observability(monitoring)

> Integration logging

* production
    * 32 days retention
    * at logger level
    * upto 1000 longer iterations in loops
* audit
    * 8 days retention
    * production + payloads of the triggers + invokes
* debug
    * production + all audit + all actions logged

