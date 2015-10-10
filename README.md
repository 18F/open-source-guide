## 18F Open Source Style Guide


This guide helps people document code repositories so that they're easy to use and understand. In each section, we outline our strategies for making sure that our code repositories are clear, accessible, and user-friendly.

It’s important to make sure our documentation is clear both for internal and external audiences. As our team expands, we want our new employees to easily find and use our existing codebases.

It's also really important if we want to make outside contributors feel welcome or have outside organizations fork and use our code. ([And we do!](https://github.com/18F/open-source-policy/blob/master/policy.md)) Explaining what a project is, why it's important, and how people can help ensures that people can fork and adapt our projects.

(Fork means to copy the code that exists over to your own repo, or repository of code, so that you can adapt or use it as needed.)

This guide also contains a checklist we created that helps ensure our repos are clear, accessible, and user-friendly. Some terminology used may be GitHub-specific, but the concepts are applicable regardless of your version control system or platform. We wrote it so that both non-coders and coders can understand it. (If something is not clear, please let us know.)

We’re sharing it because it we think it’s helpful for lots of organizations, including our own. We know that many of our repos don’t conform to this exact style. By articulating a specific style, we hope this document will also help us improve our own practices.


## How to use this guide

We created this guide for reference on an as-needed basis. It’s here when you’re wondering how to describe a repo, for instance, or when you’re wondering how to create a friendly, informational tone when writing issues for users.

To this end, we’ve structured the guide into descriptively named sections. Browse our table of contents to find the topic you’re looking for.

Most importantly, we encourage you to make a copy of this document and adapt it to your organizational needs. This guide is just that: a guide. It’s not meant to provide the final opinion on any of the topics discussed. If a certain section isn’t relevant to you and your team, delete it. And if you feel the guide is missing a section, by all means, add it by clicking 'edit this page' at the bottom of every page. This guide is yours to use, and we trust you’ll update it in the ways that best suit you.


### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0
>dedication. By submitting a pull request, you are agreeing to comply
>with this waiver of copyright interest.


### How to run a local copy of this guide

(Instructions adapted from the [18F Documentation Working Group](https://github.com/18F/wg-documentation).)

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may
consider using a Ruby version manager such as
[rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to
help ensure that Ruby version upgrades don't mean all your
[gems](https://rubygems.org/) will need to be rebuilt.

On OS X, you can use [Homebrew](http://brew.sh/) to install Ruby in
`/usr/local/bin`, which may require you to update your `$PATH` environment
variable:

```shell
$ brew update
$ brew install ruby
```

To serve the site locally:

```shell
$ git clone git@github.com:18F/open-source-guide.git
$ cd open-source-guide
$ ./go serve
```

This will check that your Ruby version is supported, install the [Bundler
gem](http://bundler.io/) if it is not yet installed, install all the gems
needed by the template, and launch a running instance on
`http://localhost:4000/`. (Make sure to include the trailing
slash! The built-in Jekyll webserver doesn't redirect to it.)

After going through these steps, run `./go` to see a list of available
commands. The `serve` command is the most common for routine development.


### How to create your own guide

This guide is based on the [DOCter template](https://github.com/cfpb/DOCter) created by the
[Consumer Financial Protection Bureau](http://www.consumerfinance.gov/) (CFPB). Our canonical
adaptation of DOCter is contained in the [18F Guides Template](https://pages.18f.gov/guides-template/).


### Contact us

If you'd like to contact us, please create a GitHub issue or email 18F@gsa.gov. Thank you!
