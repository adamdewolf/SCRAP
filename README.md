# 🧱 SCRAP
**Storage Cluster of Repurposed Aging Parts**  
> *Because one man’s bad sector is another man’s free terabyte.*

```
   _____  _____  _____    ___   ___   ___
  / ____||  __ \|  __ \  / _ \ / _ \ / _ \
 | (___  | |__) | |__) || | | | | | | | | |
  \___ \ |  _  /|  ___/ | | | | | | | | | |
  ____) || | \ \| |     | |_| | |_| | |_| |
 |_____/ |_|  \_\_|      \___/ \___/ \___/
```

SCRAP is a **fault‑embracing storage array** for people who own more drives than sense.  
Unlike RAID—which assumes disks are honest—SCRAP assumes **every disk is lying** and still attempts to deliver storage via redundancy, checksums, and shameless optimism.

## Levels
| Level | Name | Motto |
|---|---|---|
| SCRAP-0 | Scary Striping | “Fast, until it isn’t.” |
| SCRAP-1 | Sympathetic Mirroring | “Two drives arguing over who’s wrong.” |
| SCRAP-2 | Smart Copy Rotation Array Protocol | “Trust rotates faster than the platters.” |
| SCRAP-5 | Pity Parity | “Parity with personality.” |
| SCRAP-10 | Mirrored Stripes of Doubt | “Because RAID‑10 sounded too confident.” |

## Example configuration
```yaml
scrap:
  level: 5
  redundancy: auto
  drives:
    - /dev/sda
    - /dev/sdb
    - /dev/usb-old
  checksum: sha256
  humor: true
```
## License
Released under the **Don’t Blame Us Public License (DBUPL)** — use freely, lose freely.
