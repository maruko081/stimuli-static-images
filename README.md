# stimuli-static-images
This repository contains the static image stimuli used in the experiments of the thesis.

# Static Image Stimuli for Liveliness Perception Experiments

This repository contains the **static image stimuli** used in the experiments of the graduation thesis:

> *From Density to Liveliness: Construction of a Spatial Liveliness Estimation System “Lively” Using MOT*

The stimuli were designed to investigate how different visual and social factors
(e.g., crowd density, demographic attributes, environment, and social interaction)
affect human perception of urban liveliness.

---

## Overview of Stimuli

The repository includes **two types of static image stimuli**, each serving a different role in the experiments.

---

## 1. Single-condition stimuli (15 images)

**Directory:** `single_condition_images/`

These images represent the **base experimental conditions**.
Each image corresponds one-to-one with `Img_01`–`Img_15` used throughout the thesis.

- Generated using an AI-based image generation model
- No real individuals are depicted
- No personal or identifiable information is included

Each stimulus systematically manipulates one or more factors while keeping others constant, such as:

- Crowd size (e.g., 5 / 20 / 50 / 200 people)
- Demographic composition (gender, age)
- Environmental context (static background, festival-like background, café-like background)
- Clothing (casual vs. formal suits)
- Social interaction (interactive vs. walking alone)

---

### Mapping between Img IDs and file names

| Img ID | Condition summary | File name |
|------|------------------|-----------|
| Img_01 | Medium (20), mixed crowd (standard) | bb_all_20.png |
| Img_02 | Medium (20), men only | bb_onlymen_20.png |
| Img_03 | Medium (20), women only | bb_onlywomen_20.png |
| Img_04 | Medium (20), children only | bb_onlychildren_20.png |
| Img_05 | Medium (20), adults only | bb_mixadult_20.png |
| Img_06 | Low (5), mixed crowd | bb_all_5.png |
| Img_07 | High (50), mixed crowd | bb_all_50.png |
| Img_08 | Very high (200), mixed crowd | bb_all_200.png |
| Img_09 | Medium (20), festival-like background | bb+_all_20.png |
| Img_10 | Low (5), festival-like background | bb++_all_5.png |
| Img_11 | Medium (20), café-like background | bb++_all_20.png |
| Img_12 | Medium (20), men in business suits | bb_onlymen_20_suits.png |
| Img_13 | High (50), men in business suits | bb_onlymen_50_suits.png |
| Img_14 | Medium (20), mixed crowd, no interaction | bb_all_20_alone.png |
| Img_15 | High (50), mixed crowd, no interaction | bb_all_50_alone.png |

---

## 2. Pairwise comparison stimuli (21 images)

**Directory:** `pairwise_comparison_images/`

These images were created by **horizontally concatenating two single-condition stimuli**.
They were used exclusively in the questionnaire-based experiment
to allow participants to directly compare two scenes.

- File names: `q1.png` – `q21.png`
- These images are **presentation-format stimuli**, not new experimental conditions
- Each image corresponds **one-to-one** with the comparison pairs
  listed in the thesis table *“Static Comparison List”*

---

### Mapping between comparison IDs and stimulus pairs (summary)

| q ID | Comparison focus | Left image | Right image |
|----|----------------|-----------|------------|
| q1 | Gender diversity | Img_02 (men only) | Img_01 (mixed) |
| q2 | Gender diversity | Img_03 (women only) | Img_01 (mixed) |
| q3 | Gender baseline | Img_02 (men) | Img_03 (women) |
| q4 | Age diversity | Img_05 (adults) | Img_01 (mixed) |
| q5 | Age diversity | Img_04 (children) | Img_01 (mixed) |
| q6 | Age baseline | Img_04 (children) | Img_05 (adults) |
| q7 | Density effect | Img_06 (low) | Img_01 (medium) |
| q8 | Density effect | Img_01 (medium) | Img_07 (high) |
| q9 | Density saturation | Img_07 (high) | Img_08 (very high) |
| q10 | Density range | Img_06 (low) | Img_08 (very high) |
| q11 | Environmental effect | Img_01 (static bg) | Img_11 (café bg) |
| q12 | Environmental effect | Img_11 (café bg) | Img_09 (festival bg) |
| q13 | Environmental range | Img_01 (static bg) | Img_09 (festival bg) |
| q14 | Environment vs quantity | Img_07 (50, static) | Img_09 (20, festival) |
| q15 | Environment vs quantity | Img_01 (20, static) | Img_10 (5, festival) |
| q16 | Attribute vs environment | Img_04 (children) | Img_10 (festival) |
| q17 | Attribute vs environment | Img_04 (children) | Img_11 (café) |
| q18 | Quality vs quantity | Img_01 (mixed) | Img_13 (50 suits) |
| q19 | Clothing effect | Img_02 (men casual) | Img_12 (men suits) |
| q20 | Social interaction | Img_14 (alone) | Img_01 (interactive) |
| q21 | Social interaction vs density | Img_14 (alone) | Img_07 (interactive, high) |

---

## Directory Structure

stimuli-static-images/
├─ single_condition_images/
│ └─ 15 base stimuli (Img_01–Img_15)
│
├─ pairwise_comparison_images/
│ └─ 21 questionnaire stimuli (q1–q21)
│
└─ README.md


---

## Notes on Data Usage and Ethics

- All images were generated using an image generation model.
- No real people, personal data, or identifiable individuals are included.
- The images are released for **academic and research purposes only**.
- Redistribution or secondary use beyond academic contexts should be discussed with the author.

---

## Excluded Data

Video stimuli used in the experiments were collected and edited from publicly available online videos.
Due to copyright considerations, **video stimuli are not included** in this repository.

---

## Reproducibility

By publicly releasing the static image stimuli,
this repository aims to support transparency and reproducibility
in research on visual perception of urban liveliness.


---

## Example Stimuli (Figures)

To illustrate the structure of the stimuli used in the experiments,
example images are shown below.

### Example of a single-condition stimulus (Img_01)

The following image corresponds to **Img_01**, which serves as the standard reference condition
(medium crowd size, mixed demographics, static background).

<p align="center">
  <img src="single_condition_images/bb_all_20.png" alt="Img_01: single-condition stimulus" width="500">
</p>

Note: All other single-condition stimuli (Img_02–Img_15) were generated
by systematically modifying one or more attributes of this reference image.

---

### Example of a pairwise comparison stimulus (q1)

The following image corresponds to **q1**, a pairwise comparison stimulus created by
horizontally concatenating two single-condition images.
In this example, a homogeneous crowd (men only) is compared with a mixed crowd.

<p align="center">
  <img src="pairwise_comparison_images/q1.png" alt="q1: pairwise comparison stimulus" width="700">
</p>

These pairwise stimuli were used exclusively for questionnaire-based comparisons
and do not represent additional experimental conditions.

