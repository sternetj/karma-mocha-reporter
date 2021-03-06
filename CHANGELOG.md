<a name="2.0.5"></a>
## [2.0.5](https://github.com/litixsoft/karma-mocha-reporter/compare/v2.0.4...v2.0.5) (2016-07-28)


### Bug Fixes

* allows disabling the divider by setting the divider option to '' or false ([25cbe87](https://github.com/litixsoft/karma-mocha-reporter/commit/25cbe87)), closes [#68](https://github.com/litixsoft/karma-mocha-reporter/issues/68)



<a name="2.0.4"></a>
## [2.0.4](https://github.com/litixsoft/karma-mocha-reporter/compare/v2.0.3...v2.0.4) (2016-06-10)


### Bug Fixes

* no result output when no browsers are defined in the config ([53e7d65](https://github.com/litixsoft/karma-mocha-reporter/commit/53e7d65)), closes [#53](https://github.com/litixsoft/karma-mocha-reporter/issues/53)



### v2.0.3
* Fix multiline string diffs

### v2.0.2
* Print a test suite with it's child items only after all child items are completed

### v2.0.1
* Print correct failure summary and colors when a test fails only in one browser

### v2.0.0
* Move module karma to peerDependencies

### v1.3.0
* Wait before printing output of a test after all browser have run the test

### v1.2.3
* Set property success to `true` when a test is skipped. Prevents wrong output in the failure summary

### v1.2.2
* Update error message when diff output is enabled and the required modules are missing

### v1.2.1
* Check if property `assertionErrors` has at least one item before calculating the diff output

### v1.2.0
* Add support for diff output for failed tests

### v1.1.6
* Fix error that reporter output was truncated when running multiple browsers
* Reverts part of the fix from v1.1.4 (identical it blocks within the same describe block are only printed correctly when the test are run in one browser)

### v1.1.5
* Show error message when the karma runner ends with an error

### v1.1.4
* Print specs correctly when names of it blocks are identical within the same describe block

### v1.1.3
* Fix for divider is always "=" even the user set divider in config

### v1.1.2
* Show a divider line between multiple test runs for clarity

### v1.1.1
* Use overwritten colors also for the log symbols

### v1.1.0
* Add option `colors` to config that allows to overwrite the default colors

### v1.0.4
* Added plural or singular noun for 'test' based on count

### v1.0.3
* Changed some formatting to not start at newline

### v1.0.2
* enable colors when karma is piped

### v1.0.1
* print out all errors in the summary when spec fails

### v1.0.0
* add output option `noFailures` -  when set, the failure details are not logged
* time to get final with 1.0.0 :-)

### v0.3.2
* strip color from symbols when colors is set to false

### v0.3.1
* add option "ignoreSkipped" to ignore the skipped test in the output

### v0.3.0
* add option "output" to set the output level of the reporter

### v0.2.8
* add module log-symbols for printing symbols to the console

### v0.2.7
* report totalTime and netTime the same way "dots" and "progress" reporters do

### v0.2.6
* don't crash when the name of the describe or it block is a reserved object property (e.g. constructor, toString)

### v0.2.5
* results summary is now also printed when all tests fail

### v0.2.4
* better browser names formatting
* fix calculating describe items' success
* use karma's error formatter

### v0.2.3
* fix missing test results when singleRun = true

### v0.2.2
* fix that skipped test where reported as failure

### v0.2.1
* make reporter compatible with karma 0.11

### v0.2.0
* replace dependency color.js with chalk.js

### v0.1.0
* first release