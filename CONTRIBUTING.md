# Contributing to FBShipIt
We want to make contributing to this project as easy and transparent as
possible.

## Code of Conduct
Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please [read the full text](https://code.facebook.com/pages/876921332402685/open-source-code-of-conduct) so that you can understand what actions will and will not be tolerated.

## Pull Requests
We actively welcome your pull requests.

1. Fork the repo and create your branch from `master`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Ensure the Hack typechecker doesn't raise any errors.
6. If you haven't already, complete the Contributor License Agreement ("CLA").

## Contributor License Agreement ("CLA")
In order to accept your pull request, we need you to submit a CLA. You only need
to do this once to work on any of Facebook's open source projects.

Complete your CLA here: <https://code.facebook.com/cla>

## Issues
We use GitHub issues to track public bugs. Please ensure your description is
clear and has sufficient instructions to be able to reproduce the issue.

Facebook has a [bounty program](https://www.facebook.com/whitehat/) for the safe
disclosure of security bugs. In those cases, please go through the process
outlined on that page and do not file a public issue.

## Coding Style
* 2 spaces for indentation rather than tabs
* 80 character line length
* No trailing whitespace at end of lines
* Opening braces at end of line
* No space before function parameters, but spaces after control statements
* Prefer Hack strict where possible

```Hack
if ($foo) {
  myFunc($bar);
}
```

For multi-line functions:
 - one argument per line
 - trailing comma for last argument
 - closing paren is indented to the same level as the call, not the arguments
 - space between `:` and return type for definitions

```Hack
foo(
  $bar,
  $baz,
): void {
  // do stuff
}
```

## License
By contributing to FBShipIt, you agree that your contributions will be licensed
under its BSD license.
