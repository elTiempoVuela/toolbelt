0.2.11 / 2017-10-11

* Accept package-lock.json dependency files

0.2.10 / 2017-09-22

* Better error messages when project creation fails

0.2.9 / 2016-07-09

* Fix debian packages
* Code cleaning

0.2.8 / 2016-07-07

* Add a Dockerfile, to build `gemnasium/toolbelt` image
* Remove deprecation warnings when running commands

0.2.7 / 2016-02-04

* Remove hardcoded max duration for autoupdate. CI servers have timeouts anyway. (#33)

0.2.6 / 2015-02-21

* "liveeval" command now returns 1 if runtime status is red
* Better error logging: error message from API is now displayed
* Autoupdate command is now split into `run` and `apply`. The command `gemnasium autoupdate` is now `gemnasium autoupdate run`. `apply` will fetch the best set of dependencies from gemnasium (after `run` returned a success).

0.2.5 / 2014-08-05

* Fix dependency files push (gemnasium df push)
* Add --files option to df push, and make "df push" and "eval" more consistent
* Send Revision and Branch headrs (required to use auto-update with local projects, not hosted on github)
* New command: "env". Displays the env vars used by gemnasium
* Check project revision before running auto-update

0.2.4 / 2014-07-15

* Fix auth login and logout
* Fix project description with several words (#14)
* Improve test suite and code coverage

0.2.3 / 2014-07-04

* Fix login when .netrc file doesn't exist (#12)
* Fix regression in auto update

0.2.2 / 2014-07-02

* Let the server decide when to end the job.

0.2.1 / 2014-07-01

* Rename env vars to make them consistent (#10, #4)
* Fix live evaluation (#9)
* Minor bug fixes

0.2.0 / 2014-06-30

* Auto-update for ruby (http://docs.gemnasium.apiary.io/#autoupdate)
* Dependency files support (list / pust) (http://docs.gemnasium.apiary.io/#dependencyfiles)

0.1.0 / 2014-06-18

Initial release
