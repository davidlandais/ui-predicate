
# Contributing to ui-predicate
First of all thank you for expressing interest in ui-predicate! :+1:<br />
We are very happy to welcome new contributors. :tada:

## How can I contribute? :man_technologist:
### Report a bug :bug:
If you think you have found a bug, please search [our issue tracker][issues] to see if anyone has already reported it.<br />
If you are the first to have noticed it, please [create an issue][new_issue], and make sure to provide any information that might help us resolve it.<br />
You are welcome to try and fix it by submitting a pull request if you would like to (see Pull requests section for more information).

### Feature requests and enhancements :sparkles:
We are open to feature requests, be sure to search [our issue tracker][issues] to see if anyone has already asked for it.<br />
If not, please [create an issue][new_issue] describing what you want, what your use case is, and an example of code.<br />
You are welcome to try and do it yourself by submitting a pull request if you would like to (see Pull requests section for more information).<br />
As ui-predicate is still a very young project, we are also open to enhancement suggestions; if you think of anything that might help us improve the project, please [create an issue][new_issue] and we will be happy to discuss it with you.

### Pull requests :arrow_up:
#### Installation :package:
We use npm as our package manager.<br />
Once you have cloned the project, run `npm i` to install all the dependencies.

#### Architecture :house:
ui-predicate is managed as a [monorepo](https://medium.com/netscape/the-case-for-monorepos-907c1361708a) using [lerna](https://lernajs.io/)

Each package of ui-predicate is organized in namespaces (core, vue, react, angular, etc.). Please try to respect this organization; if you are not sure where to put your code, ask for the right place in your issue or PR.

#### Tests and Code style :policeman:
If you write any code, be sure to write the test that goes with it in a file located at the same place and named `<something>.test.js`; we have a coverage of a :100: percent and we would like to keep it :wink:.<br />
We use [eslint](http://eslint.org/) to enforce some coding rules (2 spaces indentation, etc.), ideally use an IDE to help you comply with these rules.<br />
Before pushing anything, please be sure to check that the tests are OK by running `npm test` and that your code complies with the coding rules by running `npm run lint`.

#### Documentation :bulb:
The better the documentation, the fewer things users will have to wonder about.<br />
We [use jsdoc](http://usejsdoc.org/) to document our code, if you write any new code please write the documentation with it and try to conform to the existing documentation.<br />
If you want to see the result of what you wrote you can run `npm run docs`, it will generate the documentation in `docs/<version>/`.<br />
:warning: Please do not commit the files generated in `docs/`, it is automatically updated once we create a new tag.

## Any questions :question:
If you are not sure whether to report a bug or ask for a new feature, or if you just have a question about anything, please [create an issue][new_issue].

## Code of conduct :page_facing_up:
In order to keep a happy and respectful atmosphere around the project, we expect everyone participating in it to follow our [Code of conduct](https://github.com/fgribreau/ui-predicate/blob/master/.github/CODE_OF_CONDUCT.md).

[issues]: https://github.com/fgribreau/ui-predicate/issues
[new_issue]: https://github.com/fgribreau/ui-predicate/issues/new
