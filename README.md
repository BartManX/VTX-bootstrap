# VTX Bootstrap

Chain bootstrap for [Vexta (VTX)](https://github.com/Caprimc/Vexta) mainnet — `blocks/` + `chainstate/` snapshot for faster initial sync.

## Latest

See [Releases](https://github.com/BartManX/VTX-bootstrap/releases) for the current zip.

| Field | Value |
|-------|-------|
| Height | 11709 |
| Best hash | `000000000000000492ab99f21d340b5ab5165263f040c11d121f9afd634c02d3` |
| File | `VTX-bootstrap-main-11709.zip` |
| SHA256 | `704efd871f5ebd22f12d1411842afa192675cdb0a91ec93bfbc72244aaaa05a0` |

## Install

1. Stop `vextad` if it is running
2. Extract `blocks/` and `chainstate/` into `~/.vexta/` (replace existing dirs)
3. Start `vextad` and allow verification to finish

Optional seeds:

```
addnode=87.106.99.23:19333
addnode=74.208.53.160:19333
addnode=51.75.129.57:19333
addnode=51.81.87.15:19333
```
