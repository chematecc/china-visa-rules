# China visa rules by passport (open data)

Which ordinary passports can enter **mainland China without a visa**, under which policy, and until when. One row per passport (194), checked daily against official Chinese sources.

**Rules last changed 2026-09-29.** This copy was checked against the official sources on 2026-10-07; the live answers for every passport, in 9 languages, and the latest check date are at **[chinavisacheck.com](https://chinavisacheck.com/china-visa/)**

| Policy | Countries | Stay | Notes |
|---|---|---|---|
| 30-day unilateral visa-free entry | 50 | 30 days | Most valid until 2026-12-31; Russia until 2027-12-31; Brunei no end date |
| Mutual visa exemption | 29 | usually 30 days per entry | Bilateral agreements |
| 240-hour visa-free transit | 57 | 10 days | Onward ticket to a third country; 65 ports in 24 provinces |
| Hainan 30-day visa-free | 61 | 30 days | Hainan Province only |
| 24-hour airside transit | all | 24 hours | Stay in the airport transit area |

Visa-free entry covers tourism, business, visiting family and friends, exchange visits and transit. It never covers work, study or journalism, and stays over 30 days need a visa.

## Files

- [`data/china-visa-by-passport.csv`](data/china-visa-by-passport.csv): one row per passport: `country, iso2, visa_free_30_days, basis, valid_until, transit_240_hour, hainan_30_day, airside_transit_24_hour, page`
- [`data/china-visa-rules.json`](data/china-visa-rules.json): the same rules grouped by policy, with sources (also served at https://chinavisacheck.com/data/china-visa-rules.json)
- Plain-text summary of every passport: https://chinavisacheck.com/llms-full.txt

## Official sources

- https://cs.mfa.gov.cn/gyls/lsgz/fwxx/202602/t20260215_11860470.shtml
- https://ca.china-embassy.gov.cn/lsyw/lszj/mqzc00/gbrjmq00/202501/t20250116_11535148.htm
- https://www.news.cn/20260820/5dc69b0a18a942f1aedc927f700b4deb/c.html
- https://cs.mfa.gov.cn/gyls/lsgz/fwxx/202504/t20250414_11594222.shtml
- https://en.nia.gov.cn/n147418/n147463/c183390/content.html

Rules change; the 30-day list is due to expire on 2026-12-31 unless China extends it. Check the date above, or the live answer at [chinavisacheck.com](https://chinavisacheck.com/china-visa/), before relying on a row. Not legal advice; not a government source.

## Licence

[CC BY 4.0](LICENSE). Credit: **China Visa Check (chinavisacheck.com)**, published by OttoLux.
