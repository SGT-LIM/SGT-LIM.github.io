---
layout: post
title: "[JDCS22] (Main) FUS (Find Undetectable Sound): An Application to Indicate Sound Direction"
collection: papers
permalink: /papers/main-find-undetectable-sound/
date: 2024-06-23
authors: "Youngsun Lim, Yongsoon Choi"
conference: "Journal of Digital Contents Society (JDCS)"
paper_link: "https://drive.google.com/file/d/1iX-k2BUr_70kWcupbTsDzPRhipt8frZy/view?usp=sharing"
---
This paper is published in the Journal of Digital Contents Society (JDCS) 2022 (Korean Citation Index).

## Abstract

When a child is exposed to high-frequency noise, problems such as noise-induced hearing loss may occur, but it is difficult for ordinary adults to recognize noise at a higher frequency than the audible frequency. To solve this problem, an application was developed to easily find a location where high-frequency noise occurs with a smartphone through the algorithm that compares the size of the sound wave. After selecting the initial design using bar charts and gradations through preliminary experiments, users conducted an experiment to find the location of high-frequency sound using the application. As a result of the experiment, a plurality of users were able to find a location where high-frequency noise occurred. In addition, as a result of the survey analysis, the service received a positive response that it was possible to find an audible high-frequency noise. In addition, we intend to develop future versions of applications that can find sound more conveniently by discussing ways to improve future designs and functions familiarly and reliably and simplify usage.

## Method

### Application Summary

FUS (Find Undetectable Sound) is a smartphone application designed to detect sounds that are difficult for humans to hear and indicate their direction. The application utilizes the recording feature on smartphones to collect sound data. Users record sounds from two different directions (e.g., left and right), then upload these sound files to the application. The application processes these files using Librosa, an audio processing library in Python, which converts the audio data into numerical values representing the sound's magnitude. By comparing these values, the application determines the direction from which the sound originated and displays this information graphically.

### Algorithm

1. **Sound Data Collection**: Users record sound from two directions using their smartphone's microphone.
2. **Pre-processing with Librosa**: The recorded audio files are uploaded to the application and processed using Librosa, which extracts the sound amplitude over time.
3. **Data Cleaning**: The initial and final seconds of the audio data are trimmed to remove potential noise from handling the phone.
4. **Amplitude Calculation**: The absolute values of the sound amplitudes are calculated, and their average is used to determine the sound's magnitude.
5. **Direction Determination**: The application compares the average amplitudes from the two recordings. The direction with the higher average amplitude is identified as the source of the sound.
6. **Graphical Representation**: The application displays a bar chart indicating the direction of the sound, with gradient coloring to enhance visual clarity.

### User Experiment

1. **Participants**: The main experiment involved 22 participants (20s-30s age range), who were briefed on the experiment's purpose and method.
2. **Procedure**: Participants, wearing earplugs to block the high-frequency noise, recorded sounds from two directions. They then used the application to identify the sound's direction, repeating the process three times.
3. **Survey**: After the experiment, participants completed a survey based on Peter Morville's HoneyComb model to assess the application's usefulness, usability, findability, and credibility. The survey included 12 Likert-scale questions and additional open-ended feedback.

## Results

- The application achieved a correct detection rate of approximately 72.7%.
- The average scores on the survey indicated overall positive feedback, with higher ratings for questions related to the application's purpose alignment, usability, and reliability of directional information.
- Participants suggested improvements for making the application more intuitive and enhancing the design for better user experience.

## Value of the Paper

This paper presents a novel application that addresses the problem of detecting high-frequency noises, which are often inaudible to adults but can cause hearing damage and stress in children and pets. The application leverages common smartphone features, making it accessible and cost-effective. The user study demonstrates the application's effectiveness and highlights areas for improvement, paving the way for future enhancements that could make the application more reliable and user-friendly. This work contributes to the fields of HCI, audio signal processing, and mobile application development, offering a practical solution for sound direction detection.

---

## Paper
<iframe src="https://drive.google.com/file/d/1iX-k2BUr_70kWcupbTsDzPRhipt8frZy/preview" width="600" height="800"></iframe>
