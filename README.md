# numbat-aqa
Overwrite constants to match AQA exam board

## Features
* Maths constants
* Physics constants

## Todo
* Units ([Missing Feature](https://github.com/kharchenkolab/numbat/issues/156))
* Chemistry / Biology

## Installation

Place [`aqa.nbt`](aqa.nbt) in one of these locations

| Location | Description |
| --- | --- |
| `$NUMBAT_MODULES_PATH` | This environment variable can point to a single directory or contain a `:` separated list of paths |
| `$HOME/.config/numbat/modules` | User module folder (Linux) |
| `$HOME/Library/Application Support/numbat` | User module folder (macOS) |
| `C:\Users\%username%\AppData\Roaming\numbat` | User module folder (Windows) |
| `/usr/share/numbat/modules` | System-wide module folder (Linux and macOS) |
| `C:\Program Files\numbat\modules`	| System-wide module folder (Windows) |

## Usage

```numbat
use aqa
```
