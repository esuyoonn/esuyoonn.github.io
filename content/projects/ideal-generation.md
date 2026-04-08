---
title: "Ideal Type Face Generation & Physiognomy Analysis"
description: "Face generation system using Stable Diffusion with ideal type worldcup interface and physiognomy analysis."
date: 2025-06-01
summary: "Developed a face generation system using Stable Diffusion based on similarity scores from an ideal type worldcup interface, with a physiognomy analysis pipeline on generated images."
---

[GitHub →](https://github.com/esuyoonn/Ideal_generation)

## Overview

Developed a two-stage system that (1) generates a personalized "ideal type" face using **Stable Diffusion** and (2) performs physiognomy analysis on the generated image.

## Approach

**Stage 1 — Ideal Type Face Generation**
- Built a worldcup-style interface where users compare pairs of faces
- Computed similarity scores from user selections to guide the generation prompt
- Used Stable Diffusion to synthesize a face matching the inferred ideal type profile

**Stage 2 — Physiognomy Analysis**
- Implemented an analysis pipeline on the generated facial images
- Extracted facial feature attributes and mapped them to interpretive physiognomy categories

## Technologies
Stable Diffusion, CLIP, Python
