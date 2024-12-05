## CVE Services 2.5.0 Deployed on December 4, 2024, adopts CVE Record Format v5.1.1 

This update introduces “non breaking” changes containing new features that some CNAs/Downstream users may be interested in using in the future.  (see  [CVE Record Format version 5.1.1 Release notes](https://github.com/CVEProject/cve-schema/releases/tag/v5.1.1-rc2).  This is a fully backwards compatible update (meaning that all previously published CVE Records will validate using this schema),  most users will see no  immediate operational impact as a result of this change.    This schema defines the data format for CVE Records, regardless of whether they were published before or after December 4. 

## Impact 

As a backwards compatabile release, most downstream users will see no operational impact.  All CVE Records previously validated using CVE Record Format 5.1.0 will continue to validate using CVE Record 5.1.1.   

## Guidance

Downstream User who validate CVE Records in their own infrastructure should use the new schema for validation.   Guidance for use of new (non mandatory) fields introduced in the new CVE Record format will be forthcoming. 
