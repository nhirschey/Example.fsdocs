This repository is an example of a starter website built using [FSharp.Formatting](http://fsprojects.github.io/FSharp.Formatting)

## Prerequisites

To work locally install
- .NET 6.
- FSharp.Formatting fsdocs tool.


## View the site locally.

The first time you run it, you need to restore the fsdocs tool by opening the terminal (powershell on windows, terminal.app on mac) and typing:

```
dotnet tool restore
```

Then, to view a live version of the site on a local web server type in the terminal:

```
dotnet fsdocs watch --eval
```
