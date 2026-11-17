# World Bank vs IMF — 40 economies, 2010–2024: real GDP growth and inflation

Reconciliation of the World Bank Indicators API against the IMF DataMapper API for 40 economies over 2010–2024, two measures (gdp growth, inflation), three daily pulls. All lists below are computed from the CSV of the last pull that did not fail — **wb-imf-pull3.csv** (1200 rows, SHA-256 `dc6cf6f31ec54366346d658805d6b5ec8c260b7e57c8e840c43f94cf9540df43`).

## Summary (pull 3)

- Rows: 1200 (40 countries x 2 measures x 15 years)
- match: 1087
- mismatch: 113
- missing in World Bank: 0
- missing in IMF: 0
- missing in both: 0

## (a) Mismatch counts per country per measure (pull 3)

| country | gdp growth | inflation | total |
|---|---|---|---|
| ARE | 2 | 0 | 2 |
| BGD | 0 | 7 | 7 |
| BGR | 0 | 8 | 8 |
| BOL | 0 | 0 | 0 |
| CIV | 5 | 1 | 6 |
| CMR | 0 | 0 | 0 |
| CRI | 0 | 0 | 0 |
| CZE | 0 | 0 | 0 |
| DNK | 0 | 1 | 1 |
| DOM | 0 | 1 | 1 |
| DZA | 0 | 0 | 0 |
| ECU | 0 | 0 | 0 |
| ETH | 9 | 13 | 22 |
| FIN | 1 | 3 | 4 |
| GHA | 1 | 6 | 7 |
| GRC | 0 | 4 | 4 |
| GTM | 0 | 0 | 0 |
| HRV | 0 | 1 | 1 |
| HUN | 0 | 0 | 0 |
| JOR | 0 | 0 | 0 |
| KAZ | 0 | 0 | 0 |
| KEN | 0 | 0 | 0 |
| LKA | 0 | 9 | 9 |
| MAR | 1 | 0 | 1 |
| NZL | 5 | 0 | 5 |
| OMN | 0 | 0 | 0 |
| PAN | 0 | 0 | 0 |
| PRT | 0 | 1 | 1 |
| PRY | 0 | 0 | 0 |
| QAT | 5 | 3 | 8 |
| ROU | 0 | 0 | 0 |
| SRB | 0 | 0 | 0 |
| SVK | 0 | 1 | 1 |
| SVN | 0 | 0 | 0 |
| TUN | 0 | 1 | 1 |
| TZA | 4 | 1 | 5 |
| UGA | 12 | 6 | 18 |
| UKR | 0 | 0 | 0 |
| URY | 0 | 0 | 0 |
| ZMB | 0 | 1 | 1 |

## (b) 15 mismatch rows with the largest absolute difference (pull 3)

Ties broken by key ascending. Difference = World Bank value rounded to 1 decimal minus the IMF value.

| # | key | world bank value | imf value | world bank rounded | difference |
|---|---|---|---|---|---|
| 1 | ETH\|inflation\|2011 | 33.2499598823344 | 18.1 | 33.2 | 15.1 |
| 2 | ETH\|inflation\|2012 | 23.600417677317 | 34.1 | 23.6 | -10.5 |
| 3 | ETH\|inflation\|2021 | 26.8395221557722 | 20.2 | 26.8 | 6.6 |
| 4 | ARE\|gdp growth\|2010 | 1.60285004336325 | 7.9 | 1.6 | -6.3 |
| 5 | ETH\|inflation\|2013 | 7.46402192944517 | 13.5 | 7.5 | -6.0 |
| 6 | ETH\|inflation\|2024 | 21.037746057771 | 26.6 | 21.0 | -5.6 |
| 7 | ETH\|inflation\|2010 | 8.14926402965082 | 2.8 | 8.1 | 5.3 |
| 8 | CIV\|gdp growth\|2010 | 6.84804939907013 | 2 | 6.8 | 4.8 |
| 9 | UGA\|gdp growth\|2016 | 4.78100029254482 | 0.2 | 4.8 | 4.6 |
| 10 | LKA\|inflation\|2022 | 49.7211021114327 | 45.2 | 49.7 | 4.5 |
| 11 | UGA\|gdp growth\|2020 | 2.95130642218098 | -1.2 | 3.0 | 4.2 |
| 12 | GHA\|inflation\|2012 | 11.1863409441067 | 7.1 | 11.2 | 4.1 |
| 13 | GHA\|inflation\|2010 | 10.7333898354914 | 6.7 | 10.7 | 4.0 |
| 14 | ETH\|inflation\|2017 | 10.6871150284238 | 6.9 | 10.7 | 3.8 |
| 15 | UGA\|gdp growth\|2017 | 3.13140551723596 | 6.8 | 3.1 | -3.7 |

## (c) Countries ranked by total mismatch rows (pull 3)

Most mismatch rows first; ties broken by country code ascending.

