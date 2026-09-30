# toggly-cli-dist

Single distribution repo for [toggly-cli](https://github.com/ops-ai/Toggly.FeatureManagement) (OPS-1580).

| Path / branch | Channel |
| --- | --- |
| `Formula/toggly-cli.rb` | Homebrew (`brew tap ops-ai/toggly-cli-dist`) |
| `toggly-cli.json` (repo root) | Scoop (`scoop bucket add toggly https://github.com/ops-ai/toggly-cli-dist`) |
| `gh-pages` | apt + yum/dnf package feeds |

Binaries and checksums always come from GitHub Releases (`cli-v*`) on `ops-ai/Toggly.FeatureManagement`. This repo only holds channel metadata / packages.
