# ForEvolve.PhantomJs.Dependencies

This repository contains the PhantomJS binaries for Windows, MacOS and Linux, used by the ForEvolve framework.

It has been created to lighten the main repository, keeping the binaries out of it. Moreover, it is an optional package.

> This package is only used to distribute the executable files.

## How to install?

Run one of the following command

```PowerShell
Install-Package ForEvolve.PhantomJs.Dependencies
```

or

```PowerShell
dotnet add package ForEvolve.PhantomJs.Dependencies
```

Please also note that this package is not part of the `ForEvolve.App` due to it's size (and it is optional).
See [ForEvolve/MetaPackages](https://github.com/ForEvolve/MetaPackages) for more information.

## Licenses

The current project is under MIT while the PhantomJs binaries are under BSD.

See the LICENSE file for more details.