| rank | country | gdp growth | inflation | total |
|---|---|---|---|---|
| 1 | ETH | 9 | 13 | 22 |
| 2 | UGA | 12 | 6 | 18 |
| 3 | LKA | 0 | 9 | 9 |
| 4 | BGR | 0 | 8 | 8 |
| 5 | QAT | 5 | 3 | 8 |
| 6 | BGD | 0 | 7 | 7 |
| 7 | GHA | 1 | 6 | 7 |
| 8 | CIV | 5 | 1 | 6 |
| 9 | NZL | 5 | 0 | 5 |
| 10 | TZA | 4 | 1 | 5 |
| 11 | FIN | 1 | 3 | 4 |
| 12 | GRC | 0 | 4 | 4 |
| 13 | ARE | 2 | 0 | 2 |
| 14 | DNK | 0 | 1 | 1 |
| 15 | DOM | 0 | 1 | 1 |
| 16 | HRV | 0 | 1 | 1 |
| 17 | MAR | 1 | 0 | 1 |
| 18 | PRT | 0 | 1 | 1 |
| 19 | SVK | 0 | 1 | 1 |
| 20 | TUN | 0 | 1 | 1 |
| 21 | ZMB | 0 | 1 | 1 |
| 22 | BOL | 0 | 0 | 0 |
| 23 | CMR | 0 | 0 | 0 |
| 24 | CRI | 0 | 0 | 0 |
| 25 | CZE | 0 | 0 | 0 |
| 26 | DZA | 0 | 0 | 0 |
| 27 | ECU | 0 | 0 | 0 |
| 28 | GTM | 0 | 0 | 0 |
| 29 | HUN | 0 | 0 | 0 |
| 30 | JOR | 0 | 0 | 0 |
| 31 | KAZ | 0 | 0 | 0 |
| 32 | KEN | 0 | 0 | 0 |
| 33 | OMN | 0 | 0 | 0 |
| 34 | PAN | 0 | 0 | 0 |
| 35 | PRY | 0 | 0 | 0 |
| 36 | ROU | 0 | 0 | 0 |
| 37 | SRB | 0 | 0 | 0 |
| 38 | SVN | 0 | 0 | 0 |
| 39 | UKR | 0 | 0 | 0 |
| 40 | URY | 0 | 0 | 0 |

## (d) Missing rows (pull 3)

None. Every country, measure and year has a value in both sources in pull 3 (0 missing in World Bank, 0 missing in IMF, 0 missing in both).

## PROOF

### Requests — pull 1

- source: World Bank Indicators API; host: api.worldbank.org; url: https://api.worldbank.org/v2/country/ARE;BGD;BGR;BOL;CIV;CMR;CRI;CZE;DNK;DOM;DZA;ECU;ETH;FIN;GHA;GRC;GTM;HRV;HUN;JOR;KAZ;KEN;LKA;MAR;NZL;OMN;PAN;PRT;PRY;QAT;ROU;SRB;SVK;SVN;TUN;TZA;UGA;UKR;URY;ZMB/indicator/NY.GDP.MKTP.KD.ZG?format=json&date=2010:2024&per_page=1000; requested at (UTC): 2026-11-15T22:32:46+00:00; HTTP status: 200; response Date header: Date: Sun, 15 Nov 2026 22:32:52 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/NGDP_RPCH/ARE/BGD/BGR/BOL/CIV/CMR/CRI/CZE/DNK/DOM/DZA/ECU/ETH/FIN/GHA/GRC/GTM/HRV/HUN/JOR; requested at (UTC): 2026-11-15T22:32:52+00:00; HTTP status: 200; response Date header: Date: Sun, 15 Nov 2026 22:33:00 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/NGDP_RPCH/KAZ/KEN/LKA/MAR/NZL/OMN/PAN/PRT/PRY/QAT/ROU/SRB/SVK/SVN/TUN/TZA/UGA/UKR/URY/ZMB; requested at (UTC): 2026-11-15T22:33:00+00:00; HTTP status: 200; response Date header: Date: Sun, 15 Nov 2026 22:33:06 GMT; ok: True
- source: World Bank Indicators API; host: api.worldbank.org; url: https://api.worldbank.org/v2/country/ARE;BGD;BGR;BOL;CIV;CMR;CRI;CZE;DNK;DOM;DZA;ECU;ETH;FIN;GHA;GRC;GTM;HRV;HUN;JOR;KAZ;KEN;LKA;MAR;NZL;OMN;PAN;PRT;PRY;QAT;ROU;SRB;SVK;SVN;TUN;TZA;UGA;UKR;URY;ZMB/indicator/FP.CPI.TOTL.ZG?format=json&date=2010:2024&per_page=1000; requested at (UTC): 2026-11-15T22:33:05+00:00; HTTP status: 200; response Date header: Date: Sun, 15 Nov 2026 22:33:10 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/PCPIPCH/ARE/BGD/BGR/BOL/CIV/CMR/CRI/CZE/DNK/DOM/DZA/ECU/ETH/FIN/GHA/GRC/GTM/HRV/HUN/JOR; requested at (UTC): 2026-11-15T22:33:10+00:00; HTTP status: 200; response Date header: Date: Sun, 15 Nov 2026 22:33:15 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/PCPIPCH/KAZ/KEN/LKA/MAR/NZL/OMN/PAN/PRT/PRY/QAT/ROU/SRB/SVK/SVN/TUN/TZA/UGA/UKR/URY/ZMB; requested at (UTC): 2026-11-15T22:33:15+00:00; HTTP status: 200; response Date header: Date: Sun, 15 Nov 2026 22:33:21 GMT; ok: True

