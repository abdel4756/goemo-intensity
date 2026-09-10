# GoEmotions Intensity Dataset

## Overview
This dataset contains 57,713 real Reddit comments with fine-grained **emotion intensity scores** for 28 emotion categories. Unlike standard binary emotion classification datasets, each emotion is scored on a continuous 0.0–1.0 scale derived from inter-annotator agreement ratios in the original GoEmotions corpus (Google Research).

## Source
Derived from [GoEmotions](https://github.com/google-research/google-research/tree/master/goemotions) by Google Research (Demszky et al., 2020).

## License
CC-BY-4.0

## Files
- `emotions.csv` — 57,713 labeled examples with 28 emotion intensity columns.
- `emotions_list.txt` — The 28 emotion categories.

## Schema (emotions.csv)
| Column | Type | Description |
|---|---|---|
| id | string | Unique UUID |
| text | string | Reddit comment |
| admiration…neutral | float | Intensity (0.0 = absent, 1.0 = full annotator agreement) |
