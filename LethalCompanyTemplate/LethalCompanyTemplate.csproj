<Project Sdk="Microsoft.NET.Sdk">

    <PropertyGroup>
        <TargetFramework>netstandard2.1</TargetFramework>
        <AssemblyName>LethalCompanyTemplate</AssemblyName>
        <Description>A template for Lethal Company</Description>
        <Version>1.0.0</Version>
        <AllowUnsafeBlocks>true</AllowUnsafeBlocks>
        <LangVersion>latest</LangVersion>
    </PropertyGroup>

    <ItemGroup>
        <PackageReference Include="BepInEx.Analyzers" Version="1.*" PrivateAssets="all"/>
        <PackageReference Include="BepInEx.Core" Version="5.*" />
        <PackageReference Include="BepInEx.PluginInfoProps" Version="1.*"/>
        <PackageReference Include="UnityEngine.Modules" Version="2022.3.9" IncludeAssets="compile" />
    </ItemGroup>

    <ItemGroup Condition="'$(TargetFramework.TrimEnd(`0123456789`))' == 'net'">
        <PackageReference Include="Microsoft.NETFramework.ReferenceAssemblies" Version="1.0.2" PrivateAssets="all"/>
    </ItemGroup>
</Project>
