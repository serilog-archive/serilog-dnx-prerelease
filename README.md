# Serilog.Dnx.Prerelease

Pre-release support for the DNX (.NET 5) runtime environment for Serilog **that will be retired** when VS2015 hits RTM.

## What

Sinks like Console, File and so-on that you'd expect in the core Serilog package, but ready to roll with the VS2015 RCs.

## Why?

.NET 5, including ASP.NET 5, DNX and the CoreCLR runtime, will eventually be supported in the core _Serilog_ NuGet package.

Until VS2015 reaches RTM however, doing this in the core project (e.g. on a branch) will make it inconvenient to release. Instead, this workspace provides a nice low-friction way to get support out there.
