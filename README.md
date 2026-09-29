# Data Security and Behavior of Minors on Social Media Platforms in Albania: The Case of TikTok

**Bachelor's Microthesis — Economic Informatics**
University of Tirana, Faculty of Economics, Department of Statistics and Applied Informatics
Author: Kamelisa Selami · Supervisor: Dr. Matilda Veliu · Tirana, 2025

[Read the full thesis (PDF)](Thesis-Kamelisa-Selami-Data-Security-Minors-TikTok.pdf)

## Context

On 6 March 2025, Albania's Council of Ministers ordered a nationwide, 12-month block of TikTok, citing risks to minors' psycho-social development and personal data protection — the only full national ban of its kind in Europe. This thesis asks a simple question the ban itself didn't answer: **did it actually change how minors use the platform, or just how they access it?**

## Research question & hypotheses

Drawing on a survey of 203 students across two schools in Tirana (ages 12–18), the study tested three hypotheses:

1. **Continued usage** — Did a majority of minors keep using TikTok after the ban, and how?
2. **Privacy awareness → protective behavior** — Does knowing TikTok collects personal data actually change what minors do (e.g. using fake email addresses)?
3. **Usage intensity → emotional impact** — Does how much minors use TikTok relate to how they say they feel afterward?

## Methodology

- **Sample:** 203 students — 159 from Myslym Keta High School (ages 15–18), 44 from Betim Muço Elementary School (ages 12–14). Purposive sampling across early/late adolescence.
- **Instrument:** an anonymous, printed survey (Albanian and English versions in the appendix), pre-tested with 12 students not included in the final sample. **No names, IPs, or device metadata were collected** — participation was voluntary, anonymous, and consented to by school administrators, in line with GDPR Article 8 and Albania's Law No. 18/2017 on Children's Rights.
- **Analysis:** RStudio (`janitor`, `dplyr`, `ggplot2`); one-proportion z-test, chi-square tests of independence, one-way ANOVA, and Fisher's exact test.

## Key findings

| Finding | Result |
|---|---|
| Continued TikTok use post-ban | **84.5%** of minors, mainly via VPNs (one-proportion z-test, χ² = 90.28, p < 0.0001) |
| Usage by age group | 100% continued use among 12–14 and 17–18 year-olds, vs. 81% among 15–16 year-olds |
| Usage by gender | 86.6% of females vs. 74% of males report ongoing use |
| Data awareness → fake email use | Significant association (χ², p = 0.0045) — awareness does translate into *some* protective behavior |
| Usage intensity → emotional state | No statistically significant relationship (ANOVA, p = 0.067), though a trend was visible |
| Harmful content: seen vs. reported | 60% had seen harmful content; only 5% of those ever reported it (Fisher's exact, p < 0.001) — a clear **knowledge–action gap** |

See [`charts/`](charts) for the underlying figures, and the PDF's Appendix C for full statistical output.

## Conclusion

A ban without enforcement or education functions more as a political signal than a protective measure: minors adapted around the block rather than disengaging. The thesis argues for reorienting Albanian child-data-protection policy from **prohibition to participation** — integrating digital literacy into the national curriculum, pairing any future restrictions with transparency and independent review, and aligning with EU standards on algorithmic transparency and age-appropriate design.

## Tools

RStudio, R (`janitor`, `dplyr`, `ggplot2`), survey design and statistical hypothesis testing (z-test, chi-square, ANOVA, Fisher's exact test), GDPR / Albanian data-protection law analysis.
