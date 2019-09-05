## Overview
It's simplely inherit from [kubectx](https://kubectx.dev), here is the [repo](https://github.com/ahmetb/kubectx)

# `azx`

```bash
USAGE:
  azx                       : list the contexts
  azx <NAME>                : switch to context <NAME>
  azx -c, --current         : show the current context name

  azx -h,--help             : show this message
```

# `Usage`

```bash
$azx mytest

$azx "mytest(123)"

$azx mytest\(123\)

$azx -c
mytest(123)
```