### Requests — pull 2

- source: World Bank Indicators API; host: api.worldbank.org; url: https://api.worldbank.org/v2/country/ARE;BGD;BGR;BOL;CIV;CMR;CRI;CZE;DNK;DOM;DZA;ECU;ETH;FIN;GHA;GRC;GTM;HRV;HUN;JOR;KAZ;KEN;LKA;MAR;NZL;OMN;PAN;PRT;PRY;QAT;ROU;SRB;SVK;SVN;TUN;TZA;UGA;UKR;URY;ZMB/indicator/NY.GDP.MKTP.KD.ZG?format=json&date=2010:2024&per_page=1000; requested at (UTC): 2026-11-16T23:03:31+00:00; HTTP status: 200; response Date header: Date: Mon, 16 Nov 2026 23:03:45 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/NGDP_RPCH/ARE/BGD/BGR/BOL/CIV/CMR/CRI/CZE/DNK/DOM/DZA/ECU/ETH/FIN/GHA/GRC/GTM/HRV/HUN/JOR; requested at (UTC): 2026-11-16T23:03:44+00:00; HTTP status: 200; response Date header: Date: Mon, 16 Nov 2026 23:03:52 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/NGDP_RPCH/KAZ/KEN/LKA/MAR/NZL/OMN/PAN/PRT/PRY/QAT/ROU/SRB/SVK/SVN/TUN/TZA/UGA/UKR/URY/ZMB; requested at (UTC): 2026-11-16T23:03:52+00:00; HTTP status: 200; response Date header: Date: Mon, 16 Nov 2026 23:03:57 GMT; ok: True
- source: World Bank Indicators API; host: api.worldbank.org; url: https://api.worldbank.org/v2/country/ARE;BGD;BGR;BOL;CIV;CMR;CRI;CZE;DNK;DOM;DZA;ECU;ETH;FIN;GHA;GRC;GTM;HRV;HUN;JOR;KAZ;KEN;LKA;MAR;NZL;OMN;PAN;PRT;PRY;QAT;ROU;SRB;SVK;SVN;TUN;TZA;UGA;UKR;URY;ZMB/indicator/FP.CPI.TOTL.ZG?format=json&date=2010:2024&per_page=1000; requested at (UTC): 2026-11-16T23:03:57+00:00; HTTP status: 200; response Date header: Date: Mon, 16 Nov 2026 23:04:23 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/PCPIPCH/ARE/BGD/BGR/BOL/CIV/CMR/CRI/CZE/DNK/DOM/DZA/ECU/ETH/FIN/GHA/GRC/GTM/HRV/HUN/JOR; requested at (UTC): 2026-11-16T23:04:22+00:00; HTTP status: 200; response Date header: Date: Mon, 16 Nov 2026 23:04:27 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/PCPIPCH/KAZ/KEN/LKA/MAR/NZL/OMN/PAN/PRT/PRY/QAT/ROU/SRB/SVK/SVN/TUN/TZA/UGA/UKR/URY/ZMB; requested at (UTC): 2026-11-16T23:04:27+00:00; HTTP status: 200; response Date header: Date: Mon, 16 Nov 2026 23:04:42 GMT; ok: True

### Requests — pull 3

