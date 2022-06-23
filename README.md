# wkentaro-labelme-flatpak

| License | Versioning |
| ------- | ---------- |
| [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) | [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) |

Wkentaro's Labelme installation via Flatpak.


## Building

Build using the following command:
```
flatpak run org.flatpak.Builder --user --install --force-clean build-dir io.extra2000.wkentaro.labelme.yml
```


## Running

```
flatpak run io.extra2000.wkentaro.labelme
```
