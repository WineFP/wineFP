# WineFP
Flatpak-ing Microsoft Windows applications with Wine.

## Goals
* Package `wine` applications via `flatpak`
* Make installing and running applications Just Work<sup>TM</sup>

## Repos
* [wineFP-sdk-images](https://github.com/WineFP/wineFP-sdk): The Sdk & Platform for `wineFP`
* [applications](https://github.com/WineFP/applications): A collection of flatpak manifest for building Microsoft Windows applications via `wineFP`

### Building
To get started with winepak you first need to build & install the Sdk & Platform, instructions can be found on the [wineFP-sdk-images](https://github.com/WineFP/wineFP-sdk) repo.

Next pick an application to build & install. A list of them with instructions can be found in the [applications](https://github.com/WineFP/applications) repo. Take note of the Platform branch the application uses. Most games require the `staging` branch of Sdk/Platform.
