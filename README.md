# Kept Bibles

Openly licensed Bible texts prepared for the Kept app: one SQLite database per translation
(gzip). 129 translations in 78 languages.

- `manifest-v2.json` lists every translation with its license and, for Creative Commons texts,
  the credit the license requires (shown in the app).
- `manifest.json` lists only the public-domain ones (read by app builds before 2026-10-04).

Files are attached to the releases (`bibles-v<schema>`), not committed to the repository.

Every text is public domain or under CC BY / BY-SA / BY-ND 4.0, which allow redistribution
in a commercial app. Kept removes footnotes and cross references and aligns verse numbers to
the English (KJV) scheme, so a reference means the same passage in each; texts under CC BY-SA
are shared on the same terms, and Biblica texts carry the modified-work credit. Translations
numbered differently were renumbered with the Paratext versification files from
[SIL libpalaso](https://github.com/sillsdev/libpalaso) (MIT License) and checked chapter by
chapter against the English layout and known passages. The King James Version is under Crown
patent in the United Kingdom and is not offered there.

Sources: [eBible.org](https://ebible.org) USFM (pinned by checksum); the Korean Revised
Version (개역한글판, 1961) from CrossWire's SWORD module KorRV (the Wikisource text), because
eBible's copy is incomplete. The Berean Standard Bible is bundled in the app.

| id | language | name | English name | license | source |
|---|---|---|---|---|---|
| ARBNAV | ar | كتاب الحياة | New Arabic Version, Ketab El Hayat (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/arbnav_usfm.zip |
| AVD | ar | ترجمة فان دايك | Arabic Bible (Van Dyck) | Public Domain | https://ebible.org/Scriptures/arb-vd_usfm.zip |
| ASMFB | as | ইণ্ডিয়ান ৰিভাইচ ভাৰচন (IRV) আচামিচ | Assamese Indian Revised Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/asmfb_usfm.zip |
| BEO | beo | Gode Ea Sia: Ida:iwane Gala | Bedamuni Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/beo_usfm.zip |
| BENIRV | bn | ইন্ডিয়ান রিভাইজড ভার্সন (IRV) | Bengali Indian Revised Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/benirv_usfm.zip |
| BENOBCV | bn | বাংলা সমকালীন সংস্করণ | Bengali Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/benobcv_usfm.zip |
| CEBCB | ceb | Ang Pulong sa Dios | Cebuano Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/cebocb_usfm.zip |
| CEBULB | ceb | Balaan nga Bibliya | Cebuano Unlocked Literal Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/cebulb_usfm.zip |
| CEKAK | cek | Asang Khongca Bible | Eastern Khumi Chin Bible (Asang Khongca, 2019) | Public Domain | https://ebible.org/Scriptures/cekak_usfm.zip |
| CHK | chk | Paipel | Chuukese Bible (Liebenzell Mission) | CC BY-ND 4.0 | https://ebible.org/Scriptures/chk_usfm.zip |
| CKB | ckb | وەشانی کوردیی سۆرانیی ستاندەر | Kurdi Sorani Standard Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/ckb_usfm.zip |
| BKR | cs | Bible kralická | Czech Kralice Bible 1613 | Public Domain | https://ebible.org/Scriptures/ces1613_usfm.zip |
| CTH | cth | Thai Phum Holy Bible | Thaiphum Chin Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/cth_usfm.zip |
| DEU1951 | de | Schlachter 1951 | Schlachter Bible 1951 | CC BY 4.0 | https://ebible.org/Scriptures/deu1951_usfm.zip |
| DEUELO | de | Unrevidierte Elberfelder 1905 | Unrevised Elberfelder Bible 1905 | Public Domain | https://ebible.org/Scriptures/deuelo_usfm.zip |
| LUT1912 | de | Lutherbibel 1912 | Luther Bible 1912 | Public Domain | https://ebible.org/Scriptures/deu1912_usfm.zip |
| DWRL | dwr | Geeshsha Mas'aafaa | Dawro Bible (Latin script) | CC BY-SA 4.0 | https://ebible.org/Scriptures/dwrl_usfm.zip |
| EWE | ee | Agbenya La | Ewe Contemporary Scriptures (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/ewe_usfm.zip |
| ENGASV | en | American Standard Version | American Standard Version (1901) | Public Domain | https://ebible.org/Scriptures/eng-asv_usfm.zip |
| ENGASVBT | en | American Standard Version Byzantine Text | ASV with the Byzantine Text New Testament | Public Domain | https://ebible.org/Scriptures/engasvbt_usfm.zip |
| ENGBBE | en | Bible in Basic English | Bible in Basic English (1965) | Public Domain | https://ebible.org/Scriptures/engBBE_usfm.zip |
| ENGDBY | en | Darby Translation | Darby Translation (1890) | Public Domain | https://ebible.org/Scriptures/engDBY_usfm.zip |
| ENGFBV | en | Free Bible Version | Free Bible Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/engfbv_usfm.zip |
| ENGGNV | en | Geneva Bible 1599 | Geneva Bible (1599) | Public Domain | https://ebible.org/Scriptures/enggnv_usfm.zip |
| ENGKJVCPB | en | King James Version (Cambridge Paragraph Bible) | KJV Cambridge Paragraph Bible (1873) | Public Domain | https://ebible.org/Scriptures/engkjvcpb_usfm.zip |
| ENGLSV | en | Literal Standard Version | Literal Standard Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/englsv_usfm.zip |
| ENGMSB | en | Majority Standard Bible | Majority Standard Bible | Public Domain | https://ebible.org/Scriptures/engmsb_usfm.zip |
| ENGOJB | en | The Orthodox Jewish Bible | Orthodox Jewish Bible (Artists for Israel) | CC BY 4.0 | https://ebible.org/Scriptures/engojb_usfm.zip |
| ENGRV | en | Revised Version | Revised Version (1885/1895, British) | Public Domain | https://ebible.org/Scriptures/eng-rv_usfm.zip |
| ENGT4T | en | Translation for Translators | Translation for Translators (Deibler) | CC BY-SA 4.0 | https://ebible.org/Scriptures/eng-t4t_usfm.zip |
| ENGULB | en | Unlocked Literal Bible | Unlocked Literal Bible (English) | CC BY-SA 4.0 | https://ebible.org/Scriptures/engULB_usfm.zip |
| ENGWEB | en | World English Bible Classic | World English Bible Classic (with “Yahweh”) | Public Domain | https://ebible.org/Scriptures/eng-web_usfm.zip |
| ENGWEBPB | en | World English Bible British Edition | World English Bible British Edition | Public Domain | https://ebible.org/Scriptures/engwebpb_usfm.zip |
| ENGWEBSTER | en | Noah Webster Bible | Noah Webster Bible (1833) | Public Domain | https://ebible.org/Scriptures/engwebster_usfm.zip |
| ENGWMB | en | World Messianic Bible | World Messianic Bible | Public Domain | https://ebible.org/Scriptures/engwmb_usfm.zip |
| ENGWMBB | en | World Messianic Bible British Edition | World Messianic Bible British Edition | Public Domain | https://ebible.org/Scriptures/engwmbb_usfm.zip |
| ENGYLT | en | Young's Literal Translation | Young's Literal Translation (1898) | Public Domain | https://ebible.org/Scriptures/engylt_usfm.zip |
| KJV | en | King James Version | King James Version | Public Domain | https://ebible.org/Scriptures/eng-kjv2006_usfm.zip |
| WEB | en | World English Bible | World English Bible | Public Domain | https://ebible.org/Scriptures/engwebp_usfm.zip |
| EPO | eo | Londona Biblio | Esperanto London Bible (1910) | Public Domain | https://ebible.org/Scriptures/epo_usfm.zip |
| PDPT | es | Palabra de Dios para ti | Spanish Bible (God's Word for You) | CC BY 4.0 | https://ebible.org/Scriptures/spapddpt_usfm.zip |
| RV1909 | es | Reina-Valera 1909 | Reina-Valera 1909 | Public Domain | https://ebible.org/Scriptures/spaRV1909_usfm.zip |
| SPABES | es | La Biblia en Español Sencillo | Spanish Bible in Simple Spanish (Español Sencillo) | CC BY 4.0 | https://ebible.org/Scriptures/spabes_usfm.zip |
| SPAONBV | es | Nueva Biblia Viva | Spanish Nueva Biblia Viva (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/spaonbv_usfm.zip |
| SPAVBL | es | Versión Biblia Libre | Spanish Free Bible Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/spavbl_usfm.zip |
| PCB | fa | کتاب مقدس، ترجمهٔ معاصر | Persian Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/pesopcb_usfm.zip |
| FRAFOB | fr | La Sainte Bible (Ostervald) | French Ostervald Bible | Public Domain | https://ebible.org/Scriptures/fra_fob_usfm.zip |
| FRAJND | fr | Bible J.N. Darby | French Darby Bible | Public Domain | https://ebible.org/Scriptures/frajnd_usfm.zip |
| LSG | fr | Louis Segond 1910 | Louis Segond 1910 | Public Domain | https://ebible.org/Scriptures/fraLSG_usfm.zip |
| GAX | gax | Kitaaba Woyyuu | Guji Oromo Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/gax_usfm.zip |
| GMVL | gmv | Geeshsha Mexaafa | Gamo Bible (Latin script) | CC BY-SA 4.0 | https://ebible.org/Scriptures/gmvl_usfm.zip |
| GOFL | gof | Geeshsha Maxaafa | Gofa Bible (Latin script) | CC BY-SA 4.0 | https://ebible.org/Scriptures/gofl_usfm.zip |
| GUJ2017 | gu | ઇન્ડિયન રીવાઇઝ્ડ વર્ઝન ગુજરાતી | Indian Revised Version (Gujarati) | CC BY-SA 4.0 | https://ebible.org/Scriptures/guj2017_usfm.zip |
| HAUSA | ha | Littafi Mai Tsarki, Sabon Rai Don Kowa | Hausa New Life for All (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/hausa_usfm.zip |
| HAW1868 | haw | Baibala Hemolele | Hawaiian Bible (1868) | Public Domain | https://ebible.org/Scriptures/haw1868_usfm.zip |
| HEB | he | תנ״ך עברי מודרני | Hebrew Bible (with Delitzsch New Testament) | Public Domain | https://ebible.org/Scriptures/heb_usfm.zip |
| HIIRV | hi | इंडियन रिवाइज्ड वर्जन (IRV) हिंदी | Indian Revised Version (Hindi) | CC BY-SA 4.0 | https://ebible.org/Scriptures/hin2017_usfm.zip |
| HINCV | hi | हिंदी समकालीन संस्करण | Hindi Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/hincv_usfm.zip |
| HIL | hil | Ang Pulong Sang Dios | Hiligaynon Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/hil_usfm.zip |
| HLT | hlt | Baibal Olcim | Matupi Chin Bible | Public Domain | https://ebible.org/Scriptures/hlt_usfm.zip |
| HNE | hne | समकालीन छत्तीसगढ़ी अनुवाद | Chhattisgarhi Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/hne_usfm.zip |
| HAT | ht | Bib La | Haitian Creole Bible 1985 | Public Domain | https://ebible.org/Scriptures/hat_usfm.zip |
| HATBSA | ht | Bib Sen An | Haitian Creole Holy Bible (Ron Smith, 2023) | CC BY-SA 4.0 | https://ebible.org/Scriptures/hatbsa_usfm.zip |
| IGCB | ig | Baịbụlụ Nsọ nʼIgbo Ndị Ugbu a | Igbo Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/ibo_usfm.zip |
| ILOULB | ilo | Ti Biblia | Ilocano Unlocked Literal Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/iloulb_usfm.zip |
| ITA1885 | it | Diodati 1885 | Italian Diodati Bible (1885 revision) | Public Domain | https://ebible.org/Scriptures/ita1885_usfm.zip |
| RIV1927 | it | Riveduta 1927 | Italian Riveduta 1927 | Public Domain | https://ebible.org/Scriptures/ita1927_usfm.zip |
| JFB | ja | フリーダム・バイブル | Japanese Freedom Bible | Public Domain | https://ebible.org/Scriptures/jpnm_usfm.zip |
| KBQ | kbq | Anumzamofo Ruotage Avontafere | Kamano-Kafe Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/kbq_usfm.zip |
| KIK | ki | Kiugo Gĩtheru Kĩa Ngai Kĩhingũre | Kikuyu Holy Word of God (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/kik_usfm.zip |
| KANIRV | kn | ಇಂಡಿಯನ್ ರಿವೈಜ್ಡ್ ವರ್ಸನ್ (IRV) - ಕನ್ನಡ | Indian Revised Version (Kannada) | CC BY-SA 4.0 | https://ebible.org/Scriptures/kanirv_usfm.zip |
| KANOKCV | kn | ಕನ್ನಡ ಸಮಕಾಲಿಕ ಭಾಷಾಂತರ | Kannada Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/kanokcv_usfm.zip |
| KRV | ko | 성경전서 개역한글판 | Korean Revised Version (Korean Bible Society, 1961) | Public Domain | https://www.crosswire.org/ftpmirror/pub/sword/packages/rawzip/KorRV.zip |
| KOS | kos | Bible Mutal | Kosraean Bible | Public Domain | https://ebible.org/Scriptures/kos_usfm.zip |
| KPG | kpg | Beebaa Dabu | Kapingamarangi Bible | CC BY-ND 4.0 | https://ebible.org/Scriptures/kpg_usfm.zip |
| LUG | lg | Bayibuli Entukuvu | Luganda Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/lug_usfm.zip |
| LIN | ln | Mokanda na Bomoi | Lingala Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/lin_usfm.zip |
| LUO | luo | Ochiw Thuolo Motingʼo Loko Manyien | Dholuo New Luo Translation (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/luo_usfm.zip |
| MDYETH | mdy | ጌኤዦ ማፃኣፖ | Maale Bible (Ethiopic script) | CC BY-SA 4.0 | https://ebible.org/Scriptures/mdyeth_usfm.zip |
| MKW | mkw | Mambu ya Nzambi | Kituba Bible (Congo-Brazzaville) | CC BY-SA 4.0 | https://ebible.org/Scriptures/mkw_usfm.zip |
| MAL2015 | ml | സത്യവേദപുസ്തകം 1910 (സമകാലിക ലിപിയിൽ) | Malayalam Bible 1910 (contemporary orthography) | CC BY-SA 4.0 | https://ebible.org/Scriptures/mal2015_usfm.zip |
| MALC | ml | സമകാലിക മലയാളവിവർത്തനം | Malayalam Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/malc_usfm.zip |
| MLIRV | ml | ഇന്ത്യൻ റിവൈസ്ഡ് വേർഷൻ (IRV) - മലയാളം | Indian Revised Version (Malayalam) | CC BY-SA 4.0 | https://ebible.org/Scriptures/mal_usfm.zip |
| MPS | mps | Godigo dwagi yai po buku | Dadibi Bible | CC BY-ND 4.0 | https://ebible.org/Scriptures/mps_usfm.zip |
| MAR | mr | इंडियन रीवाइज्ड वर्जन (IRV) | Marathi Indian Revised Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/mar_usfm.zip |
| MARC | mr | मराठी समकालीन संस्करण | Marathi Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/marc_usfm.zip |
| MSY2020 | msy | Godɨn Eghaghanim | Aruamu Bible (2020) | CC BY-SA 4.0 | https://ebible.org/Scriptures/msy2020_usfm.zip |
| NDE | nd | IBhayibhili Elingcwele LesiNdebele Elifinyelelekayo | Ndebele Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/nde_usfm.zip |
| NPIONCB | ne | नेपाली समकालीन सर्वसुलभ संस्करण | Nepali Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/npioncb_usfm.zip |
| NPIULB | ne | पवित्र बाइबल | Nepali Unlocked Literal Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/npiulb_usfm.zip |
| SV1917 | nl | De Heilige Schrift 1917 | Dutch Bible 1917 | Public Domain | https://ebible.org/Scriptures/nld_usfm.zip |
| NYA | ny | Mawu a Mulungu mu Chichewa Chalero | Chichewa Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/nya_usfm.zip |
| GAZ | om | Kitaaba Qulqulluu, Hiikkaa Ammayyaa Haaraa | New Oromo Contemporary Version, Western (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/gaz_usfm.zip |
| GAZE | om-Ethi | ክታበ ቁልቁሉ, ሂካ አመያ ሃራ | New Oromo Contemporary Version, Western, Ethiopic script (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/gaze_usfm.zip |
| ORY | or | ଇଣ୍ଡିୟାନ ରିୱାଇସ୍ଡ୍ ୱରସନ୍ ଓଡିଆ | Odia Indian Revised Version | CC BY-SA 4.0 | https://ebible.org/Scriptures/ory_usfm.zip |
| PAN | pa | ਇੰਡਿਅਨ ਰਿਵਾਇਜ਼ਡ ਵਰਜ਼ਨ (IRV) - ਪੰਜਾਬੀ | Indian Revised Version (Punjabi) | CC BY-SA 4.0 | https://ebible.org/Scriptures/pan_usfm.zip |
| UBG | pl | Uwspółcześniona Biblia Gdańska | Updated Gdańsk Bible | CC BY-ND 4.0 | https://ebible.org/Scriptures/polubg_usfm.zip |
| BLIVRE | pt | Bíblia Livre | Portuguese Free Bible (Almeida revision) | CC BY 4.0 | https://ebible.org/Scriptures/porbr2018_usfm.zip |
| BPM | pt | Bíblia Portuguesa Mundial | World Portuguese Bible | Public Domain | https://ebible.org/Scriptures/porbrbsl_usfm.zip |
| PORONBV | pt | Nova Bíblia Viva | Portuguese New Living Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/poronbv_usfm.zip |
| RMC | rmc | Le Devleskero Lav Andre Romaňi Čhib | Eastern Slovak Romani Bible (2022) | CC BY-ND 4.0 | https://ebible.org/Scriptures/rmc_usfm.zip |
| SYN | ru | Синодальный перевод | Russian Synodal Bible | Public Domain | https://ebible.org/Scriptures/russyn_usfm.zip |
| RUG | rug | Buka Hope | Roviana Bible | CC BY-ND 4.0 | https://ebible.org/Scriptures/rug_usfm.zip |
| SNA | sn | Bhaibheri Dzvene MuChiShona Chanhasi | Shona Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/sna_usfm.zip |
| SRPONSPC | sr | Нови српски превод | New Serbian Translation, Cyrillic (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/srponspc_usfm.zip |
| SRPONSTL | sr | Novi srpski prevod | New Serbian Translation, Latin (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/srponstl_usfm.zip |
| SWCB | sw | Neno: Bibilia Takatifu | Kiswahili Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/swhonen_usfm.zip |
| SWHONMM | sw | Neno: Maandiko Matakatifu | Kiswahili Contemporary Scriptures (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/swhonmm_usfm.zip |
| SWHULB | sw | Biblia Takatifu | Swahili Unlocked Literal Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/swhulb_usfm.zip |
| TAIRV | ta | இண்டியன் ரிவைஸ்டு வெர்ஸன் (IRV) - தமிழ் | Indian Revised Version (Tamil) | CC BY-SA 4.0 | https://ebible.org/Scriptures/tam2017_usfm.zip |
| TAMTCV | ta | தமிழ் சமகால பதிப்பு | Indian Tamil Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/tamtcv_usfm.zip |
| TEL2017 | te | ఇండియన్ రివైజ్డ్ వెర్షన్ (IRV) | Telugu Indian Revised Version (2019) | CC BY-SA 4.0 | https://ebible.org/Scriptures/tel2017_usfm.zip |
| TELOTSA | te | తెలుగు సమకాలీన అనువాదం | Telugu Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/telotsa_usfm.zip |
| TLULB | tl | Banal na Bibliya | Tagalog Unlocked Literal Bible | CC BY-SA 4.0 | https://ebible.org/Scriptures/tglulb_usfm.zip |
| TON | to | Ko e Tohi Tapu Kātoa | Tongan Bible (Revised West Version) | Public Domain | https://ebible.org/Scriptures/ton_usfm.zip |
| TURYTC | tr | Yorumsuz Türkçe Çeviri | Turkish Literal Translation (YTC) | CC BY-ND 4.0 | https://ebible.org/Scriptures/turytc_usfm.zip |
| TWI | tw | Akuapem Twi Nkwa Asɛm | Akuapem Twi Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/twi_usfm.zip |
| TWIASANTE | tw | Asante Twi Nkwa Asɛm | Asante Twi Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/twiasante_usfm.zip |
| UKR1871 | uk | Біблія в перекладі Куліша | Ukrainian Bible (Kulish) | Public Domain | https://ebible.org/Scriptures/ukr1871_usfm.zip |
| UKRFB | uk | Біблія свободи | Ukrainian Freedom Bible (Kulish–Puluj, updated) | Public Domain | https://ebible.org/Scriptures/ukrfb_usfm.zip |
| URDOUCV | ur | اردو ہم عصر ترجمہ | Urdu Contemporary Version (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/urdoucv_usfm.zip |
| URD | ur-Deva | इंडियन रिवाइज्ड वर्जन उर्दू | Indian Revised Version Urdu (Devanagari script) | CC BY-SA 4.0 | https://ebible.org/Scriptures/urd_usfm.zip |
| VI1923 | vi | Kinh Thánh 1923 | Vietnamese Bible 1923 | Public Domain | https://ebible.org/Scriptures/vie1934_usfm.zip |
| VIEOVCB | vi | Kinh Thánh Hiện Đại | Vietnamese Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/vieovcb_usfm.zip |
| YOCB | yo | Bíbélì Mímọ́ ní Èdè Yorùbá Òde-Òní | Yoruba Contemporary Bible (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/yor_usfm.zip |
| CMNCBS | zh-Hans | 圣经当代译本（简体） | Chinese Contemporary Bible, Simplified (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/cmncbs_usfm.zip |
| CUVS | zh-Hans | 和合本（简体） | Chinese Union Version (Simplified) | Public Domain | https://ebible.org/Scriptures/cmn-cu89s_usfm.zip |
| CMNCBT | zh-Hant | 聖經當代譯本（繁體） | Chinese Contemporary Bible, Traditional (based on Biblica’s open text) | CC BY-SA 4.0 | https://ebible.org/Scriptures/cmncbt_usfm.zip |
| CUVT | zh-Hant | 和合本（繁體） | Chinese Union Version (Traditional) | Public Domain | https://ebible.org/Scriptures/cmn-cu89t_usfm.zip |
