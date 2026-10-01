# Kept Bibles

Public-domain Bible texts prepared for the Kept app: one SQLite database per translation
(gzip), plus `manifest.json` listing each file with its size and SHA-256.

Files are attached to the releases (`bibles-v<schema>`), not committed to the repository.

| id | language | name | English name | source |
|---|---|---|---|---|
| WEB | en | World English Bible | World English Bible | https://ebible.org/Scriptures/engwebp_usfm.zip |
| KJV | en | King James Version | King James Version | https://ebible.org/Scriptures/eng-kjv2006_usfm.zip |
| RV1909 | es | Reina-Valera 1909 | Reina-Valera 1909 | https://ebible.org/Scriptures/spaRV1909_usfm.zip |
| BPM | pt | Bíblia Portuguesa Mundial | World Portuguese Bible | https://ebible.org/Scriptures/porbrbsl_usfm.zip |
| LUT1912 | de | Lutherbibel 1912 | Luther Bible 1912 | https://ebible.org/Scriptures/deu1912_usfm.zip |
| CUVS | zh-Hans | 和合本（简体） | Chinese Union Version (Simplified) | https://ebible.org/Scriptures/cmn-cu89s_usfm.zip |
| CUVT | zh-Hant | 和合本（繁體） | Chinese Union Version (Traditional) | https://ebible.org/Scriptures/cmn-cu89t_usfm.zip |
| RIV1927 | it | Riveduta 1927 | Italian Riveduta 1927 | https://ebible.org/Scriptures/ita1927_usfm.zip |
| SV1917 | nl | De Heilige Schrift 1917 | Dutch Bible 1917 | https://ebible.org/Scriptures/nld_usfm.zip |
| VI1923 | vi | Kinh Thánh 1923 | Vietnamese Bible 1923 | https://ebible.org/Scriptures/vie1934_usfm.zip |
| JFB | ja | フリーダム・バイブル | Japanese Freedom Bible | https://ebible.org/Scriptures/jpnm_usfm.zip |
| LSG | fr | Louis Segond 1910 | Louis Segond 1910 | https://ebible.org/Scriptures/fraLSG_usfm.zip |
| SYN | ru | Синодальный перевод | Russian Synodal Bible | https://ebible.org/Scriptures/russyn_usfm.zip |
| UKR1871 | uk | Біблія в перекладі Куліша | Ukrainian Bible (Kulish) | https://ebible.org/Scriptures/ukr1871_usfm.zip |

All texts are in the **public domain**. They were converted from the USFM published by
[eBible.org](https://ebible.org) (pinned by checksum) and checked against the canon and
against known passages. The King James Version is under Crown patent in the United Kingdom
and is not offered there.

Every translation is stored in the English (KJV) verse numbering, so a reference means the
same passage in each. Translations numbered differently (Louis Segond, Synodal, Kulish) were
renumbered with the Paratext versification files from
[SIL libpalaso](https://github.com/sillsdev/libpalaso) (MIT License).

The Berean Standard Bible (also public domain, from bereanbible.com) is bundled in the app.
