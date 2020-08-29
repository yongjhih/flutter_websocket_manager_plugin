# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Documentation
Any project is only as good as its documentation.

A key objective of this project is to provide quality documentation which makes it easy for both experienced and novices users to use the package.

## Issues

Issues are very valuable to this project.

* Ideas are a valuable source of contributions others can make
* Problems show where this project is lacking
* With a question you show where contributors can improve the user experience

Thank you for creating them.

## Pull Requests

Pull requests are, a great way to get your ideas into this repository.

When deciding if I merge in a pull request I look at the following things:

### Does it state intent

You should be clear which problem you're trying to solve with your contribution.

For example:

> Add link to code of conduct in README.md

Doesn't tell me anything about why you're doing that

> Add link to code of conduct in README.md because users don't always look in the CONTRIBUTING.md

Tells me the problem that you have found, and the pull request shows me the action you have taken to solve it.


### Is it of good quality

* There are no spelling mistakes
* It reads well
* For english language contributions: Has a good score on [Grammarly](grammarly.com) or [Hemingway App](http://www.hemingwayapp.com/)

### Does it move this repository closer to my vision for the repository

The aim of this repository is:

* To provide a WebSocket plugin anyone can use
* The content is usable by someone who hasn't written something like this before
* Foster a culture of respect and gratitude in the open source community.

### Does it follow the contributor covenant

This repository has a [code of conduct](CODE_OF_CONDUCT.md), This repository has a code of conduct, I will remove things that do not respect it.

### Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in once you have the sign-off of other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Coding Standards

The dart code base will adhere the 'effective dart' lint rules. Standards will be defined for the Kotlin and Swift code bases as we move forward.

- Code MUST be free of errors and warnings before it will be accepted.
- All code must be formatting using the standard dartfmt tool before it is submitted.
- All public API's should include examples code in the comments.
- Careful consideration is to be given to what methods/class are exposed as part of the public api. The objective is to expose the smallest api possible.
- Abbreviations in variable, method and class names should be avoided.

The code should attempt to adhere to conventions that are recognizable to the broader Flutter community and any recommended by the Google Flutter team.

## Prefer dart over Kotlin or Swift
If functionallity can be implemented in Dart then it should be implemented in Dart.

Any code written in Kotlin or Swift takes twice as much labour to support and debugging in these environments is still less than ideal on the Flutter platform.

## Unit Tests
Currently this repository has no unit tests. This is an issue that we will need to remedy sooner rather than later. In the early stages of the project we will be linient on code submitted without unit tests but as we move forward there will be an expectation for all code be submitted with unit tests.