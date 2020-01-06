# Backup SLA:

## Coverage:
* Wordpress database only
* Bind configuration
## RPO:
* When nightly backup fails an incident will be raised - recovery time is up to 1h
## Versioning:
* Three latest versions are stored in backup server
## Retention:
* Retention is implemented by having three latest versions in central backup storage
## Usability:
* No automatic recovery testing has been implemented
## Restoration criteria:
* After service failure has been detected by monitoring system and incident has been spawned,
it is decided by service engineer if the restoration is needed.
## RTO:
* Depending on size of data the RTO is up to 2h.
