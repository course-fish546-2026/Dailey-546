# data/

-   `raw/` holds raw inputs and is **not committed** (see `.gitignore`). Record each raw file here: source, date obtained, and checksum.
-   `processed/` holds small derived tables that are safe to commit.

## Raw data record

| File                       | Source                        | Date       | md5 |
|----------------------------|-------------------------------|------------|-----|
| PB01_END01_S1_R1_001.fastq | Salipante lab transfer folder | 08/19/2026 |     |

Generate checksums with `md5sum data/raw/* > data/raw-checksums.txt` and commit that file.
