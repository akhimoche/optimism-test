# Seligman Optimism Test

An interactive web app based on Martin Seligman's Attributional Style Questionnaire (ASQ), as described in *Learned Optimism* (1991). Built as a single self-contained HTML file — no dependencies, no backend, no data collected.

## What it does

Presents all 48 questions from the ASQ and scores responses across six dimensions of explanatory style:

| Symbol | Dimension |
|--------|-----------|
| PmG | Permanence of Good Events |
| PmB | Permanence of Bad Events |
| PvG | Pervasiveness of Good Events |
| PvB | Pervasiveness of Bad Events |
| PsG | Personalisation of Good Events |
| PsB | Personalisation of Bad Events |

It then calculates:

- **G** — Total Good Events score (PmG + PvG + PsG)
- **B** — Total Bad Events score (PmB + PvB + PsB)
- **G−B** — Overall optimism score
- **PmB + PvB** — Hopefulness score (Seligman's derived measure of hopelessness)

Each score comes with a band label and a detailed plain-English interpretation.

## Results page includes

- Overall score banner with interpretation
- Good and bad event totals with explanations
- Individual cards for all six dimensions, each with a progress bar, score band, what the dimension measures, and a specific interpretation for where you scored
- Hopefulness derived score
- Export options: print/PDF, copy to clipboard, download as standalone HTML

## Scoring

Responses are scored according to the original ASQ key. Higher scores on good-event dimensions and lower scores on bad-event dimensions indicate a more optimistic explanatory style.

## Usage

Just open `index.html` in any modern browser. No installation, no internet connection required (except for loading the Google Fonts, which degrade gracefully if unavailable).

## Live version

[Take the test →](https://yourusername.github.io/optimism-test) *(update this link once deployed)*

## Based on

Seligman, M. E. P. (1991). *Learned Optimism*. Knopf.
