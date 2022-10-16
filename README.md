# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

OS | Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed | GB free
---|:--------------------:|:-----------------:|:---------------:|---------:|-------:
ubuntu-18.04 |  |  |  | 7 | 38
ubuntu-18.04 |  |  | true | 7 | 38
ubuntu-18.04 |  | true |  | 10 | 41
ubuntu-18.04 |  | true | true | 10 | 41
ubuntu-18.04 | true |  |  | 21 | 52
ubuntu-18.04 | true |  | true | 21 | 52
ubuntu-18.04 | true | true |  | 23 | 54
ubuntu-18.04 | true | true | true | 23 | 54
ubuntu-20.04 |  |  |  | 7 | 39
ubuntu-20.04 |  |  | true | 7 | 39
ubuntu-20.04 |  | true |  | 9 | 41
ubuntu-20.04 |  | true | true | 65 | 97
ubuntu-20.04 | true |  |  | 18 | 50
ubuntu-20.04 | true |  | true | 18 | 50
ubuntu-20.04 | true | true |  | 20 | 52
ubuntu-20.04 | true | true | true | 20 | 52
ubuntu-22.04 |  |  |  | 7 | 48
ubuntu-22.04 |  |  | true | 7 | 48
ubuntu-22.04 |  | true |  | 7 | 48
ubuntu-22.04 |  | true | true | 7 | 48
ubuntu-22.04 | true |  |  | 18 | 59
ubuntu-22.04 | true |  | true | 18 | 59
ubuntu-22.04 | true | true |  | 18 | 59
ubuntu-22.04 | true | true | true | 18 | 59
