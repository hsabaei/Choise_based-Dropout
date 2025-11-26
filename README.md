# Choise_based-Dropout
Choice-Based Dropout trains K dropout variants each epoch and keeps the best one.
It gives small but consistent gains on MLPs (≈0.5% test improvement) and mixed results on CNNs, where the benefits are negligible.
The method is simple but computationally heavier, and works best when dropout strongly affects model stability.


<img width="364" height="364" alt="{528DE0FC-5801-45BA-BCBE-2F38667EA44E}" src="https://github.com/user-attachments/assets/daf268cf-9933-4fee-b15a-b6e85a4aa465" />
