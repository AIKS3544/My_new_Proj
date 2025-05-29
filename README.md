# StressSense: AI-Based Stress Level Estimator via Voice Analysis

Final project for the Building AI course

## Summary

StressSense is a voice-based AI tool that detects stress levels in real-time by analyzing vocal tone, pitch, and speech patterns, helping users manage their mental health.  
Building AI course project

## Background

Stress-related conditions are a leading cause of mental and physical illness worldwide, yet many people fail to recognize early signs of stress. Wearables exist, but they can be expensive or inconvenient to use.

This project aims to:
* provide accessible stress monitoring through voice alone
* help users detect hidden signs of mental strain
* support early mental health intervention

Motivation: With growing burnout and anxiety in modern life, a lightweight AI tool that listens and provides feedback could promote awareness and self-care.

## How is it used?

The user speaks naturally into their phone or computer (e.g., during a journal entry, work call, or check-in). The app analyzes audio input to evaluate stress indicators like elevated pitch, faster tempo, or inconsistent rhythm.

Useful for:
* Remote workers
* Therapists and life coaches
* Mental health self-care routines

<img src="https://upload.wikimedia.org/wikipedia/commons/3/37/Woman_wearing_headphones_and_speaking.jpg" width="300">

## Data sources and AI methods

Data sources:
* Public speech emotion datasets like [RAVDESS](https://zenodo.org/record/1188976)
* Open voice samples labeled with emotional states

AI methods:
* Feature extraction (MFCCs, pitch, tempo)
* Classification with deep neural networks or SVMs
* Potential extension with LSTM networks for temporal emotion patterns

| Data Source | Description |
|-------------|-------------|
| RAVDESS      | Labeled emotional speech dataset |
| Custom user data | Optional personalization with user permission |

## Challenges

StressSense _does not_:
* Provide clinical diagnoses
* Work equally well across all languages or accents
* Guarantee accuracy in noisy environments

Ethical concerns:
* Privacy and consent when recording voices
* Bias from training data (age, gender, accent)
* Transparency about how analysis is made

## What next?

* Improve personalization using individual baseline calibration
* Develop mobile app prototype with real-time feedback
* Integrate breathing and mindfulness suggestions based on detected stress level

What’s needed:
* More diverse voice datasets
* Support from mental health professionals
* UX designers for intuitive and calming interface

## Acknowledgments

* [RAVDESS Dataset on Zenodo](https://zenodo.org/record/1188976)
* [Image: Woman with headphones by Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Woman_wearing_headphones_and_speaking.jpg) / [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0)
* Inspired by apps like Wysa and Mindstrong, but aimed at a lighter, more accessible use case
