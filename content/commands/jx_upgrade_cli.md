---
date: 2019-02-05T14:48:28Z
title: "jx upgrade cli"
slug: jx_upgrade_cli
url: /commands/jx_upgrade_cli/
---
## jx upgrade cli

Upgrades the command line applications - if there are new versions available

### Synopsis

Upgrades the Jenkins X command line tools if there is a newer release

```
jx upgrade cli [flags]
```

### Examples

```
  # Upgrades the Jenkins X CLI tools
  jx upgrade cli
```

### Options

```
  -b, --batch-mode                In batch mode the command never prompts for user input
      --headless                  Enable headless operation if using browser automation
  -h, --help                      help for cli
      --install-dependencies      Should any required dependencies be installed automatically
      --log-level string          Logging level. Possible values - panic, fatal, error, warning, info, debug. (default "info")
      --no-brew                   Disables the use of brew on macOS to install or upgrade command line dependencies
      --pull-secrets string       The pull secrets the service account created should have (useful when deploying to your own private registry): provide multiple pull secrets by providing them in a singular block of quotes e.g. --pull-secrets "foo, bar, baz"
      --skip-auth-secrets-merge   Skips merging a local git auth yaml file with any pipeline secrets that are found
      --verbose                   Enable verbose logging
  -v, --version string            The specific version to upgrade to
```

### SEE ALSO

* [jx upgrade](/commands/jx_upgrade/)	 - Upgrades a resource

###### Auto generated by spf13/cobra on 5-Feb-2019
