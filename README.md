# SimpleSAMLphp

![Build Status](https://github.com/simplesamlphp/simplesamlphp/workflows/CI/badge.svg?branch=master)
[![Coverage Status](https://codecov.io/gh/simplesamlphp/simplesamlphp/branch/master/graph/badge.svg)](https://codecov.io/gh/simplesamlphp/simplesamlphp)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp/?branch=master)
[![Type coverage](https://shepherd.dev/github/simplesamlphp/simplesamlphp/coverage.svg)](https://shepherd.dev/github/simplesamlphp/simplesamlphp)
[![BrowserStack Status](https://automate.browserstack.com/badge.svg?badge_key=LzlCL29sZEVDRXJpdGtxZUdITFA3YjYyUFBBYkVVZDVDcG1YZXRaN2pvTT0tLVhCNzkwVUNGVFVjVFVicUg0R1BNR0E9PQ==--f9efb6f330bd98dd6e3c7b816ac2f0982275a872)](https://automate.browserstack.com/public-build/LzlCL29sZEVDRXJpdGtxZUdITFA3YjYyUFBBYkVVZDVDcG1YZXRaN2pvTT0tLVhCNzkwVUNGVFVjVFVicUg0R1BNR0E9PQ==--f9efb6f330bd98dd6e3c7b816ac2f0982275a872)

This is the official repository of the SimpleSAMLphp software.

* [SimpleSAMLphp homepage](https://simplesamlphp.org)
* [SimpleSAMLphp Downloads](https://simplesamlphp.org/download)

Please, [contribute](CONTRIBUTING.md)!


----------------------------------------------------------------------------------------------------------------------------------------------------------
# SimpleSAMLphp - After Fixing Vulnerabilities

SimpleSAMLphp is a native PHP software that controls authentication and has received several accolades. The Norwegian National Research and Education Network is being led by UNINETT, a government-owned business. As either a Service Provider (SP) or an Identity Provider (IdP), this PHP programme is SAML 2.0 compliant.
Web SSO (Single Sign On) often makes use of SAML (Security Assertion Markup Language). To verify a user's identity before giving access, SimpleSAMLphp establishes a secure connection to an authentication server.
After reviewing the "Issues" page on GitHub and executing the application in sonarcloud.io, the following security vulnerabilities were discovered in this application:
*	Vulnerability to brute-force password guesswork in admin-based logins.
*	Functional codes utilize a weak pseudo-random number generator.
*	Functional codes employ weak cryptographic hashing algorithms.
*	User-Provided Data Validation for Class/Method Naming
*	Verify that the referenced value variable is unset at the conclusion of the iteration.
*	The Vulnerability and Impact of Including Files Multiple Times in PHP and the Importance of Using include_once
In addition, we have added an OAuth feature to the application to accommodate future implementation suggestions from customers. Therefore, we have developed a simple web page for contributors to upload content to our Google Drive. 
The team members have also developed fixes and recommended security procedures to be used when addressing the aforementioned issues, and we have integrated the OAuth part to further secure file uploads.
