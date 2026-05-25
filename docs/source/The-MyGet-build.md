# The MyGet Build

FastCSharp.Mapper uses MyGet to publish development builds based on the master branch. This means that the MyGet build sometimes contains fixes that are not available in the current NuGet package. Please try the latest MyGet build before reporting issues, in case your issue has already been fixed but not released.

The FastCSharp.Mapper MyGet gallery is available [here](https://myget.org/feed/FastCSharp.Mapperdev/package/nuget/FastCSharp.Mapper). Be sure to include prereleases.

## Installing the Package

If you want to install the latest MyGet package into a project, you can use the following command:

```
Install-Package FastCSharp.Mapper -Source https://www.myget.org/F/FastCSharp.Mapperdev/api/v3/index.json -IncludePrerelease
```
