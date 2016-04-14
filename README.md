terminology
===========

openEHR reference model terminology, and artefacts for binding or using standard terminologies.

#Draft RELEASE-2.0.0-alpha

This is an initial attempt to establish a more solid baseline for terminology list governance -Feedback welcome.

Some of the [outstanding terminology SPECPRs](https://openehr.atlassian.net/browse/SPECPR-95?jql=project%20%3D%20SPECPR%20AND%20component%20%3D%20%22openEHR%20Terminology%22) have been fixed here, other fixes will be applied in later commits.

The intention is to use the Git Tag mechanism to formally label Releases e.g. RELEASE-2.0.0,using the semver.org mechanism adopted by the clinical models.

The current master is at RELEASE-1.0.0 and reflects current usage within the java-libs repository, currently the 'source-of-truth' for most implementers.

On publication, this branch will be RELEASE-2.0.0, reflecting the breaking changes in the file format and content.

##Changes from RELEASE-1.0.0

Based on java-lib terminology files - [SPECPR-25](https://openehr.atlassian.net/browse/SPECPR-25)

New directory structure  
Removed mediatypes from openEHR internal terminology, now carried as external terminology  
Added mediatypes [SPECPR-97](https://openehr.atlassian.net/browse/SPECPR-97)  
Added Khmer language [SPECPR-24](https://openehr.atlassian.net/browse/SPECPR-24  
Added XML schema for Terminology XML files [SPECPR-3](https://openehr.atlassian.net/browse/SPECPR-3)  
