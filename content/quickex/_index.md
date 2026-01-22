---
title:
toc: false
---

## Low Level Examples

Low level API examples for high performance applications. These examples focus on exposing the low level control options.

Typical .csproj for all code snippets:

```csharp
<Project Sdk="Microsoft.NET.Sdk">

    <PropertyGroup>
        <OutputType>Exe</OutputType>
        <TargetFramework>net10.0</TargetFramework>
        <ImplicitUsings>enable</ImplicitUsings>
        <Nullable>enable</Nullable>
        <AllowUnsafeBlocks>true</AllowUnsafeBlocks>
    </PropertyGroup>

    <ItemGroup>
      <PackageReference Include="URocket" Version="x.y.z" />
    </ItemGroup>

</Project>

```

Replace x.y.z for the latest URocket nuget available.