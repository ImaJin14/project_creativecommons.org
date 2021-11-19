# project_creativecommons.org

Project to manage technical implementation of
[creativecommons.org](https://creativecommons.org/) (primary website)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-7-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/creativecommons/project_creativecommons.org)


## Status

1. Website: **Pre-release**
   - (For current/legacy repositories, see:
     [creativecommons/creativecommons.org][ccorgrepo]: Website parent project,
     legalcode and translations, and GitHub Issues for public help and support)

[ccorgrepo]: https://github.com/creativecommons/creativecommons.org


## Overview

This repository manages the primary website
([creativecommons.org](https://creativecommons.org/)) project. The primary
website consists of the following components and repositries:
1. WordPress
   - [creativecommons/creativecommons-base][ccbase]: Base WordPress theme for
     Creative Commons websites.
     - [creativecommons/wp-theme-creativecommons.org][wpthemeccorg]: New
       WordPress theme for Creative Commons website
   - URI Paths:
     - *default* (any URIs that don't match those listed, below)
2. Chooser
   - ~~[Creativecommons/chooser](https://github.com/creativecommons/chooser/):
     [WIP] The new and improved CC license selection tool.~~
     - #147
3. Legal Tools
   - [creativecommons/cc-legal-tools-app][legaltoolsapp] New license
     infrastructure for Creative Commons (generates Legal Tools Data)
   - [creativecommons/cc-legal-tools-data][legaltoolsdata]: CC Licenses data
     (static HTML, language files, etc.)
   - URI Paths:
     - `/characteristic`
     - `/choose`
     - `/licenses`
     - `/ns`
     - `/publicdomain`
     - `/rdf`
     - `/schema.rdf`
3. Misc Resources
   - [creativecommons/faq][faq]: Creative Commons FAQ page
   - [creativecommons/mp][mp]: Documentation for CC integration into
     user-generated content platforms
   - URI Paths:
     - `/faq`
     - `/platform/toolkit`

Infrastructure Management is handled by:
- [creativecommons/sre-salt-prime][saltprime]: Site Reliability Engineering /
  DevOps SaltStack configuration files

[wpthemeccorg]: https://github.com/creativecommons/wp-theme-creativecommons.org
[ccbase]: https://github.com/creativecommons/creativecommons-base
[legaltoolsapp]: https://github.com/creativecommons/cc-legal-tools-app
[legaltoolsdata]:https://github.com/creativecommons/cc-legal-tools-data
[faq]:https://github.com/creativecommons/faq
[mp]: https://github.com/creativecommons/mp
[saltprime]: https://github.com/creativecommons/sre-salt-prime/


## Development

See [`CONTRIBUTING.md`](CONTRIBUTING.md).


## Code of Conduct

[`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md):
> The Creative Commons team is committed to fostering a welcoming community.
> This project and all other Creative Commons open source projects are governed
> by our [Code of Conduct][code_of_conduct]. Please report unacceptable
> behavior to [conduct@creativecommons.org](mailto:conduct@creativecommons.org)
> per our [reporting guidelines][reporting_guide].

[code_of_conduct]:https://creativecommons.github.io/community/code-of-conduct/
[reporting_guide]:https://creativecommons.github.io/community/code-of-conduct/enforcement/


## License

- [`LICENSE`](LICENSE) (Expat/[MIT][mit] License)


## Contributing

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

See [`CONTRIBUTING.md`](CONTRIBUTING.md) and [Contributors ✨](#contributors-), below.


[mit]: http://www.opensource.org/licenses/MIT "The MIT License | Open Source Initiative"


### Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Akpjunior94"><img src="https://avatars.githubusercontent.com/u/56775903?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Akpan Abraham</b></sub></a><br /><a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=Akpjunior94" title="Code">💻</a></td>
    <td align="center"><a href="http://www.epacking.be"><img src="https://avatars.githubusercontent.com/u/19891785?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alain Seys</b></sub></a><br /><a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=alainseys" title="Code">💻</a> <a href="#infra-alainseys" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=alainseys" title="Documentation">📖</a></td>
    <td align="center"><a href="http://linkedin.com/in/brylie-christopher-oxley/"><img src="https://avatars.githubusercontent.com/u/17307?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Brylie Christopher Oxley</b></sub></a><br /><a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=brylie" title="Code">💻</a> <a href="https://github.com/creativecommons/project_creativecommons.org/pulls?q=is%3Apr+reviewed-by%3Abrylie" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/creativecommons/project_creativecommons.org/issues?q=author%3Abrylie" title="Bug reports">🐛</a> <a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=brylie" title="Documentation">📖</a></td>
    <td align="center"><a href="https://github.com/MuluhGodson"><img src="https://avatars.githubusercontent.com/u/40151808?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MuluhGodson</b></sub></a><br /><a href="#design-MuluhGodson" title="Design">🎨</a> <a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=MuluhGodson" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/cillacode"><img src="https://avatars.githubusercontent.com/u/54538525?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Priscillia Umeakuekwe</b></sub></a><br /><a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=cillacode" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/shailee-m"><img src="https://avatars.githubusercontent.com/u/10625985?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Shailee Mehta</b></sub></a><br /><a href="https://github.com/creativecommons/project_creativecommons.org/pulls?q=is%3Apr+reviewed-by%3Ashailee-m" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://zehta.me/"><img src="https://avatars.githubusercontent.com/u/691322?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Timid Robot Zehta</b></sub></a><br /><a href="https://github.com/creativecommons/project_creativecommons.org/pulls?q=is%3Apr+reviewed-by%3ATimidRobot" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=TimidRobot" title="Documentation">📖</a> <a href="https://github.com/creativecommons/project_creativecommons.org/commits?author=TimidRobot" title="Code">💻</a> <a href="#infra-TimidRobot" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/creativecommons/project_creativecommons.org/issues?q=author%3ATimidRobot" title="Bug reports">🐛</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
