# Awesome TAP with stars

> Useful resources for the [Test Anything Protocol](https://testanything.org)

TAP is a simple text-based interface between testing modules in a test harness.

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*

## Contents

* [Reporters](#reporters)
* [Producers](#producers)
* [Consumers](#consumers)
* [Tools](#tools)
* [Articles](#articles)
* [Tutorials](#tutorials)
* [Documentation](#documentation)
* [Community](#community)

## Reporters

### JavaScript

* [faucet](https://github.com/substack/faucet) ⭐ 557 | 🐛 18 | 🌐 JavaScript | 📅 2024-02-16 - Human-readable summarizer.
* [tap-spec](https://github.com/scottcorgan/tap-spec) ⭐ 282 | 🐛 11 | 🌐 JavaScript | 📅 2024-06-01 - Mocha-like spec reporter.
* [tap-nyan](https://github.com/calvinmetcalf/tap-nyan) ⭐ 148 | 🐛 5 | 🌐 JavaScript | 📅 2019-05-06 - Nyan cat.
* [tap-diff](https://github.com/axross/tap-diff) ⚠️ Archived - Human-friendly output with diffing.
* [tap-notify](https://github.com/axross/tap-notify) ⭐ 61 | 🐛 3 | 🌐 JavaScript | 📅 2019-07-18 - Notifier for macOS, Linux and Windows.
* [tap-difflet](https://github.com/namuol/tap-difflet) ⭐ 48 | 🐛 2 | 🌐 JavaScript | 📅 2019-07-08 - Minimal output with diffing.
* [tap-summary](https://github.com/zoubin/tap-summary) ⭐ 45 | 🐛 3 | 🌐 JavaScript | 📅 2022-05-24 - Summarized output.
* [tap-xunit](https://github.com/aghassemi/tap-xunit) ⭐ 41 | 🐛 11 | 🌐 JavaScript | 📅 2025-08-19 - xUnit output.
* [tap-dot](https://github.com/scottcorgan/tap-dot) ⭐ 38 | 🐛 7 | 🌐 JavaScript | 📅 2019-06-18 - Dotted output.
* [tap-prettify](https://github.com/toolness/tap-prettify) ⭐ 35 | 🐛 5 | 🌐 JavaScript | 📅 2013-09-15 - Nice readable output with diffing.
* [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) ⭐ 29 | 🐛 17 | 🌐 JavaScript | 📅 2025-10-25 - Use any of the [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters) ⭐ 29 | 🐛 17 | 🌐 JavaScript | 📅 2025-10-25.
* [tap-json](https://github.com/gummesson/tap-json) ⭐ 26 | 🐛 4 | 🌐 JavaScript | 📅 2019-10-25 - JSON output.
* [tap-bail](https://github.com/juliangruber/tap-bail) ⭐ 17 | 🐛 3 | 🌐 JavaScript | 📅 2017-03-03 - Bail out when the first test fails.
* [tap-pessimist](https://github.com/clux/tap-pessimist) ⭐ 16 | 🐛 1 | 🌐 JavaScript | 📅 2017-09-06 - Only shows failed tests.
* [tap-teamcity](https://github.com/smockle/tap-teamcity) ⚠️ Archived - Output for TeamCity.
* [tap-min](https://github.com/derhuerst/tap-min) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-20 - Minimal output.
* [tap-simple](https://github.com/joeybaker/tap-simple) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2015-04-30 - Simple output.
* [ava-tap-json](https://github.com/yovasx2/ava-tap-json) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2019-10-25 - JSON output with AVA compatibility.
* [tap-colorize](https://github.com/substack/tap-colorize) - Colorize the output while preserving machine-readability.

### Go

* [tapfmt](https://github.com/coreybutler/tapfmt) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2022-12-23 - Standalone cross-platform formatter.

## Producers

Things that produce TAP output.

### JavaScript

* [AVA](https://github.com/sindresorhus/ava) ⭐ 20,833 | 🐛 72 | 🌐 JavaScript | 📅 2026-06-17 - Futuristic test runner (`$ ava --tap`).
* [tape](https://github.com/substack/tape) ⭐ 5,798 | 🐛 40 | 🌐 JavaScript | 📅 2026-06-18 - TAP-producing test harness for Node.js and browsers.
* [tap](https://github.com/isaacs/node-tap) ⭐ 2,426 | 🐛 17 | 🌐 JavaScript | 📅 2026-07-27 - TAP test framework for Node.js.
* [zora](https://github.com/lorenzofox3/zora) ⭐ 540 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-12 - TAP-producing test runner that works with ES2015 without Babel.
* [jasmine-reporters](https://github.com/larrymyers/jasmine-reporters) ⭐ 395 | 🐛 23 | 🌐 JavaScript | 📅 2024-09-20 - TAP output for Jasmine.
* [mos](https://github.com/zkochan/mos) ⚠️ Archived - Markdown file generator and tester (`$ mos test --tap`).
* [qunit-tap](https://github.com/twada/qunit-tap) ⭐ 72 | 🐛 1 | 🌐 JavaScript | 📅 2017-04-06 - TAP output for QUnit.
* [karma-tap-reporter](https://github.com/fumiakiy/karma-tap-reporter) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-10 - TAP output for Karma.
* [ESLint](https://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter (`$ eslint --format=tap`).
* [Mocha](https://mochajs.org) - Feature-rich test framework for Node.js and browsers (`$ mocha reporter=tap`).
* [node:test](https://nodejs.org/api/test.html) - Minimal TAP test runner included with Node.js.

### Swift

* [TAP](https://github.com/swiftdocorg/tap) ⚠️ Archived - A Swift package for the Test Anything Protocol (v13).

### Fish

* [Fishtape](https://github.com/fisherman/fishtape) ⭐ 383 | 🐛 4 | 🌐 Shell | 📅 2024-05-26 - TAP producer and test harness for fish.

### Bash

* [bats](https://github.com/sstephenson/bats) ⚠️ Archived - Bash Automated Testing System.
* [ShellSpec](https://github.com/shellspec/shellspec) ⭐ 1,392 | 🐛 110 | 🌐 Shell | 📅 2025-11-24 - A full-featured BDD unit testing framework for POSIX shells.

[More…](https://testanything.org/producers.html)

## Consumers

Things that consume TAP output.

### JavaScript

* [tap-parser](https://github.com/substack/tap-parser) ⚠️ Archived - TAP parser.
* [tap-out](https://github.com/scottcorgan/tap-out) ⭐ 23 | 🐛 19 | 🌐 JavaScript | 📅 2023-03-04 - TAP parser.
* [yamlish](https://github.com/isaacs/yamlish) ⚠️ Archived - YAML-block parser.

[More…](https://testanything.org/consumers.html)

## Tools

### JavaScript

* [smokestack](https://github.com/hughsk/smokestack) ⭐ 243 | 🐛 32 | 🌐 JavaScript | 📅 2022-12-08 - Run TAP tests in a browser and write the output to `stdout`.
* [tap-dev-tool](https://github.com/Jam3/tap-dev-tool) ⭐ 29 | 🐛 3 | 🌐 JavaScript | 📅 2015-06-16 - Prettify TAP in the browser console.
* [tap-merge](https://github.com/anko/tap-merge) ⭐ 13 | 🐛 1 | 🌐 LiveScript | 📅 2019-11-21 - Merge multiple TAP streams.
* [chutney](https://github.com/derhuerst/chutney) ⭐ 4 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-10 - Run TAP tests at Sauce Labs. Lightweight [smokestack](https://github.com/hughsk/smokestack) ⭐ 243 | 🐛 32 | 🌐 JavaScript | 📅 2022-12-08 alternative.

### Python

* [tappy](https://github.com/mblayman/tappy) ⭐ 147 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - Tools for working with TAP.

## Articles

* [Understand the Test Anything Protocol](https://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)

## Tutorials

* [test-anything](https://github.com/finnp/test-anything) ⭐ 169 | 🐛 0 | 🌐 JavaScript | 📅 2023-04-02 - Learn to test anything with TAP through an interactive workshop.

## Documentation

* [Specification](https://testanything.org/tap-version-13-specification.html)
* [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)

## Community

* [Discuss](https://github.com/TestAnything/Specification/issues) ⭐ 102 | 🐛 24 | 📅 2024-08-16
* [Reddit](https://www.reddit.com/r/testanythingprotocol)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/tap)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
