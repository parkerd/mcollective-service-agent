# Changelog

Change history for mcollective-service.

## 3.1.3

Released 2014-06-18

* Add pl:packaging to support {apt,yum}.puppetlabs.com (MCOP-70)
* Correctly gate around empty result sets (MCOP-55)


# 3.1.2

Released 2013-03-08

* Small wording fix in the DDL for the data plugin (19659)


# 3.1.1

Released 2013-02-26

* Improved failure message on failed restart action (19429)


# 3.1.0

Released 2013-02-21

* Allow application parameters to be passed as either `action service`
  or `service action` (19371)


# 3.0.2

Released 2013-02-20

* Remove request for confirmation when calling application's status
  action unfiltered (19346)


# 3.0.1

Released 2013-01-21

* Published complete rewrite of the service agent (18729)
