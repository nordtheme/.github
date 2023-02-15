# Contributing

> **Note**
> By interacting with the Nord project, organization, and community you agree to abide to its [code of conduct][1] and follow [general open source contribution guidelines][6] and [etiquettes][36]!

We’re excited that you’re interested in contributing to Nord!
Please take a moment to read the guidelines in order to make the contribution process easy and effective for everyone involved.
Following these guidelines helps to communicate that you respect the time of the members managing and developing this project. In return, they will reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

As for everything else in the project, contributions are governed by our [Code of Conduct][1]. By participating, you are expected to uphold this code. Please [report unacceptable behavior to a project member or volunteer][2].

## Getting Started

As an open source project we love to receive contributions from the community! There are many ways to contribute, from [writing- and improving documentations](#documentations) and guides, [reporting bugs](#bug-reports), and submitting [enhancement suggestions](#enhancement-suggestions) which can be incorporated into the code base [through pull requests](#pull-requests).
The development workflow and process uses GitHub [“Issues“][3] and [“Pull Requests“][4] to track and manage contributions. The respective [issue and pull request templates][7] of a repository help to create contributions in the right form and also serve as a good starting point.

Before you continue with these contribution guidelines we highly recommend to read the GitHub‘s awesome [“Open Source Guides“][5], especially the chapter about [how to make open source contributions][6].

### Repository Assignment

Nord is a large open source project that [consists of many repositories][8], since [supporting a wide variety of applications][9] is one of the main goals and the structure is therefore deliberately designed to be very modular. Each of these “ports“ lives in its own repository where the name indicates the target application.

**Please make sure to determine the correct repository before you continue!**
Contributions related to a [port][9] belong to the specific repository while contributions related to [the website and documentations][10] or the [color palettes and specifications][11] itself are welcome in their respective repositories. This helps project members, volunteers and contributors to process every contribution faster without organization overhead.

## Bug Reports

A bug is a _demonstrable problem_ that is caused by the code in the repository. This section guides you through submitting a bug report. Following these guidelines helps project members and volunteers to understand your report, reproduce the behavior, find related reports and fix or resolve the cause.

- **Use the [GitHub issue search][12]** — check if a similar issue has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one, but only if you can add new or otherwise helpful information or context. Submitting a comment that reflects already known information or is only intended to show that you are also affected (“me too“ or “+1“ comments) only create notifications noise and increases the maintenance overhead for the project members and overall time until a solution can be provided. If you find a closed issue that seems like it is the same problem that you are experiencing, open a new issue and mention the already existing issue since closed issues are no longer monitored and processed.
- **Check if the problem has already been fixed** — try to reproduce it using the latest version of the project or the `main` repository branch which contains the latest development state and might already include required code changes.
- **Isolate the problem** — ideally create a [MCVE](#mcve) to help project members to reproduce the problem behavior.

Please always provide as much detail and context as possible, e.g. your configuration and environment, and at least **fill out and stick to the respective issue template**, the information it asks for helps project members to understand the whole context, reproduce the problem and resolve issues faster.

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Describe the exact steps which reproduce the problem** in as many details as possible.
- **[Attach files][13] like screenshots or videos** if appropriate which show you following the described steps and clearly demonstrate the problem.
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/paste snippets. If you are providing snippets in the issue, use [Markdown code blocks][14] or [attach files to the issue][13].

**Do NOT [report security vulnerabilities][16] in public issues!**
Please only [contact one of the project members in a responsible manner][2] to help project members to process and resolve it, [working towards a coordinated disclosure][15]. We will assess the issue as soon as possible on a best-effort basis and will give you an estimate for when we have a fix and release available for [an public disclosure][17].

## Enhancement Suggestions

This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality. Following these guidelines helps project members and volunteers to understand your suggestion, discuss and process it.

- **Use the [GitHub issue search][12]** — check if a similar issue has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one, but only if you can add new or otherwise helpful information or context. Submitting a comment that reflects already known information or is only intended to show that you are also affected (“me too“ or “+1“ comments) only create notifications noise and increases the maintenance overhead for the project members and overall time until a solution can be provided. If you find a closed issue that seems like it is the enhancement that you want to suggest, open a new issue and mention the already existing issue since closed issues are no longer monitored and processed.
- **Check if the enhancement has already been implemented** — use the latest version of the project or the `main` repository branch, which contains the latest development state, to ensure that the feature or improvement is not already available.
- **Optionally provide a reduced showcase, if possible** — creating a [MCVE](#mcve) helps project members to understand the goal quicker and maybe reuse the provided changes.

Before creating enhancement suggestions, please check if your idea fits with the scope and always provide as much detail and context as possible. **Fill out and stick to the respective issue template**, the information it asks for helps project members to understand the whole context, discuss it and process issues faster.

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as many details as possible and provide use cases.
- **Provide examples to demonstrate the need of an enhancement**. Include links to files or GitHub projects, or copy/paste snippets. If you are providing snippets in the issue, use [Markdown code blocks][14] or [attach files to the issue][13].
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
- **Explain why this enhancement would be useful** to most users.
- **Optionally list other projects where this enhancement exists** or, if appropriate, **[attach files][13] like screenshots, videos or animated GIFs** showing the suggested enhancement.

## Pull Requests

This section guides you through submitting an pull request. Following these guidelines helps project members and volunteers to better understand your contribution, discuss and process it.
**Please [suggest an enhancement](#enhancement-suggestions) or [report a bug](#bug-reports) first before embarking on any significant pull request** (e.g. implementing features, refactoring code, fixing a bug), otherwise you risk spending your time working on something that the maintainers might not want to merge into the project.

Before submitting a pull request, please check if it fits the project scope and always provide as much detail and context as possible. **Fill out and stick to the respective issue template**, the information it asks for helps project members to understand the whole context, discuss it and process contributions faster.

- **Use a clear and descriptive title** for the pull request to identify the contribution.
- **Do not include issue numbers in the pull request title** but add it to the top of the description like shown in the pull request template. This will enable the use of [GitHub‘s issue keyword][18] feature to link to specific [enhancement suggestions](#enhancement-suggestions) or [bug reports](#bug-reports).
- **[Attach files][13] like screenshots, videos or animated GIFs**, if appropriate, that clearly demonstrate the change.
- **Make sure to follow the project style guides**.
- **Remain focused in scope and avoid to include unrelated commits**.
- **Features and improvements should be accompanied with tests and documentation**. If the pull request improves the performance consider to include a benchmark test, optimally including a chart.
- **Lint and test before submitting your changes**.
- **Make sure to create the pull request from a [topic branch][19]**.

**All pull requests must be send against the `main` branch** - Please make sure to read the [branch organization](#branch-organization) section below for details about the branching model before submitting a pull request.

## Documentations

The documentation consists of user guides, specifications that serve as core references and dedicated documentations for each port.

You can help to improve these documents by making them more coherent, consistent and readable, adding missing information, correcting factual errors, fixing typos, and bringing them up-to-date when there are differences to the latest versions and development states. This can be done by submitting an [enhancement suggestion](#enhancement-suggestions) and then opening a [pull request](#pull-requests) for it.

## Branch Organization

Nord uses the [GitHub Flow][26] branching model. The repository consists of the `main` core branch with an infinite development lifecycle. The source code of [Git‘s `HEAD`][21] in this branch contains the latest development state and reflects all tagged release versions.

**All [pull requests](#pull-requests) for limited development lifecycle _story_/_topic_ branches must be send against the `main` branch**.

## General Help

### Improve Issues

Some issues are created with missing information, are not reproducible, or plain invalid. You can help to make it easier for project members and volunteers to understand and resolve them faster since handling issues takes a lot of time that could rather be spend on writing code and other changes.

### Feedback

We‘re always looking for more opinions on discussions in issues and pull request reviews which is a good opportunity to influence the future direction of Nord.

## Style Guides

Larger and major open source projects have their own style guides, a set of standards and conventions for the writing and design of code, documentations and [Git][22] [][^1] [commit messages][23]. It is much easier to understand content and a large code base when it is written with a consistent style.
A style guide establishes and enforces style to improve the intelligibility and communication within a project community. It ensures consistency and enforces best practice in usage and language composition.

Therefore Nord adheres to several style guides to ensure good quality and ensure to keep these standards for the future of the project. The listed style guides are used in all core projects and every port:

- [Markdown Style Guide][24]
- [Git Style Guide][25] — A well-crafted Git commit message is the best way to communicate _context_ about a change to the maintainers. The code will tell what changed, but only the commit message can properly tell why. Re-establishing the context of a piece of code is wasteful. We can‘t avoid it completely, so our efforts should go to reducing it as much as possible. The style guide assumes that you are familiar with the [GitHub Flow][26] branching model.

Other style guides are in use depending on the project context like the programming language(s) and tools. Details about these varying style guides can be found in the corresponding documentations of the respective projects.

## Versioning

Nord follows the [Semantic Versioning Specification][30] (SemVer).
We release patch versions for bug fixes, minor versions for enhancements like new features and improvements, and major versions for any backwards incompatible changes. Deprecation warnings for breaking changes are introduced in a minor version so that users can learn about the upcoming changes and migrate their code in advance.
Every significant change is at least documented in the [changelog][31] of the respective project, but will also be announced through Nord‘s infrastructure and community platforms.

## MCVE

A **M**inimal, **C**omplete, and **V**erifiable **E**xample.

When [reporting a bug](#bug-reports), sometimes even when [suggesting enhancements](#enhancement-suggestions), the issue can be processed faster if you provide code for reproduction. That code should be…

- …minimal — use as little code as possible that still produces the same behavior
- …complete — provide all parts needed to reproduce the behavior
- …verifiable — test the code you‘re about to provide to make sure it reproduces the behavior

A MCVE is a common practice for large development communities and platforms like [Stack Overflow][27] and sometimes it is also called [SSCCE][28], a **S**hort, **S**elf **C**ontained, **C**orrect (Compilable), **E**xample.

The recommended way for GitHub based projects is to create a MCVE as [Codespaces][37], [Gist][29], or new repository, but you can also [attach it to issues and pull requests as file(s)][13], use any free code (snippet) or file hosting service like [Codesandbox][38] or paste the code in [Markdown code blocks][14] into the issue.

### Minimal

The more code there is to go through, the less likely developers can understand your enhancement or find the bug. Streamline your example in one of two ways:

- **Restart from scratch** — Create new code, adding in only what is needed to demonstrate the behavior and also useful if you can‘t post the original code publicly for legal, personal or ethical reasons.
- **Divide and conquer** — When you have a small amount of code, but the source of the bug is entirely unclear, start removing code a bit at a time until the problem disappears – then add the last part back and document this behavior to help developers to trace and debug faster.

#### Minimal And Readable

Minimal does not mean terse, don‘t sacrifice communication to brevity. Use consistent naming and indentation following the [style guides](#style-guides) of the project, and include comments if needed to explain portions of the code.

### Complete

Make sure all resources and code necessary to reproduce the behavior is included. The problem might not be in the part you suspect it is, but another part entirely.

### Verifiable

To entirely understand your bug report or enhancement, developers will need to verify that it _exists_:

- **Follow the contribution guidelines regarding the description and details** — Without information developers won‘t be able to understand and reproduce the behavior.
- **Eliminate any issues that are not relevant** — Ensure that there are no compile-time errors.
- **Make sure that the example actually reproduces the problem** — Sometimes the bug gets fixed inadvertently or unconsciously while composing the example or does not occur when running in a “fresh“ development environment.

<p align="center">
  <picture>
    <source srcset="https://raw.githubusercontent.com/nordtheme/assets/main/static/images/elements/separators/iceberg/footer/dark/spaced.svg?sanitize=true" width="100%" media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" />
    <source srcset="https://raw.githubusercontent.com/nordtheme/assets/main/static/images/elements/separators/iceberg/footer/light/spaced.svg?sanitize=true" width="100%" media="(prefers-color-scheme: dark)" />
    <img src="https://raw.githubusercontent.com/nordtheme/assets/main/static/images/elements/separators/iceberg/footer/dark/spaced.svg?sanitize=true" width="100%" />
  </picture>
</p>

<p align="center">
  Copyright &copy; 2016-present <a href="https://www.svengreb.de" target="_blank">Sven Greb</a>
</p>

<p align="center">
  <a href="https://github.com/nordtheme/.github/blob/main/license" target="_blank">
    <img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=MIT&logoColor=eceff4&logo=creativecommons&colorA=4c566a&colorB=88c0d0"/>
  </a>
</p>

Thanks for the inspirations to GitHub‘s [Open Source Guides][5] and various contribution guides of large open source projects like [React][33], [Atom][35], [PhotoPrism][39] and [Ruby on Rails][34].

<!--lint disable final-definition-->

[1]: https://github.com/nordtheme/.github/blob/main/code_of_conduct.md
[2]: https://github.com/nordtheme/.github/blob/main/support.md
[3]: https://docs.github.com/en/issues
[4]: https://docs.github.com/en/pull-requests
[5]: https://opensource.guide
[6]: https://opensource.guide/how-to-contribute
[7]: https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates
[8]: https://github.com/orgs/nordtheme/repositories
[9]: https://www.nordtheme.com/ports
[10]: https://github.com/nordtheme/docs
[11]: https://github.com/nordtheme/nord
[12]: https://docs.github.com/en/search-github/searching-on-github/searching-issues-and-pull-requests
[13]: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/attaching-files
[14]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
[15]: https://docs.github.com/en/code-security/repository-security-advisories/about-coordinated-disclosure-of-security-vulnerabilities
[16]: https://docs.github.com/en/code-security/repository-security-advisories/about-coordinated-disclosure-of-security-vulnerabilities#best-practices-for-vulnerability-reporters
[17]: https://docs.github.com/en/code-security/repository-security-advisories/about-coordinated-disclosure-of-security-vulnerabilities#best-practices-for-maintainers
[18]: https://docs.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue
[19]: https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows#_topic_branch
[21]: https://git-scm.com/book/en/v2/Git-Internals-Git-References#ref_the_ref
[22]: https://git-scm.com
[23]: https://git-scm.com/docs/git-commit
[24]: https://github.com/svengreb/styleguide-markdown
[25]: https://github.com/svengreb/styleguide-git
[26]: https://docs.github.com/en/get-started/quickstart/github-flow
[27]: https://stackoverflow.com/help/mcve
[28]: http://sscce.org
[29]: https://gist.github.com
[30]: https://semver.org
[31]: https://keepachangelog.com
[33]: https://reactjs.org/docs/how-to-contribute.html
[34]: https://guides.rubyonrails.org/contributing_to_ruby_on_rails.html
[35]: https://github.com/atom/atom/blob/master/CONTRIBUTING.md
[36]: https://opensource.how/etiquette
[37]: https://github.com/features/codespaces
[38]: https://codesandbox.io
[39]: https://docs.photoprism.app/developer-guide

<!--lint disable no-duplicate-definitions-->

[^1]: https://en.wikipedia.org/wiki/Version_control
