| Component            | Path                       | Offset (hex) | Offset (decimal) | Notes                                        |
| -------------------- | -------------------------- | ------------ | ---------------- | -------------------------------------------- |
| Bootloader           | `bootloader.bin`           | `0x0000`     | `0`              | Always starts at the beginning of flash      |
| Partition Table      | `partition-table.bin`      | `0x8000`     | `32768`          | ESP-IDF standard location                    |
| Application Firmware | `BoostedBreakReceiver.bin` | `0x10000`    | `65536`          | First app partition unless otherwise defined |
