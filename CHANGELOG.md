Change Log
==========

Version 0.4
----------------------------
* Retrofit 2.0 upgrade

Version 0.3
----------------------------
* Add support for prefetch API to fetch selected alternatives without participation

Version 0.2
----------------------------
* Switch from async to synchronous API, user of the client will need their own threading
* Proper validation of experiment and alternative names locally instead of having them fail on the server
* Ensure there's no confusion about proper ordering of alternatives (control alternative is first)

Version 0.1
----------------------------

* Initial snapshot release of sixpack-java
* Full support for creating, participating in and converting experiments