- source: World Bank Indicators API; host: api.worldbank.org; url: https://api.worldbank.org/v2/country/ARE;BGD;BGR;BOL;CIV;CMR;CRI;CZE;DNK;DOM;DZA;ECU;ETH;FIN;GHA;GRC;GTM;HRV;HUN;JOR;KAZ;KEN;LKA;MAR;NZL;OMN;PAN;PRT;PRY;QAT;ROU;SRB;SVK;SVN;TUN;TZA;UGA;UKR;URY;ZMB/indicator/NY.GDP.MKTP.KD.ZG?format=json&date=2010:2024&per_page=1000; requested at (UTC): 2026-11-17T23:21:51+00:00; HTTP status: 200; response Date header: Date: Tue, 17 Nov 2026 23:23:33 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/NGDP_RPCH/ARE/BGD/BGR/BOL/CIV/CMR/CRI/CZE/DNK/DOM/DZA/ECU/ETH/FIN/GHA/GRC/GTM/HRV/HUN/JOR; requested at (UTC): 2026-11-17T23:23:32+00:00; HTTP status: 200; response Date header: Date: Tue, 17 Nov 2026 23:23:38 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/NGDP_RPCH/KAZ/KEN/LKA/MAR/NZL/OMN/PAN/PRT/PRY/QAT/ROU/SRB/SVK/SVN/TUN/TZA/UGA/UKR/URY/ZMB; requested at (UTC): 2026-11-17T23:23:38+00:00; HTTP status: 200; response Date header: Date: Tue, 17 Nov 2026 23:23:42 GMT; ok: True
- source: World Bank Indicators API; host: api.worldbank.org; url: https://api.worldbank.org/v2/country/ARE;BGD;BGR;BOL;CIV;CMR;CRI;CZE;DNK;DOM;DZA;ECU;ETH;FIN;GHA;GRC;GTM;HRV;HUN;JOR;KAZ;KEN;LKA;MAR;NZL;OMN;PAN;PRT;PRY;QAT;ROU;SRB;SVK;SVN;TUN;TZA;UGA;UKR;URY;ZMB/indicator/FP.CPI.TOTL.ZG?format=json&date=2010:2024&per_page=1000; requested at (UTC): 2026-11-17T23:23:41+00:00; HTTP status: 200; response Date header: Date: Tue, 17 Nov 2026 23:25:27 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/PCPIPCH/ARE/BGD/BGR/BOL/CIV/CMR/CRI/CZE/DNK/DOM/DZA/ECU/ETH/FIN/GHA/GRC/GTM/HRV/HUN/JOR; requested at (UTC): 2026-11-17T23:25:27+00:00; HTTP status: 200; response Date header: Date: Tue, 17 Nov 2026 23:25:33 GMT; ok: True
- source: IMF DataMapper API; host: www.imf.org; url: https://www.imf.org/external/datamapper/api/v1/PCPIPCH/KAZ/KEN/LKA/MAR/NZL/OMN/PAN/PRT/PRY/QAT/ROU/SRB/SVK/SVN/TUN/TZA/UGA/UKR/URY/ZMB; requested at (UTC): 2026-11-17T23:25:32+00:00; HTTP status: 200; response Date header: Date: Tue, 17 Nov 2026 23:25:37 GMT; ok: True

### World Bank paging elements (verbatim, one per World Bank response)

- pull 1, NY.GDP.MKTP.KD.ZG: `{"page":1,"pages":1,"per_page":1000,"total":600,"sourceid":"2","lastupdated":"2026-11-11"}`
- pull 1, FP.CPI.TOTL.ZG: `{"page":1,"pages":1,"per_page":1000,"total":600,"sourceid":"2","lastupdated":"2026-11-11"}`
- pull 2, NY.GDP.MKTP.KD.ZG: `{"page":1,"pages":1,"per_page":1000,"total":600,"sourceid":"2","lastupdated":"2026-11-11"}`
- pull 2, FP.CPI.TOTL.ZG: `{"page":1,"pages":1,"per_page":1000,"total":600,"sourceid":"2","lastupdated":"2026-11-11"}`
- pull 3, NY.GDP.MKTP.KD.ZG: `{"page":1,"pages":1,"per_page":1000,"total":600,"sourceid":"2","lastupdated":"2026-11-11"}`
- pull 3, FP.CPI.TOTL.ZG: `{"page":1,"pages":1,"per_page":1000,"total":600,"sourceid":"2","lastupdated":"2026-11-11"}`

### Mismatch and missing rows — source records (pull 3)

One line per row: the World Bank record as returned, then the IMF year and value as printed (or "IMF year absent" when the IMF has no value for that year).

