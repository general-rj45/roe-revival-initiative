# Ring of Elysium — Asset Unpacking Research

## Objective

Document the structure of Ring of Elysium's asset archives (`.sfc`, `.vfs`) for **preservation and research purposes only**.

## Tools Used

- [QuickBMS](http://quickbms.com/) — universal file extractor
- Scripts:
  - `qq_sfc.bms` — for `.sfc` archives
  - `dzs_qq.bms` — for `.vfs` archives

## Current Findings

- Archives are encrypted with custom Tencent algorithms
- Extracted files lose original filenames → manual identification required
- Some files are Lua scripts (game logic, UI, item configs)
- Server-side logic is **not present** in client files

## Known Issues

- Recent patches may have changed archive structure
- Some archives fail to extract with standard scripts

## References

- [ZenHAX Forum — Ring of Elysium thread](http://zenhax.com/viewtopic.php?f=9&t=10346)

---

*If you have additional tools or findings, please contribute.*
