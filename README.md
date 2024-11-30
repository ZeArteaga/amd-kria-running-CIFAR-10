# amd-kria-running-CIFAR-10
Made in the context of a group project for an **Embedded AI** course (University of Twente) - **Group 7**.

# Steps (fill-in)
- [ ] 1. Training a CNN to classify the CIFAR-10 dataset. The target test accuracy for this project is 90% or more.
- [ ] 2. Using [KRIA KV260](https://www.amd.com/en/products/system-on-modules/kria/k26/kv260-vision-starter-kit.html) board to infer the trained CNN without using the FPGA (CPU only using numpy and weights / bias not tensorflow) and measure the [performance metrics](https://docs.google.com/spreadsheets/d/1PJPRZUFgHM_1D1Kx5eAISgnVnhnDLMWt/edit?usp=sharing&ouid=106156661825394405985&rtpof=true&sd=true).
- [ ] 3. Using VITIS-AI (or an alternative platform, in consultation with the TA) and the FPGA fabric of the KRIA board to accelerate inference of the neural network and measure the [performance metrics](https://docs.google.com/spreadsheets/d/1PJPRZUFgHM_1D1Kx5eAISgnVnhnDLMWt/edit?usp=sharing&ouid=106156661825394405985&rtpof=true&sd=true). This step aims to increase the inference throughput (inference per second) as much as possible without considerable loss of accuracy. You may need to revise your neural network in step 1 to achieve this (co-optimization of hardware and algorithm)
