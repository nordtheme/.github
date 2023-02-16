# Security Policies And Procedures

> **Note**
> By interacting with the Nord project, organization, and community you agree to abide to its [code of conduct][24] and follow [general open source contribution guidelines][25] and [etiquettes][26]!

This document outlines security procedures and policies for security vulnerabilities in the Nord project.

Nord takes the security of its projects seriously, which includes all (source code) repositories managed through [this GitHub organization][1] as well as the [official organization for the Nord community][2].

If you believe you have found a security [vulnerability][4] [][^1] in any Nord-owned repository that meets the [definition of vulnerabilities][3], please report it as described below.

## Scope

Reports should only be related to…

- [official Nord projects and ports][17] within the [`nordtheme` GitHub organization][1], including the [official website(s)][19].
  Only code that is actually owned by Nord is supported while issues related to the upstream project of a port must be reported to the corresponding maintainers or companies of the upstream project. Of course Nord will help to report issues to the upstream team but we are **not responsible for security vulnerabilities in upstream projects in any way**.
- [Nord community projects and ports][18] within the [`nordtheme-community` GitHub organization][2].
  The same scope for upstream projects of ports applies like for official Nord projects and ports, but additionally the task of the security vulnerability handling and disclosure process is part of the corresponding maintainer team of the specific Nord community project or port. Of course the Nord core team will aid in closing issues as quickly as possible, but the main administration lies with the respective maintainers.

## Reporting Security Issues

> **Warning**
> Never report security vulnerabilities through public GitHub issues or any other public (communication) channel or platform!

Instead, please report security vulnerabilities by either…

- …[using GitHub‘s “Private Security Vulnerability Reporting“ system][5].
- …sending an email to [security@nordtheme.com][6], if you prefer to submit without logging in or creating a GitHub account. If possible, please encrypt your email with Nord‘s [Age][20] [][^4] or [PGP][21] [][^5] ([GPG][23]) key where both can be found [in the GitHub organization `.github` repository][22] [][^6] [][^7] and inlined below this list.
- …writing a private message in [Matrix][8] to [`@svengreb:matrix.org`][10] or [`@nordtheme:matrix.org`][7] or ask any moderator in the [`#nordtheme:matrix.org` space][9] for further help to submit a report. Alternatively, contact `svengreb#2186` or `nordtheme#0637` on the [official Nord Discord server][11].
  Please note that both [community platforms][12] are public areas. When escalating to that address please do not discuss the issue in public, e.g. no private messaging chats, but simply ask for ways to get a hold of someone from the project team if both direct contacts listed above are not available at the moment.

Public keys for encrypted communications:

<details>
  <summary><em>Age</em></summary>
  <pre>
    <code>age10tg5xee38ecn3jgt45quzvkxq2nghlrk4dxpul28tvcmr8ksjfhstmcuar</code>
  </pre>
</details>

<details>
<summary><em>PGP</em> (<em>GPG</em>)</summary>
<pre>
<code>
  -----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEY8QP3BYJKwYBBAHaRw8BAQdAwzx7db39Nn0ipmt/cvLDzwGiTjWD3Afvtvph
Ey5QWOO0L25vcmR0aGVtZSAoTm9yZCBUaGVtZSkgPHNlY3VyaXR5QG5vcmR0aGVt
ZS5jb20+iJMEExYKADsWIQRhbe+hBgD3WHC1Pl6oD1Bh26nrkgUCY8QP3AIbAwUL
CQgHAgIiAgYVCgkICwIEFgIDAQIeBwIXgAAKCRCoD1Bh26nrkupJAP4v988C6lOo
Q+M4i2yY3DQXDzcboNsV09RaSIr9CHNL0wEA/cXIgoMvEH9kXUh1G26q71wHe2PF
3FLqseRjyKiKnwq4OARjxA/cEgorBgEEAZdVAQUBAQdArJ+LNPCjPZ6GjQfRVWNu
iKwzI0xKxkUyMvWOxaqa81EDAQgHiHgEGBYKACAWIQRhbe+hBgD3WHC1Pl6oD1Bh
26nrkgUCY8QP3AIbDAAKCRCoD1Bh26nrknCPAQDJb2HEMt8SbDyYzDtmBnKHru8C
xvBwhenNEVmbv57fOwEApIbZ0Sw9f1BZ89l6At8t1/aO5Uz2WX6usNQYu6DWSA8=
=PLj5
-----END PGP PUBLIC KEY BLOCK-----
</code>

