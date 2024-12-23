![license](https://img.shields.io/github/license/Joelrau/iw4x64-mod.svg)

# IW4x64-Mod

<br>

> [!NOTE]
> The game binaries are stored in an encrypted file system and have to be dumped to use IW4x64-Mod. This can be done using [UWPDumper](https://github.com/Wunkolo/UWPDumper).

## Compile from source

- Clone the Git repo. Do NOT download it as ZIP, that won't work.
- Update the submodules and run `premake5 vs2022` or simply use the delivered `generate.bat`.
- Build via solution file in `build\iw4x64-mod.sln`.

### Premake arguments

| Argument                    | Description                                    |
|:----------------------------|:-----------------------------------------------|
| `--copy-to=PATH`            | Optional, copy the EXE to a custom folder after build, define the path here if wanted. |
| `--dev-build`               | Enable development builds of the client. |

## Disclaimer

This software has been created purely for the purposes of academic research. It is not intended to be used to attack other systems. Project maintainers are not responsible or liable for misuse of the software. Use responsibly.
