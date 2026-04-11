# daylight-key-generator

Windows WPF desktop tool that generates license keys from an 8-digit machine ID for remote controlled machines.

## Platform

- .NET Framework 4.7.2
- WPF (C#)

## Build

Open `DayLightKeyGenerator.sln` in Visual Studio and build, or from the command line:

```
msbuild DayLightKeyGenerator.sln /p:Configuration=Release
```

## Usage

Run the built executable, enter the 8-digit machine ID, and press Generate to produce the license key.
