# recogen

Generate React components by templates nice and easy

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/recogen.svg)](https://npmjs.org/package/recogen)
[![CircleCI](https://circleci.com/gh/Hennessy811/recogen/tree/master.svg?style=shield)](https://circleci.com/gh/Hennessy811/recogen/tree/master)
[![Downloads/week](https://img.shields.io/npm/dw/recogen.svg)](https://npmjs.org/package/recogen)
[![License](https://img.shields.io/npm/l/recogen.svg)](https://github.com/Hennessy811/recogen/blob/master/package.json)

<!-- toc -->
* [recogen](#recogen)
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->
```sh-session
$ npm install -g recogen
$ recogen COMMAND
running command...
$ recogen (-v|--version|version)
recogen/0.1.3 darwin-x64 node-v12.18.4
$ recogen --help [COMMAND]
USAGE
  $ recogen COMMAND
...
```
<!-- usagestop -->

# Commands

<!-- commands -->
* [`recogen g`](#recogen-g)
* [`recogen help [COMMAND]`](#recogen-help-command)

## `recogen g`

Generate React components

```
USAGE
  $ recogen g

OPTIONS
  -h, --help  show CLI help

EXAMPLE
  $ recogen g
       Enter component name?: MyComponent
       ? Select styling module: (Use arrow keys)
       > .less
         .scss
         .css
         no styles
       Use TypeScript? (Y/n)
       Generating...... done
```

_See code: [src/commands/g.ts](https://github.com/Hennessy811/recogen/blob/v0.1.3/src/commands/g.ts)_

## `recogen help [COMMAND]`

display help for recogen

```
USAGE
  $ recogen help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.0/src/commands/help.ts)_
<!-- commandsstop -->
