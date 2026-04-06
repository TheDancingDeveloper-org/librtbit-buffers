# librtbit-buffers

Utils to work with byte buffers in librtbit source code.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |
| librtbit-bencode (lib) | git | v0.1.0 |
| librtbit-core (lib) | git | v0.1.0 |
| librtbit-peer-protocol (lib) | git | v0.1.0 |
| librtbit-dht (lib) | git | v0.1.0 |
| librtbit-tracker-comms (lib) | git | v0.1.0 |

### Depends On

- **librtbit-clone-to-owned** (git, v0.1.0) — for CloneToOwned trait

## Public API

- `ByteBuf<'a>` — borrowed byte buffer with Display/Debug
- `ByteBufOwned` — owned byte buffer with Display/Debug
- `ByteBufT` trait — common interface for both variants
