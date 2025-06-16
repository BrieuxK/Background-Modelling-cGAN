# Background-Modelling-cGAN

Conditional Generative Adversarial Network (CGAN) applied to background modelling for the CMS particle detector in CERN.

The goal of this thesis was to propose an innovative approach to a persistent problem in particle physics. Specific events currently investigated in high energy physics come with overwhelming background. The majority of this background can be eliminated with straightforward techniques as filters. However, some specific physical processes remain unfiltered and throw false positive alerts. The goal was to tackle these remaining background components with generative machine learning techniques in order to remove them from the final data sample.

The differents steps were :

1. Extract, transform and load official CERN data
2. Design a 1D model to assess the potential of the approach in replicating target data
3. Expend to 2D
4. Expend the model's scope to replicating the underlying patterns between the selected variables
5. Expend to 3D (can go beyond but stopped here for academic reasons)
6. Assess the quality of generated data


In this first set of results, we can observe the performance of the model in replicating the distribution of the 3 selected variables.

<!-- Row 1 -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/7b2f8898-1e74-4069-9348-c8701021baaa" width="30%" />
  <img src="https://github.com/user-attachments/assets/84cf9727-5adc-4e96-b691-b0d9708cac4c" width="30%" />
  <img src="https://github.com/user-attachments/assets/fca9175f-c5f1-487e-9a27-fb33b42bc799" width="30%" />
</p>

Here lies the main result of this project : the capacity of the model to replicate underlying patterns between variables.

<!-- Row 2 -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/a0e64bd9-040f-4396-8253-bd1a8fe15748" width="45%" />
  <img src="https://github.com/user-attachments/assets/d980801f-1acd-4dde-a627-fb8933cfcaa0" width="45%" />
  <img src="https://github.com/user-attachments/assets/86974b6b-9476-437d-9cfe-0b8abe39af65" width="45%" />
</p>
