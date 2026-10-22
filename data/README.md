# data/

-   `raw/` holds raw inputs and is **not committed** (see `.gitignore`). Record each raw file here: source, date obtained, and checksum.
-   `processed/` holds small derived tables that are safe to commit.

## Raw data record

+--------------------+-------------------------------+------------+----------------------------------+
| File               | Source                        | Date       | md5                              |
+====================+===============================+============+==================================+
| PB01_L01_S3_R1_001 | Salipante lab transfer folder | 08/19/2026 | ```                              |
|                    |                               |            | c38b8710bbd8a4517ddbcef3eca0aed4 |
|                    |                               |            | ```                              |
+--------------------+-------------------------------+------------+----------------------------------+
| PB01_L01_S3_R2_001 | Salipante lab transfer folder | 8/19/26    | ```                              |
|                    |                               |            | 8a46f81e72e3e50915a64abba122e382 |
|                    |                               |            | ```                              |
+--------------------+-------------------------------+------------+----------------------------------+

Generate checksums with `md5sum data/raw/* > data/raw-checksums.txt` and commit that file.
