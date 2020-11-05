# electrode-io.github.io

This repository contains the source for the Electrode documentation site, which
is generated using [Jekyll](http://jekyllrb.com/).

## Contributing

* Commit contributions to the `develop` branch
* Use [Markdown](https://daringfireball.net/projects/markdown/) when authoring
  new documentation

## Installation

### Prerequisites

* [Ruby](https://www.ruby-lang.org/en/)
* [Bundler](https://bundler.io/)

### Setup & Run

Install the project dependencies using Bundler:

```sh
npm run bootstrap
```

Run the server locally:

```sh
npm start
```

You should be able to access the site at: [127.0.0.1:4000](http://127.0.0.1:4000/)

## Deploying to GitHub Pages

The site must be generated locally and deployed using
[jgd](http://www.yegor256.com/2014/06/24/jekyll-github-deploy.html).

> NOTE: this should be done from a local clone of the **original repo**; make
> sure you're _**not**_ working in a fork.

First, make sure the `jgd` gem is installed by running `npm run bootstrap`.
Next, generate and deploy to `master` with the following command:

```sh
npm run publish
```

Explore the [Electrode.io](http://www.electrode.io/) Website.

Built with :heart: by [Team Electrode](https://github.com/orgs/electrode-io/people)
@WalmartLabs.
