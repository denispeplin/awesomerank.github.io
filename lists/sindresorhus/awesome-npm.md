<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="sindresorhus/awesome-npm">sindresorhus/awesome-npm</a> with ranks
</p>
---
# awesome npm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome) [<img src="https://github.com/npm/logos/blob/7fb0bc425e0dac1bab065217c4ed595594448db4/npm-transparent.png" width="200" align="right" alt="npm">](https://www.npmjs.com)

> Awesome [npm](https://www.npmjs.com) resources and tips

You might also like [awesome-nodejs ★17249](sindresorhus/awesome-nodejs).

*Please read the [contribution guidelines](https://github.com/sindresorhus/awesome-npm/blob/master/contributing.md) before contributing.*


## Contents

- [Articles](#articles)
- [Tools](#tools)
- [Packages](#packages)
- [Clients](#clients)
- [Tips](#tips)
- [FAQ](#faq)
- [Community](#community)
- [Documentation](#documentation)
- [Support](#support)


## Articles

- [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328)
- [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - Write programs that do one thing and do it well.
- [Writing small modules](http://substack.net/how_I_write_modules)
- [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/) *(Must read!)*
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [Offline installation of npm packages](https://addyosmani.com/blog/using-npm-offline/)
- [Task automation with npm run](http://substack.net/task_automation_with_npm_run)
- [How to use npm as a build tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
- [Install npm packages globally without sudo on macOS and Linux](https://github.com/sindresorhus/guides/blob/master/npm-global-without-sudo.md)
- [Optimizing the footprint of an npm package](https://medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
- [The Art of Node ★6414](maxogden/art-of-node#modules) - An introduction to Node.js and client-side development with npm.
- [Why npm scripts?](https://css-tricks.com/why-npm-scripts/) - An introduction to npm scripts with common packages and scripts, as well as a boilerplate project.


## Tools

### Web

- [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
- [npmsearch](http://npmsearch.com) - Fast package search with ranking based on metrics like stars, dependents, release frequency, etc.
- [node-modules](http://node-modules.com) - Personalized package search based on your GitHub social graph.
- [NodeICO](https://nodei.co/) - Package badges.
- [Libraries.io](https://libraries.io/npm) - Package discovery.
- [npm-stat](http://npm-stat.com) - Statistics charts for packages.
- [npmgraph](http://npm.anvaka.com) - Visualization of dependencies.
- [npm trends](http://www.npmtrends.com) - Compare package download counts over time.
- [npm-compare](https://npmcompare.com) - Easily search and compare packages.
- [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - npm users by downloads.
- [npm semver calculator](http://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.
- [npm-stats](http://www.npm-stats.com) - Displays metrics about packages.
- [greenkeeper.io](http://greenkeeper.io) - Automates dependency updates through pull requests.
- [ghub.io](http://ghub.io) - Redirects to the GitHub repo of an npm package.
- [npm addict](https://npmaddict.com) - Your daily injection of npm packages.
- [npm discover](http://www.npmdiscover.com) - Discover what packages are commonly used together.
- [snyk](https://snyk.io) - Find, fix and monitor for known vulnerabilities in npm dependencies.

### Browser extensions

- [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension to navigate across npm packages on GitHub with ease.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to explore npm dependencies on GitHub repos.

### CLI

- [zsh-better-npm-completion ★56](lukechilds/zsh-better-npm-completion) - Better ZSH completion for npm.


## Packages

### Publishing

- [np ★2191](sindresorhus/np) - A better `npm publish`.
- [publish-please ★706](inikulin/publish-please) - Publish packages safely and gracefully.
- [npm-release](https://github.com/phuu/npm-release) - Making releasing to npm so easy a kitten could probably do it™.
- [pkgfiles ★48](timoxley/pkgfiles) - List all files which would be published in a package.
- [semantic-release ★2522](semantic-release/semantic-release) - Fully automated package publishing.

### Registry

- [npm-name ★94](sindresorhus/npm-name-cli) - Check whether a package name is available on npm.
- [package-json ★48](sindresorhus/package-json) - Get the package.json of a package from the npm registry.
- [latest-version ★25](sindresorhus/latest-version-cli) - Get the latest version of an npm package.
- [npm-keyword ★28 ⏳1Y](sindresorhus/npm-keyword) - Get a list of npm packages with a certain keyword.
- [npm-user ★35 ⏳1Y](sindresorhus/npm-user) - Get user info of an npm user.
- [npm-email ★12 ⏳1Y](sindresorhus/npm-email) - Get the email of an npm user.
- [npm-user-packages ★2](kevva/npm-user-packages-cli) - Get packages by an npm user.
- [dpn ★23](gillstrom/dpn) - Get the dependents of a user's npm packages.
- [npm-stats ★45 ⏳1Y](hughsk/npm-stats) - Get data from an npm registry.
- [npm-cli-login ★10](postmanlabs/npm-cli-login) - Log in to npm.
- [nrm ★646](Pana/nrm) - Registry manager.
- [npm-register ★221](dickeyxxx/npm-register) - Easy to set up and maintain npm registry and proxy.
- [verdaccio ★768](verdaccio/verdaccio) - Lightweight private npm proxy registry.

### Other

- [npm-home ★49](sindresorhus/npm-home) - Open the npm page of a package.
- [gh-home ★78](sindresorhus/gh-home) - Open the GitHub page of a package.
- [david ★741](alanshaw/david) - Check if your package dependencies are out of date.
- [npm-check ★3373](dylang/npm-check) - Check for outdated, incorrect, and unused dependencies, as well as interactive update.
- [npm-upgrade ★69](th0r/npm-upgrade) - Update outdated npm dependencies interactively.
- [npm-shrinkwrap ★772](uber/npm-shrinkwrap) - A consistent shrinkwrap tool.
- [npm-windows-upgrade ★1103](felixrieseberg/npm-windows-upgrade) - Upgrade npm on Windows.
- [generator-nm ★450](sindresorhus/generator-nm) - Scaffold out an npm package.
- [pkg-up ★26](sindresorhus/pkg-up) - Find the closest package.json file.
- [read-pkg-up ★41](sindresorhus/read-pkg-up) - Read the closest package.json file.
- [normalize-package-data ★64](npm/normalize-package-data) - Normalize package metadata.
- [pkg-conf ★47](sindresorhus/pkg-conf) - Get namespaced config from the closest package.json.
- [npm-run-path ★33](sindresorhus/npm-run-path) - Run locally installed binaries in the terminal by name like with global ones.
- [local-npm](https://github.com/nolanlawson/local-npm) - Use npm [offline](https://addyosmani.com/blog/using-npm-offline/).
- [npe ★34](zeke/npe) - CLI for inspecting and editing properties in package.json.
- [engine-deps ★20 ⏳1Y](samccone/engine-deps) - Manage Node.js version specific dependencies with ease.
- [enpeem-search ★3 ⏳1Y](amovah/enpeem-search) - Search packages by scraping the npm web search.
- [npm-issues ★46 ⏳1Y](seanzarrin/npm-issues) - Search known issues of all your packages at once.
- [john ★44](davej/john) - Make npm3's flat dependencies easier to find and sort.
- [ntl ★374](ruyadorno/ntl) - Interactive CLI menu to list & run npm tasks.
- [decheck ★8](egoist/decheck) - Explore dependencies of npm packages in the command-line.
- [shrinkpack ★744](JamieMason/shrinkpack) - Lock down your dependencies and install offline.
- [redrun ★41](coderaiser/redrun) - Expand scripts from package.json to improve execution speed.
- [package-size ★58](egoist/package-size) - Get the bundle size of an npm package.


## Clients

- [yarn ★25413](yarnpkg/yarn) - Fast, reliable, and secure dependency management.
- [npm ★12573](npm/npm) - The official client.
- [pnpm ★2372](pnpm/pnpm) - Fast, disk space efficient npm installs.
- [ied ★1938](alexanderGugel/ied) - Faster npm.


## Tips

### Update to the latest npm version

```
$ npm install --global npm
```

*[Windows users, read more. ★1103](felixrieseberg/npm-windows-upgrade)*

### Command aliases

- `npm i ` → `npm install`
- `npm i -D` → `npm install --save-dev`
- `npm t` → `npm test`
- `npm it` → `npm install && npm test`
- `npm r` → `npm uninstall`

### Shell aliases

Speed up your common npm tasks.

In your `.zshrc`/`.bashrc`:

```sh
alias ni='npm install'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias ns='npm start'
alias nf='npm cache clean && rm -rf node_modules && npm install'
alias nlg='npm list --global --depth=0'
```


### Add to package.json when installing

You can have npm add packages to package.json when installing by specifying the `--save`/`-S` flag for `dependencies` and `--save-dev`/`-D` for `devDependencies`:

```
$ npm install --save chalk
```

### Run scripts

You can easily [run scripts](https://docs.npmjs.com/cli/run-script) using npm by adding them to the `"scripts"` field in package.json and run them with `npm run <script-name>`. Run `npm run` to see available scripts. Binaries of locally install packages are made available in the [PATH](https://en.wikipedia.org/wiki/PATH_(variable)), so you can run them by name. `npm run foo` will also run `prefoo` and `postfoo` if defined.

```json
{
	"name": "awesome-package",
	"scripts": {
		"cat": "cat-names"
	},
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

```
$ npm run cat
Max
```

All package.json properties are [exposed](https://docs.npmjs.com/misc/scripts#packagejson-vars) as environment variables:

```json
{
	"name": "awesome-package",
	"scripts": {
		"name": "echo $npm_package_name"
	}
}
```

```
$ npm run name
awesome-package
```


### Link local packages

Sometimes it can be useful to have a local version of a package as a dependency. You can use `npm link` to link one local package into another. Run `npm link` in the package you want to use. This creates a global reference. Then go into your original package and run `npm link <package-name>` to link in the other package.

```
$ cd rainbow
$ npm link
$ cd ../unicorn
$ npm link rainbow
```

You can now use `rainbow` as a dependency in the `unicorn` package.

### Install a package from GitHub

npm supports using a shorthand for installing a package directly from a GitHub repo:

```
$ npm install sindresorhus/chalk
```

Let's target a specific commit as master is a moving target:

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

Specify either a commit SHA, branch, tag, or nothing.


### Install a specific version of a package

```
$ npm install chalk@1.0.0
```


### List top-level installed packages and their version

```
$ npm ls --depth=0
```

### Command help

Get help docs for a command:

```
$ npm help <command>
```

Example:

```
$ npm help install
```

### Standalone version of a package

Quickly get a standalone version of a package that is browserified and usable in the browser.

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

Examples:

- https://wzrd.in/standalone/object-assign
- https://wzrd.in/standalone/object-assign@4.0.0

Great for prototyping, but download the file or use Browserify yourself for production.


## FAQ

- [Check in node_modules vs. shrinkwrap](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
- [What is the difference between Bower and npm?](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
- [What does `^` mean in package.json versioning?](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
- [Find the version of an installed npm package](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
- [What's the difference between dependencies, devDependencies, and peerDependencies in package.json?](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)


## Community

- [`#npm` on Freenode](http://webchat.freenode.net/?channels=npm)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/npm)
- [Reddit](https://www.reddit.com/r/npm)
- [Twitter](https://twitter.com/npmjs)
- [Blog](http://blog.npmjs.org)


## Documentation

- [Official](https://docs.npmjs.com)
- [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting)
- [Semantic versioning](https://docs.npmjs.com/getting-started/semantic-versioning)
- [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
- [package.json](https://docs.npmjs.com/files/package.json)
- [npm run script](https://docs.npmjs.com/cli/run-script)
- [Stats API ★177](npm/download-counts)


## Support

- [Issue tracker](https://github.com/npm/npm/issues)
- [Twitter](https://twitter.com/npm_support)
- [Contact form](https://www.npmjs.com/support)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="sindresorhus/awesome-npm">sindresorhus/awesome-npm</a> with ranks
</p>