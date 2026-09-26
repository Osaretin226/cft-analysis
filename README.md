# CFT Analysis — Composite Scoring Pipeline

Python implementation of a composite scoring analysis for a Cognitive
Flexibility Task, originally designed and validated as part of my
undergraduate research (PSY 403, University of Ibadan).

## What this does
- Loads participant scores (processing speed and set-shifting capability)
- Calculates a weighted composite score (CCFS): `0.6 × PS + 0.4 × SCS`
- Generates descriptive statistics across the participant group
- Visualizes the score distribution

## Background
The original instrument was designed, built, and validated (inter-rater
reliability, content validity testing) as part of a Test Construction
course project. This repository rebuilds the analysis pipeline in Python
as part of ongoing technical skill development ahead of postgraduate
study in NeuroAI.

## Status
Currently using mock data structured to match the real dataset. Will be
updated with the original study's data.

## Tools
Python, pandas, matplotlib
