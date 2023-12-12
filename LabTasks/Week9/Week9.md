# Week9 - Analysing and Extracting Meaning from Audio
## Task 1-Extract Features
For this week's task, I used the same tracks from last week's assignment. Below is a screenshot of the transformations we had to perform in Sonic Visualiser (Spectrogram, Mel Frequency Cepstral Coefficients, and Chromagram).
### Cruel Summer-Taylor Swift
<img width="438" alt="image" src="https://github.com/Vvvi00/MCA-2023/assets/145675705/7a9afd2f-a96f-452c-85b6-6fbf58277bf7">

### Animals-Martin Garrix
<img width="478" alt="image" src="https://github.com/Vvvi00/MCA-2023/assets/145675705/86643e4a-c26d-4b91-bba5-933432bcb47c">

### Queencard-(G)Idle
<img width="463" alt="image" src="https://github.com/Vvvi00/MCA-2023/assets/145675705/61bf281a-e178-4916-87d5-d5dc3028e97f">

## Task 2-Compute and visualize features with histograms
### Computed Spectrograms to Histograms

Cruel Summer-Taylor Swift | Animals-Martin Garrix | Queencard-(G)Idle
------- | ------- | -------
![cruel summer-spec](https://github.com/Vvvi00/MCA-2023/assets/145675705/344e39c3-c6b2-45ae-a762-c0b49e7c7be6) | ![animals-spec](https://github.com/Vvvi00/MCA-2023/assets/145675705/e1cbd86d-fb1a-4898-b995-884aba5b5709) | ![queencard-spec](https://github.com/Vvvi00/MCA-2023/assets/145675705/7d6bbc55-2c56-4861-ab39-60c1ca1e38ae)

### Computed MFCC's to Histograms

Cruel Summer-Taylor Swift | Animals-Martin Garrix | Queencard-(G)Idle
------- | ------- | -------
![Cruel Summer-MFCC-p4](https://github.com/Vvvi00/MCA-2023/assets/145675705/dfd1dcfd-a69e-46bd-bc1c-7b646a4ae678) | ![Animals-MFCC-p4](https://github.com/Vvvi00/MCA-2023/assets/145675705/ed844633-f50c-45a7-ac43-e9c6fe38597e) | ![Queencard-MFCC-p4](https://github.com/Vvvi00/MCA-2023/assets/145675705/8ef2f448-9b28-4e61-b437-82b4ed24ab61)

### Computed Chromagrams to Histograms

Cruel Summer-Taylor Swift | Animals-Martin Garrix | Queencard-(G)Idle
------- | ------- | -------
<img width="540" alt="截屏2023-12-12 03 23 57" src="https://github.com/Vvvi00/MCA-2023/assets/145675705/cd1b273d-33fe-4128-bf6e-02609f1094c6"> | <img width="534" alt="截屏2023-12-12 03 24 22" src="https://github.com/Vvvi00/MCA-2023/assets/145675705/29de4071-becb-4306-8ffb-d9557d13539c"> | <img width="535" alt="截屏2023-12-12 03 24 48" src="https://github.com/Vvvi00/MCA-2023/assets/145675705/41772c45-082a-4460-8a45-2c6ed9488abd">

### Analysis and Compare the histograms
I have no previous background in music theory, and through this task I have found that histograms help to identify significant differences between tracks. For example, since all 3 songs are pop music and somewhat similar in tempo, if listened to individually they may not seem to have particularly significant differences, but a histogram can visualize them well.

For this part of the task I decided to compare the histograms calculated from the Mel Frequency Cepstrum Coefficients (MFCC) for each track. In MFCC, the frequency bands are equally spaced on the Mel scale, which is closer to the response of the human auditory system than the linearly spaced bands used in normal spectra, and this frequency distortion allows for a better representation of the sound. Considering that the three tracks I'm going to compare, although from different places and genres, all fall under the broad umbrella of pop music aurally, they may be partially similar. This is indeed the case, as we can see from the histogram above. However, they still have differences that exist; Animals will have more accents and drums than Cruel Summer, and as a result its peaks will be higher and more numerous than Cruel Summer.