</pre>
</details>

Please include [as much information as possible][16], using the questions listed below as a guideline, to help us better understand the nature and scope of the possible issue and help us triage the report more quickly:

- Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

Note that all communications, following the global standard, must be in English to ensure that the process can take place with as few language barriers as possible and to avoid possible translation problems during the process.

## Public Disclosure Process

Confirmed vulnerabilities will be investigated and patched as quickly as possible and rolled out to affected users through a [patch][13] or [minor][14] release version, depending on the status of the current project development, release cycle process and ways to backport to other supported versions.

Resolved security vulnerabilities will be made public as [advisory][15] [][^2] [][^3] on GitHub and, in most cases, additionally announced via other official communication channels and platforms. This might also include a guide on how to apply mitigating steps to aid users in closing the security vulnerability as simply as possible.

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
  <a href="https://www.svengreb.de">
    <img src="https://img.shields.io/static/v1.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAABMklEQVQ4jcWQvUoDQRRGz52s5IfVIiDWPkGKFFaCIVaGdIagjcFAwICFb7DvIK6QQlNpY2UQLMQVBbEQ0SewFkGbKCQmOzaTJay7/lR+zTAf9xwuF/47Mv45rdezqWEq72v/RWZnHgqOMwDwHMfSj085JSqb6Pu38we7r18E3nqzhmYbsE11rxKsAvhDfQiSM30XYbOw57YDwfnaRl6U3ABWaMNn806H+oGPzBX3d+4UgChZiYBHYBgGsBLoKoAyhR0x9G20Zmpc4P1ZoMQDcwMNclFrdhBKv6M5WWi7ZQGtjEUn35IV4OwnVjSX/WGmKqCDDUa5rmyle3bvGFiMg3WGUsF1u0EXHoqTRMGRgkAy2eugKZrqijRLYThWANBpNDL2h3UE0J0YLJdbrfe42f/NJ0wqY7/KcXKPAAAAAElFTkSuQmCC&label=lovely%20crafted%20in&message=Germany&colorA=4c566a&colorB=88c0d0"/>
  </a>
</p>

<!--lint disable final-definition-->

[1]: https://github.com/nordtheme
[2]: https://github.com/nordtheme-community
[3]: https://en.wikipedia.org/wiki/Vulnerability_(computing)#Definitions
[4]: https://en.wikipedia.org/wiki/Vulnerability_(computing)
[5]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerabilitys
[6]: mailto:security@nordtheme.com
[7]: https://matrix.to/#/@nordtheme:matrix.org
[8]: https://matrix.org
[9]: https://matrix.to/#/#nordtheme:matrix.org
[10]: https://matrix.to/#/@svengreb:matrix.org
[11]: https://discord.gg/65nrRxuJzB
[12]: https://www.nordtheme.com/community
[13]: https://semver.org/#spec-item-6
[14]: https://semver.org/#spec-item-7
[15]: https://docs.github.com/en/code-security/security-advisories/repository-security-advisories/about-repository-security-advisories
[16]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/best-practices-for-writing-repository-security-advisories
[17]: https://github.com/orgs/nordtheme/repositories
[18]: https://github.com/orgs/nordtheme-community/repositories
[19]: https://www.nordtheme.com
[20]: https://raw.githubusercontent.com/nordtheme/.github/main/data/nordtheme.age.txt.pub
[21]: https://raw.githubusercontent.com/nordtheme/.github/main/data/nordtheme.gpg.asc
[22]: https://github.com/nordtheme/.github/tree/main/data

<!-- The reference is actually used but the currently used version of remark fails to parse reference link usages that are wrapped in braces. -->

<!--lint ignore no-unused-definitions-->

[23]: https://gnupg.org
[24]: https://github.com/nordtheme/.github/blob/main/code_of_conduct.md
[25]: https://opensource.guide/how-to-contribute
[26]: https://opensource.how/etiquette

<!--lint disable no-duplicate-definitions-->

[^1]: https://csrc.nist.gov/glossary/term/vulnerability
[^2]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/about-coordinated-disclosure-of-security-vulnerabilities
[^3]: https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure
[^4]: https://age-encryption.org
[^5]: https://www.openpgp.org
[^6]: https://github.com/nordtheme/.github/blob/main/data/nordtheme.age.txt.pub
[^7]: https://github.com/nordtheme/.github/blob/main/data/nordtheme.gpg.asc
