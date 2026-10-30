# Privacy under Article 21 in the Supreme Court of India, 2021 to 2026

## Team
- Nandini Sodani, [section], Symbiosis Law School, Nagpur
- [Member 2 name and section]

## Topic
This project looks at how the Supreme Court of India has treated the right to privacy under Article 21 since 1 September 2021, the period after *Puttaswamy* (2017) had made privacy a fundamental right. Our question is whether the Court has moved from treating privacy as a liberty and autonomy right (bodily and reproductive choice) towards something closer to informational self-determination (control over data, communications and location), and whether it protects privacy less absolutely as time goes on. The analysis page is `index.html`.

## How we found the judgments
We searched the Supreme Court Observer's privacy tag, LiveLaw, Verdictum, SCC Online and the Supreme Court's own PDF portal, using terms such as "right to privacy", "Article 21", "surveillance", "DNA test", "electoral bonds", "informational privacy" and "bail condition location". We looked at roughly 40 hits and kept judgments only if they were (1) decided between 1 September 2021 and 31 August 2026, (2) reasoned judgments rather than interim or listing orders, and (3) a case in which a privacy claim under Article 21 was a live question the Court decided. We excluded pending matters (for example the digital-device search guidelines case) and stays. That left 11 judgments. Where the Court's own PDF could be found we use it as the source link; the other links are to the copy we read and are marked for replacement in `VERIFY.md`.

## What the data shows
![Judgments per year](chart1-per-year.png)

Decisions are spread thinly across the period (one to three a year), with 2024 and 2025 the busiest. Each case is tagged by its main dimension of privacy. Informational privacy and surveillance (4 cases) and bodily privacy against compelled testing (5) dominate; decisional autonomy and dignity (2) appears only in 2022 and 2024. What surprised us was how much of the Court's privacy case law comes from family and evidence law, mainly DNA-test orders, rather than from data protection.

![Did the privacy claim prevail?](chart2-privacy-outcome.png)

The privacy claim prevailed in 8 of 11 cases. All four decisions up to 2023 favour privacy, and all three in which privacy yielded come in 2024 or later: Electoral Bonds (2024), *Vibhor Garg v. Neha* (2025) and *Chaturbhuj Pradhan v. Amar Pradhan* (2026). The DNA line shows the change well: *Inayath Ali* (2022) treats testing as an intrusion not to be ordered as a matter of course, while *Chaturbhuj Pradhan* (2026) orders a test because the son's interest outweighs the father's privacy. This fits a move from privacy as a near-trump to privacy as one interest to be balanced, but with 11 cases it is a pattern to test, not a trend.

![Who brought the case and who won](chart3-who-brought-won.png)

Nine of the eleven cases were brought by individuals, one by an NGO and one by a State; no company appears. The party who brought the case won in ten of eleven, the exception being the 2026 paternity appeal. We expected more State-versus-citizen surveillance cases, but only *Pegasus*, Electoral Bonds and *Frank Vitus* fit that description. We also expected the phrase "informational self-determination", but in the passages we read the Court keeps to the *Puttaswamy* vocabulary of dignity, autonomy and proportionality.

## Limits
Eleven judgments are a small and non-random sample, and the tags ("dimension", "prevailed or yielded") are our own judgment calls. Most benches had two judges, and only one had five, so these cases show how the Court applies *Puttaswamy*, not how it might extend it. Nothing here shows what High Courts are doing, which is where several right-to-be-forgotten and data cases have arisen. The window is five years, so it cannot show the earlier path from *Kharak Singh* to *Puttaswamy*.

## AI-use disclosure
We used Claude (Anthropic) to help find candidate judgments, read and summarise them, fill the Dataset template, draw the charts and draft `index.html` and this README. Claude could read some judgments directly from the Supreme Court's PDFs (*Electoral Bonds*, *R. Rajendran*, *Chaturbhuj Pradhan*) but relied on law-report and commentary pages for others. The coding in `data.xlsx` is therefore a draft which each team member has to check against the official judgment before it is relied on; the "Coded by" column names the member who did that check, and `VERIFY.md` lists what to confirm.
