mynewcli2
=========



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/mynewcli2.svg)](https://npmjs.org/package/mynewcli2)
[![Codecov](https://codecov.io/gh/baronTommy/mynewcli2/branch/master/graph/badge.svg)](https://codecov.io/gh/baronTommy/mynewcli2)
[![Downloads/week](https://img.shields.io/npm/dw/mynewcli2.svg)](https://npmjs.org/package/mynewcli2)
[![License](https://img.shields.io/npm/l/mynewcli2.svg)](https://github.com/baronTommy/mynewcli2/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g mynewcli2
$ mynewcli2 COMMAND
running command...
$ mynewcli2 (-v|--version|version)
mynewcli2/0.0.0 darwin-x64 node-v13.6.0
$ mynewcli2 --help [COMMAND]
USAGE
  $ mynewcli2 COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`mynewcli2 hello [FILE]`](#mynewcli2-hello-file)
* [`mynewcli2 help [COMMAND]`](#mynewcli2-help-command)

## `mynewcli2 hello [FILE]`

describe the command here

```
USAGE
  $ mynewcli2 hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ mynewcli2 hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/baronTommy/mynewcli2/blob/v0.0.0/src/commands/hello.ts)_

## `mynewcli2 help [COMMAND]`

display help for mynewcli2

```
USAGE
  $ mynewcli2 help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_
<!-- commandsstop -->