- ARE|gdp growth|2010 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"AE","value":"United Arab Emirates"},"countryiso3code":"ARE","date":"2010","value":1.60285004336325,"unit":"","obs_status":"","decimal":1} | IMF 2010: 7.9
- ARE|gdp growth|2024 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"AE","value":"United Arab Emirates"},"countryiso3code":"ARE","date":"2024","value":3.99181200361831,"unit":"","obs_status":"","decimal":1} | IMF 2024: 6.6
- BGD|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2010","value":8.12667639169917,"unit":"","obs_status":"","decimal":1} | IMF 2010: 7.3
- BGD|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2011","value":11.3951651552399,"unit":"","obs_status":"","decimal":1} | IMF 2011: 8.8
- BGD|inflation|2012 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2012","value":6.21750422069283,"unit":"","obs_status":"","decimal":1} | IMF 2012: 8.9
- BGD|inflation|2013 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2013","value":7.53040640913172,"unit":"","obs_status":"","decimal":1} | IMF 2013: 6.8
- BGD|inflation|2022 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2022","value":7.69695437176898,"unit":"","obs_status":"","decimal":1} | IMF 2022: 6.1
- BGD|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2023","value":9.8835030377921,"unit":"","obs_status":"","decimal":1} | IMF 2023: 9
- BGD|inflation|2024 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BD","value":"Bangladesh"},"countryiso3code":"BGD","date":"2024","value":10.4657482763412,"unit":"","obs_status":"","decimal":1} | IMF 2024: 9.7
- BGR|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2010","value":2.43899060504117,"unit":"","obs_status":"","decimal":1} | IMF 2010: 3
- BGR|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2011","value":4.21990346601872,"unit":"","obs_status":"","decimal":1} | IMF 2011: 3.4
- BGR|inflation|2012 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2012","value":2.95456829831012,"unit":"","obs_status":"","decimal":1} | IMF 2012: 2.4
- BGR|inflation|2015 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2015","value":-0.104633261008479,"unit":"","obs_status":"","decimal":1} | IMF 2015: -1.1
- BGR|inflation|2017 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2017","value":2.06159619443141,"unit":"","obs_status":"","decimal":1} | IMF 2017: 1.2
- BGR|inflation|2019 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2019","value":3.10372944796771,"unit":"","obs_status":"","decimal":1} | IMF 2019: 2.5
- BGR|inflation|2022 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2022","value":15.3252589264367,"unit":"","obs_status":"","decimal":1} | IMF 2022: 13
- BGR|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"BG","value":"Bulgaria"},"countryiso3code":"BGR","date":"2023","value":9.44284140088564,"unit":"","obs_status":"","decimal":1} | IMF 2023: 8.6
- CIV|gdp growth|2010 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"CI","value":"Cote d'Ivoire"},"countryiso3code":"CIV","date":"2010","value":6.84804939907013,"unit":"","obs_status":"","decimal":1} | IMF 2010: 2
- CIV|gdp growth|2012 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"CI","value":"Cote d'Ivoire"},"countryiso3code":"CIV","date":"2012","value":7.62041176451649,"unit":"","obs_status":"","decimal":1} | IMF 2012: 10.9
- CIV|gdp growth|2013 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"CI","value":"Cote d'Ivoire"},"countryiso3code":"CIV","date":"2013","value":10.7602131311256,"unit":"","obs_status":"","decimal":1} | IMF 2013: 9.3
- CIV|gdp growth|2014 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"CI","value":"Cote d'Ivoire"},"countryiso3code":"CIV","date":"2014","value":9.37199994240375,"unit":"","obs_status":"","decimal":1} | IMF 2014: 8.8
- CIV|gdp growth|2015 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"CI","value":"Cote d'Ivoire"},"countryiso3code":"CIV","date":"2015","value":7.19494942728191,"unit":"","obs_status":"","decimal":1} | IMF 2015: 8.8
- CIV|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"CI","value":"Cote d'Ivoire"},"countryiso3code":"CIV","date":"2010","value":1.22645612135479,"unit":"","obs_status":"","decimal":1} | IMF 2010: 1.8
- DNK|inflation|2022 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"DK","value":"Denmark"},"countryiso3code":"DNK","date":"2022","value":7.70063309931329,"unit":"","obs_status":"","decimal":1} | IMF 2022: 8.6
- DOM|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"DO","value":"Dominican Republic"},"countryiso3code":"DOM","date":"2011","value":5.79676809206533,"unit":"","obs_status":"","decimal":1} | IMF 2011: 8.5
- ETH|gdp growth|2010 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2010","value":12.5505383347633,"unit":"","obs_status":"","decimal":1} | IMF 2010: 10.6
- ETH|gdp growth|2013 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2013","value":10.5822700502552,"unit":"","obs_status":"","decimal":1} | IMF 2013: 9.9
- ETH|gdp growth|2016 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2016","value":9.43348265981905,"unit":"","obs_status":"","decimal":1} | IMF 2016: 8
- ETH|gdp growth|2017 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2017","value":9.56418965754014,"unit":"","obs_status":"","decimal":1} | IMF 2017: 10.2
- ETH|gdp growth|2018 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2018","value":6.81614778557282,"unit":"","obs_status":"","decimal":1} | IMF 2018: 7.7
- ETH|gdp growth|2019 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2019","value":8.36408573111346,"unit":"","obs_status":"","decimal":1} | IMF 2019: 9
- ETH|gdp growth|2021 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2021","value":5.64153069324176,"unit":"","obs_status":"","decimal":1} | IMF 2021: 6.3
- ETH|gdp growth|2022 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2022","value":5.32175988485454,"unit":"","obs_status":"","decimal":1} | IMF 2022: 6.4
- ETH|gdp growth|2023 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2023","value":6.59424599054353,"unit":"","obs_status":"","decimal":1} | IMF 2023: 7.2
- ETH|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2010","value":8.14926402965082,"unit":"","obs_status":"","decimal":1} | IMF 2010: 2.8
- ETH|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2011","value":33.2499598823344,"unit":"","obs_status":"","decimal":1} | IMF 2011: 18.1
- ETH|inflation|2012 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2012","value":23.600417677317,"unit":"","obs_status":"","decimal":1} | IMF 2012: 34.1
- ETH|inflation|2013 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2013","value":7.46402192944517,"unit":"","obs_status":"","decimal":1} | IMF 2013: 13.5
- ETH|inflation|2014 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2014","value":6.89001951597191,"unit":"","obs_status":"","decimal":1} | IMF 2014: 8.1
- ETH|inflation|2015 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2015","value":9.56889955968623,"unit":"","obs_status":"","decimal":1} | IMF 2015: 7.7
- ETH|inflation|2016 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2016","value":6.62813337230924,"unit":"","obs_status":"","decimal":1} | IMF 2016: 9.7
- ETH|inflation|2017 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2017","value":10.6871150284238,"unit":"","obs_status":"","decimal":1} | IMF 2017: 6.9
- ETH|inflation|2018 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2018","value":13.8330356586661,"unit":"","obs_status":"","decimal":1} | IMF 2018: 14.5
- ETH|inflation|2019 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2019","value":15.8096321719344,"unit":"","obs_status":"","decimal":1} | IMF 2019: 12.6
- ETH|inflation|2021 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2021","value":26.8395221557722,"unit":"","obs_status":"","decimal":1} | IMF 2021: 20.2
- ETH|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2023","value":30.2188278135278,"unit":"","obs_status":"","decimal":1} | IMF 2023: 32.5
- ETH|inflation|2024 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ET","value":"Ethiopia"},"countryiso3code":"ETH","date":"2024","value":21.037746057771,"unit":"","obs_status":"","decimal":1} | IMF 2024: 26.6
- FIN|gdp growth|2024 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"FI","value":"Finland"},"countryiso3code":"FIN","date":"2024","value":0.374566568538427,"unit":"","obs_status":"","decimal":1} | IMF 2024: 1
- FIN|inflation|2013 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"FI","value":"Finland"},"countryiso3code":"FIN","date":"2013","value":1.47828883999966,"unit":"","obs_status":"","decimal":1} | IMF 2013: 2.2
- FIN|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"FI","value":"Finland"},"countryiso3code":"FIN","date":"2023","value":6.25107162517039,"unit":"","obs_status":"","decimal":1} | IMF 2023: 4.3
- FIN|inflation|2024 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"FI","value":"Finland"},"countryiso3code":"FIN","date":"2024","value":1.57635467980291,"unit":"","obs_status":"","decimal":1} | IMF 2024: 1
- GHA|gdp growth|2012 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2012","value":9.2927894063005,"unit":"","obs_status":"","decimal":1} | IMF 2012: 8.4
- GHA|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2010","value":10.7333898354914,"unit":"","obs_status":"","decimal":1} | IMF 2010: 6.7
- GHA|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2011","value":8.7284593709302,"unit":"","obs_status":"","decimal":1} | IMF 2011: 7.7
- GHA|inflation|2012 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2012","value":11.1863409441067,"unit":"","obs_status":"","decimal":1} | IMF 2012: 7.1
- GHA|inflation|2018 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2018","value":7.80876516610703,"unit":"","obs_status":"","decimal":1} | IMF 2018: 9.8
- GHA|inflation|2022 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2022","value":31.2558951049016,"unit":"","obs_status":"","decimal":1} | IMF 2022: 31.9
- GHA|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GH","value":"Ghana"},"countryiso3code":"GHA","date":"2023","value":38.1069656296501,"unit":"","obs_status":"","decimal":1} | IMF 2023: 39.2
- GRC|inflation|2015 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GR","value":"Greece"},"countryiso3code":"GRC","date":"2015","value":-1.72561164771509,"unit":"","obs_status":"","decimal":1} | IMF 2015: -1.1
- GRC|inflation|2016 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GR","value":"Greece"},"countryiso3code":"GRC","date":"2016","value":-0.837681877998503,"unit":"","obs_status":"","decimal":1} | IMF 2016: 0
- GRC|inflation|2021 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GR","value":"Greece"},"countryiso3code":"GRC","date":"2021","value":1.22394673806362,"unit":"","obs_status":"","decimal":1} | IMF 2021: 0.6
- GRC|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"GR","value":"Greece"},"countryiso3code":"GRC","date":"2023","value":3.46456960141384,"unit":"","obs_status":"","decimal":1} | IMF 2023: 4.2
- HRV|inflation|2024 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"HR","value":"Croatia"},"countryiso3code":"HRV","date":"2024","value":2.97200477643625,"unit":"","obs_status":"","decimal":1} | IMF 2024: 4
- LKA|inflation|2015 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2015","value":3.76836783062096,"unit":"","obs_status":"","decimal":1} | IMF 2015: 2.2
- LKA|inflation|2017 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2017","value":7.70413767850601,"unit":"","obs_status":"","decimal":1} | IMF 2017: 6.6
- LKA|inflation|2018 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2018","value":2.135037737132,"unit":"","obs_status":"","decimal":1} | IMF 2018: 4.3
- LKA|inflation|2019 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2019","value":3.52839358231811,"unit":"","obs_status":"","decimal":1} | IMF 2019: 4.3
- LKA|inflation|2020 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2020","value":6.15394508391737,"unit":"","obs_status":"","decimal":1} | IMF 2020: 4.6
- LKA|inflation|2021 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2021","value":7.01478071238194,"unit":"","obs_status":"","decimal":1} | IMF 2021: 6
- LKA|inflation|2022 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2022","value":49.7211021114327,"unit":"","obs_status":"","decimal":1} | IMF 2022: 45.2
- LKA|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2023","value":16.5411742279831,"unit":"","obs_status":"","decimal":1} | IMF 2023: 17.4
- LKA|inflation|2024 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"LK","value":"Sri Lanka"},"countryiso3code":"LKA","date":"2024","value":-0.42936004906973,"unit":"","obs_status":"","decimal":1} | IMF 2024: 1.2
- MAR|gdp growth|2024 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"MA","value":"Morocco"},"countryiso3code":"MAR","date":"2024","value":3.79336515978963,"unit":"","obs_status":"","decimal":1} | IMF 2024: 4.4
- NZL|gdp growth|2019 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"NZ","value":"New Zealand"},"countryiso3code":"NZL","date":"2019","value":2.32371708441623,"unit":"","obs_status":"","decimal":1} | IMF 2019: 3
- NZL|gdp growth|2020 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"NZ","value":"New Zealand"},"countryiso3code":"NZL","date":"2020","value":-0.240916114758988,"unit":"","obs_status":"","decimal":1} | IMF 2020: -1.2
- NZL|gdp growth|2021 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"NZ","value":"New Zealand"},"countryiso3code":"NZL","date":"2021","value":4.29916005216614,"unit":"","obs_status":"","decimal":1} | IMF 2021: 5.5
- NZL|gdp growth|2022 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"NZ","value":"New Zealand"},"countryiso3code":"NZL","date":"2022","value":3.34521847792682,"unit":"","obs_status":"","decimal":1} | IMF 2022: 2.7
- NZL|gdp growth|2024 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"NZ","value":"New Zealand"},"countryiso3code":"NZL","date":"2024","value":-0.868722371893952,"unit":"","obs_status":"","decimal":1} | IMF 2024: -0.3
- PRT|inflation|2023 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"PT","value":"Portugal"},"countryiso3code":"PRT","date":"2023","value":4.3112819189868,"unit":"","obs_status":"","decimal":1} | IMF 2023: 5.3
- QAT|gdp growth|2010 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2010","value":16.7315558489187,"unit":"","obs_status":"","decimal":1} | IMF 2010: 17.7
- QAT|gdp growth|2011 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2011","value":13.0214050496923,"unit":"","obs_status":"","decimal":1} | IMF 2011: 11.3
- QAT|gdp growth|2013 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2013","value":4.43070196521455,"unit":"","obs_status":"","decimal":1} | IMF 2013: 5.6
- QAT|gdp growth|2014 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2014","value":4.11911527912761,"unit":"","obs_status":"","decimal":1} | IMF 2014: 5.3
- QAT|gdp growth|2020 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2020","value":-3.5576039896784,"unit":"","obs_status":"","decimal":1} | IMF 2020: -2.7
- QAT|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2011","value":1.13836623529202,"unit":"","obs_status":"","decimal":1} | IMF 2011: 2
- QAT|inflation|2014 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2014","value":3.34972085659523,"unit":"","obs_status":"","decimal":1} | IMF 2014: 4.2
- QAT|inflation|2015 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"QA","value":"Qatar"},"countryiso3code":"QAT","date":"2015","value":1.8140772393776,"unit":"","obs_status":"","decimal":1} | IMF 2015: 0.9
- SVK|inflation|2022 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"SK","value":"Slovak Republic"},"countryiso3code":"SVK","date":"2022","value":12.774146363761,"unit":"","obs_status":"","decimal":1} | IMF 2022: 12.1
- TUN|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"TN","value":"Tunisia"},"countryiso3code":"TUN","date":"2010","value":3.33897963601068,"unit":"","obs_status":"","decimal":1} | IMF 2010: 4.4
- TZA|gdp growth|2012 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"TZ","value":"Tanzania"},"countryiso3code":"TZA","date":"2012","value":4.50015356010131,"unit":"","obs_status":"","decimal":1} | IMF 2012: 5.1
- TZA|gdp growth|2018 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"TZ","value":"Tanzania"},"countryiso3code":"TZA","date":"2018","value":5.50267599384966,"unit":"","obs_status":"","decimal":1} | IMF 2018: 7
- TZA|gdp growth|2019 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"TZ","value":"Tanzania"},"countryiso3code":"TZA","date":"2019","value":5.79999999996723,"unit":"","obs_status":"","decimal":1} | IMF 2019: 6.9
- TZA|gdp growth|2020 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"TZ","value":"Tanzania"},"countryiso3code":"TZA","date":"2020","value":1.99196460647855,"unit":"","obs_status":"","decimal":1} | IMF 2020: 4.5
- TZA|inflation|2010 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"TZ","value":"Tanzania"},"countryiso3code":"TZA","date":"2010","value":6.20015595647402,"unit":"","obs_status":"","decimal":1} | IMF 2010: 7.2
- UGA|gdp growth|2010 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2010","value":5.63761163749757,"unit":"","obs_status":"","decimal":1} | IMF 2010: 7.5
- UGA|gdp growth|2011 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2011","value":9.3916554927176,"unit":"","obs_status":"","decimal":1} | IMF 2011: 7.7
- UGA|gdp growth|2012 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2012","value":3.83745560605229,"unit":"","obs_status":"","decimal":1} | IMF 2012: 2.3
- UGA|gdp growth|2014 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2014","value":5.10630732539796,"unit":"","obs_status":"","decimal":1} | IMF 2014: 5.7
- UGA|gdp growth|2015 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2015","value":5.18785986002466,"unit":"","obs_status":"","decimal":1} | IMF 2015: 8
- UGA|gdp growth|2016 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2016","value":4.78100029254482,"unit":"","obs_status":"","decimal":1} | IMF 2016: 0.2
- UGA|gdp growth|2017 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2017","value":3.13140551723596,"unit":"","obs_status":"","decimal":1} | IMF 2017: 6.8
- UGA|gdp growth|2018 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2018","value":6.30392378262997,"unit":"","obs_status":"","decimal":1} | IMF 2018: 5.6
- UGA|gdp growth|2019 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2019","value":6.43874503276439,"unit":"","obs_status":"","decimal":1} | IMF 2019: 7.6
- UGA|gdp growth|2020 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2020","value":2.95130642218098,"unit":"","obs_status":"","decimal":1} | IMF 2020: -1.2
- UGA|gdp growth|2021 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2021","value":3.53658034070898,"unit":"","obs_status":"","decimal":1} | IMF 2021: 5.5
- UGA|gdp growth|2022 | WB: {"indicator":{"id":"NY.GDP.MKTP.KD.ZG","value":"GDP growth (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2022","value":4.58802192181773,"unit":"","obs_status":"","decimal":1} | IMF 2022: 6.2
- UGA|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2011","value":16.5643496174515,"unit":"","obs_status":"","decimal":1} | IMF 2011: 18.7
- UGA|inflation|2012 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2012","value":12.6790377224658,"unit":"","obs_status":"","decimal":1} | IMF 2012: 14
- UGA|inflation|2013 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2013","value":4.90520875694556,"unit":"","obs_status":"","decimal":1} | IMF 2013: 5.5
- UGA|inflation|2014 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2014","value":3.07570668958641,"unit":"","obs_status":"","decimal":1} | IMF 2014: 4.3
- UGA|inflation|2015 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2015","value":5.58968606251725,"unit":"","obs_status":"","decimal":1} | IMF 2015: 3.7
- UGA|inflation|2019 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"UG","value":"Uganda"},"countryiso3code":"UGA","date":"2019","value":2.86758803446899,"unit":"","obs_status":"","decimal":1} | IMF 2019: 2.1
- ZMB|inflation|2011 | WB: {"indicator":{"id":"FP.CPI.TOTL.ZG","value":"Inflation, consumer prices (annual %)"},"country":{"id":"ZM","value":"Zambia"},"countryiso3code":"ZMB","date":"2011","value":6.4293968107234,"unit":"","obs_status":"","decimal":1} | IMF 2011: 8.7

## Changes — PULL 2 vs PULL 1

no change — pull 1 rows: 1200, pull 2 rows: 1200.

## Changes — PULL 3 vs PULL 2

no change — pull 2 rows: 1200, pull 3 rows: 1200.

## Data files

- wb-imf-pull1.csv — 1200 rows, SHA-256 dc6cf6f31ec54366346d658805d6b5ec8c260b7e57c8e840c43f94cf9540df43
- wb-imf-pull2.csv — 1200 rows, SHA-256 dc6cf6f31ec54366346d658805d6b5ec8c260b7e57c8e840c43f94cf9540df43
- wb-imf-pull3.csv — 1200 rows, SHA-256 dc6cf6f31ec54366346d658805d6b5ec8c260b7e57c8e840c43f94cf9540df43

The three CSVs are byte-identical: both sources publish historical 2010–2024 values, and no value changed between the pulls. Progress notes PULL 1, PULL 2 and PULL 3 are recorded on the escrow with each CSV's row count and SHA-256; the PULL 2 note is at least 24 hours after the PULL 1 note and the PULL 3 note at least 24 hours after the PULL 2 note.
