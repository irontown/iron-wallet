# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. 

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

1. Ensure any install or build dependencies are removed before the end of the layer when doing a 
   build.
2. Update the README.md with details of changes to the interface, this includes new environment 
   variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this
   Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you 
   do not have permission to do that, you may request the second reviewer to merge it for you.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at [INSERT EMAIL ADDRESS]. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/

# Contributing Guidelines

For anyone looking to get involved to this project, we are glad to hear from you. Here are a few of the kind of contributions
that we would be interested.

*  Bug fixes
    -  If you find a bug, please first report it using GitHub issues.
    -  Issues that have already been identified as a bug will be labeled `bug`.
    -  If you'd like to submit a fix for a bug, create a Pull Request from your own fork and mention the issue number.
        +  Include a test that isolates the bug and verifies that it was fixed.
*  New Features
    -  If you'd like to accomplish something in the library that it doesn't already do, describe the problem in a new
       GitHub issue.
    -  Issues that have been identified as a feature request will be labeled `enhancement`.
    -  If you'd like to implement the new feature, please wait for feedback from the project maintainers before spending
       too much time writing the code. In some cases, `enhancement`s may not align well with the project objectives at
       the time.
*  Tests, Documentation, Miscellaneous
    -  If you think the test coverage could be improved, the documentation could be clearer, you've got an alternative
       implementation of something that may have more advantages, or any other change we would be glad hear about
       it.
       -  If it's a trivial change, go ahead and create a Pull Request with the changes you have in mind
       -  If not, open a GitHub issue to discuss the idea first.

## Requirements

For a contribution to be accepted:

*  The test suite must be complete and pass
*  Code must follow existing styling conventions
*  Commit messages must be descriptive. Related issues should be mentioned by number.

If the contribution doesn't meet these criteria, a maintainer will discuss with you on the issue. You can still
continue to add more commits to the branch you have sent the Pull Request from.

## How To Start

1. Fork this repository on GitHub.
1. Clone/fetch your fork to your local development machine.
1. Create a new branch (e.g. `issue-12`, `feat.add_foo`, etc) and check it out.
1. Make your changes and commit them. (Did the tests pass?)
1. Push your new branch to your fork. (e.g. `git push myname issue-12`)
1. Open a Pull Request from your new branch to the original fork's `master` branch.
