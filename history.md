1.5.0 / Unreleased
==================
* Diff for humans now shows 2 weeks ago instead of 14 days ago
* Added a local getter to test if the instance is in the local timezone
* Added a utc getter to check if the instance is in UTC timezone
* Fixed dst comment / phpdoc
* Optimize timezone getters

1.4.0 / 2013-09-08
==================
* Corrected various PHPdocs
* formatLocalized() is now more OS independent
* Improved diff methods
* Test now can be mocked using a relative term

1.3.0 / 2013-08-21
==================

  * Added modifier methods firstOfMonth(), lastOfMonth(), nthOfMonth(), next(), previous(), and so on
  * Added modifiers startOfWeek() and endOfWeek()
  * Added testing helpers to allow mocking of new Carbon(), new Carbon('now') and Carbon::now()
  * Added formatLocalized() to format a string using strftime() with the current locale
  * Improved diffInSeconds()
  * Improved [add|sub][Years|Months|Days|Hours|Minutes|Seconds|Weeks]
  * Docblocks everywhere ;(
  * Magic class properties
  * Added PHP 5.5 to travis test coverage
  * General Code cleanup

1.2.0 / 2012-10-14
==================

  * Added history.md
  * Implemented __isset() (thanks @flevour)
  * Simplified tomorrow()/yesterday() to rely on today()... more DRY
  * Simplified __set() and fixed exception text
  * Updated readme

1.1.0 / 2012-09-16
==================

  * Updated composer.json
  * Added better error messaging for failed readme generation
  * Fixed readme typos
  * Added static helpers `today()`, `tomorrow()`, `yesterday()`
  * Simplified `now()` code

1.0.1 / 2012-09-10
==================

  * Added travis-ci.org

1.0.0 / 2012-09-10
==================

  * Initial release
