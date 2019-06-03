# Galaxy 🚀

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![CircleCI](https://circleci.com/gh/tuist/galaxy.svg?style=svg)](https://circleci.com/gh/tuist/galaxy)
[![Slack](http://slack.tuist.io/badge.svg)](http://slack.tuist.io)
[![License](https://img.shields.io/github/license/tuist/galaxy.svg)](/LICENSE.md)

To improve teams' workflows with Xcode projects, it's crucial to have insights and metrics from the projects. Although some insights can be exported using `xcodebuild`, teams rarely do anything with that information nor know how to collect the data that they are really interested in.

Galaxy is Tuist's attempt to make that possible. Projects using Tuist can integrate with Galaxy, a team dashboard where teams can check metrics that Tuist reports from the projects.

It's a paid service, but since the project is open source, teams can deploy the web app and API into their internal infrastructure.

## Setup

The repositories contains 2 projects, an API built with [Rails](https://rubyonrails.org/) under the `api` directory and a web app built with [NextJS](https://nextjs.org/) under `app`.

### API

1. Clone the repository: `git clone git@github.com:tuist/galaxy.git`.
2. cd into the `api` directory: `cd api`.
3. Install dependencies: `bundle install`.
4. Run it locally: `bundle exec rails server`.

### App

1. Clone the repository: `git clone git@github.com:tuist/galaxy.git`.
2. cd into the `app` directory: `cd app`.
3. Install dependencies: `yarn install`.
4. Run it locally: `yarn dev`.


## Open source

Tuist is a proud supporter of the [Software Freedom Conservacy](https://sfconservancy.org/)

<a href="https://sfconservancy.org/supporter/"><img src="https://sfconservancy.org/img/supporter-badge.png" width="194" height="90" alt="Become a Conservancy Supporter!" border="0"/></a>

## License

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftuist%2Ftuist.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftuist%2Ftuist?ref=badge_large)