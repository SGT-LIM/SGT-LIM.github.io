---
title: "(Capstone) FUS (Find Undetectable Sound): Machine Learning Application to Indicate the Sound Direction"
collection: papers
permalink: /papers/capstone-find-undetectable-sound/
authors: "Youngsun Lim, Yongsoon Choi"
conference: "Proceedings of the Korean HCI Conference"
paper_link: "https://drive.google.com/file/d/1RnItVjJy5TRj-Tx6K8gnX4-KT3kn1DCQ/view?usp=sharing"
---
This paper is accepted at the Proceedings of the Korean HCI Conference 2022.

### Abstract
To address the issues caused by high-frequency noise, it is necessary to identify sounds that are not easily detectable. For this purpose, a logistic regression algorithm was developed to locate the source of the sound using a smartphone. Additionally, three apps were created to visualize the results, and their effectiveness in presenting the data was analyzed to determine the most efficient visualization method.

### Summary
#### Research Motivation and Value
The research addresses the issue of high-frequency noise, often undetectable by adults, which can cause significant stress to infants who can hear these sounds. The primary motivation is to develop a tool that helps locate the source of such noise, enabling parents to be aware of and mitigate the impact of high-frequency noise on infants. This research aims to enhance the quality of life by preventing noise-induced hearing loss and stress.

#### Methodology
1. **Data Collection**: The study involved recording high-frequency sounds (16,000 Hz) in different directions around a smartphone, simulating real-life scenarios where noise sources need to be identified.
2. **Preprocessing**: The recorded sounds were preprocessed using Mel Frequency Cepstral Coefficients (MFCC) to extract features essential for sound recognition and direction detection.
3. **Machine Learning Model**: A logistic regression algorithm was employed to classify the sound direction (left or right). Logistic regression was chosen due to its effectiveness and lower computational complexity in classification tasks.
4. **Visualization**: Three types of visualizations (Pie chart, Horizontal bar chart, Vertical bar chart) were developed to display the sound direction probabilities. These visualizations were evaluated for their usability.

#### Results
The machine learning model achieved approximately 90% accuracy in detecting the direction of the sound. The research demonstrated that high-frequency noise sources could be effectively identified using a smartphone-based application, providing valuable insights into developing tools for noise detection and prevention. The study also planned further experiments to evaluate the usability of the visualizations with participants, aiming to identify the most effective method for representing sound direction data.

#### Conclusion
This research showcases a practical application of machine learning in addressing real-world problems related to high-frequency noise detection. By improving the detection and visualization of undetectable sounds, the study contributes to enhancing auditory awareness and preventing hearing loss and stress caused by noise.

### Paper
<iframe src="https://drive.google.com/file/d/1RnItVjJy5TRj-Tx6K8gnX4-KT3kn1DCQ/preview" width="600" height="800"></iframe>
