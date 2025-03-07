# v2.8.8 (Wed May 12 2021)

:tada: This release contains work from new contributors! :tada:

Thanks for all your work!

:heart: Jimmy Andrade ([@jimmyandrade](https://github.com/jimmyandrade))

:heart: Jack Howard ([@JackHowa](https://github.com/JackHowa))

#### 🐛 Bug Fix

- fix: make it possible to deploy from SOURCE_BRANCH [#102](https://github.com/storybookjs/storybook-deployer/pull/102) ([@jimmyandrade](https://github.com/jimmyandrade))
- build: set up codeql analysis [#95](https://github.com/storybookjs/storybook-deployer/pull/95) ([@jimmyandrade](https://github.com/jimmyandrade))

#### 🔩 Dependency Updates

- fix(deps): bump lodash from 4.17.19 to 4.17.21 [#108](https://github.com/storybookjs/storybook-deployer/pull/108) ([@jimmyandrade](https://github.com/jimmyandrade))
- fix(deps): bump hosted-git-info from 2.8.5 to 2.8.9 [#109](https://github.com/storybookjs/storybook-deployer/pull/109) ([@jimmyandrade](https://github.com/jimmyandrade))
- build(deps): bump gitlog from 4.0.3 to 4.0.4 [#106](https://github.com/storybookjs/storybook-deployer/pull/106) ([@jimmyandrade](https://github.com/jimmyandrade))
- fix(deps): bump y18n from 4.0.0 to 4.0.1 [#105](https://github.com/storybookjs/storybook-deployer/pull/105) ([@jimmyandrade](https://github.com/jimmyandrade))
- chore(dev-deps): bump ini from 1.3.5 to 1.3.8 [#99](https://github.com/storybookjs/storybook-deployer/pull/99) ([@jimmyandrade](https://github.com/jimmyandrade))
- chore: Update auto dependencies to ensure no security node-fetch issues [#96](https://github.com/storybookjs/storybook-deployer/pull/96) ([@JackHowa](https://github.com/JackHowa))

#### Authors: 2

- Jack Howard ([@JackHowa](https://github.com/JackHowa))
- Jimmy Andrade ([@jimmyandrade](https://github.com/jimmyandrade))

---

# v2.8.7 (Tue Oct 06 2020)

:tada: This release contains work from a new contributor! :tada:

Thank you, Jimmy Andrade ([@jimmyandrade](https://github.com/jimmyandrade)), for all your work!

#### 🐛 Bug Fix

- fix(deps): bump lodash from 4.17.15 to 4.17.19 [#89](https://github.com/storybookjs/storybook-deployer/pull/89) ([@jimmyandrade](https://github.com/jimmyandrade))

#### Authors: 1

- Jimmy Andrade ([@jimmyandrade](https://github.com/jimmyandrade))

---

# v2.8.6 (Tue May 12 2020)

:tada: This release contains work from a new contributor! :tada:

Thank you, Jeri Sommers ([@sojeri](https://github.com/sojeri)), for all your work!

#### 🐛 Bug Fix

- fix yargs-parser & kind-of vulnerabilities [#84](https://github.com/storybookjs/storybook-deployer/pull/84) ([@sojeri](https://github.com/sojeri))

#### Authors: 1

- Jeri Sommers ([@sojeri](https://github.com/sojeri))

---

# v2.8.5 (Thu Apr 02 2020)

:tada: This release contains work from a new contributor! :tada:

Thank you, Fraser Killip ([@FraserKillip](https://github.com/FraserKillip)), for all your work!

#### 🐛 Bug Fix

- Remove check for Github.com when using an access token [#80](https://github.com/storybookjs/storybook-deployer/pull/80) ([@FraserKillip](https://github.com/FraserKillip))

#### Authors: 1

- Fraser Killip ([@FraserKillip](https://github.com/FraserKillip))

---

# v2.8.4 (Thu Apr 02 2020)

:tada: This release contains work from a new contributor! :tada:

Thank you, Lucas Machado ([@luksm](https://github.com/luksm)), for all your work!

#### 🐛 Bug Fix

- fix: Updating git-url-parser [#68](https://github.com/storybookjs/storybook-deployer/pull/68) ([@luksm](https://github.com/luksm))

#### ⚠️  Pushed to `master`

- update lock file ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### 🏠 Internal

- Add automated releases and contributors [#81](https://github.com/storybookjs/storybook-deployer/pull/81) ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 2

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Lucas Machado ([@luksm](https://github.com/luksm))

---

# Change Log

### v2.8.2

21-Feb-2020

- Allow no aws profile via `--aws-profile=NONE`

### v1.2.0

09-Sep-2016

- Add a trailing slash to the URL where it's the correct GH pages URL.

### v1.1.0

08-Aug-2016

- Fix issue when there's already a build-storybook command. See: [#1](https://github.com/kadirahq/storybook-deployer/issues/1).
- Add some better logs when executing commands.
- Now we create a random directory to build the output.

### v1.0.0

07-May-2016

- Initial Release
