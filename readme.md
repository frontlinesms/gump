Forrest Gump
============

Continuous Testing scripts for [Grails][1].

# The Scripts

This toolkit consists of some simple scripts for helping to run Grails tests continuously:

## parse_junit_report

This evaluates a junit report XML and turns it into a simple console-friendly output with colour coding for passing and failing tests.

## run_and_watch

Continuously re-run a build and generate a report detailing build failure or `parse_junit_report` output as appropriate.

## run_forever

Run run_and_watch as a background task and continuously update the result to the console.

[1]: http://www.grails.org

