---
layout: default
---

# Demo of SDNet

## Test Set Samples

&emsp;&emsp;&emsp;&emsp;**Noisy(at 8kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Ours**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/1.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/2.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/3.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/4.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/5.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/6.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/7.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/7.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/7.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/8.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/8.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/8.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/9.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/9.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/9.wav" type="audio/wav"></audio>

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/10.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/10.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/10.wav" type="audio/wav"></audio>

## Real World Samples

In this part, we selected some old speech to repair their quality. Some samples are below.

### Sample 1

" Science has profoundly altered the conditions of man's life both materially and in ways of the spirit as well. " - J. Robert Oppenheimer

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/1_pr.wav" type="audio/wav"></audio>

Spectrogram: 

<img src="img\real_1.png" alt="real_1" style="zoom: 50%;" /><img src="img\real_1_pr.png" alt="real_1_pr" style="zoom: 50%;" />

### Sample 2

" If someone, again who hadn't been here before, asked you ‘ Is it safe to come to Northern Ireland? ’ What would you say? " - From an old interview

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/2_pr.wav" type="audio/wav"></audio>

Spectrogram: 

<img src="img\real_8.png" alt="real_8" style="zoom:50%;" /><img src="img\real_8_pr.png" alt="real_8_pr" style="zoom:50%;" />

### Sample 3

" Begin the day with Able Mabel. She'll wake you at your preset time. " - From an old TV advertisement

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/3_pr.wav" type="audio/wav"></audio>

Spectrogram:

<img src="img\real_9.png" alt="real_9" style="zoom: 50%;" /><img src="img\real_9_pr.png" alt="real_9_pr" style="zoom: 50%;" />

## Settings of Each Layer

Layers are listed in order of precedence, from top to bottom. The last dimension may be different based on the duration of input speech.

<img src="img\Network Settings.PNG" alt="Network Settings" style="zoom:100%;" />

## Acknowledgement

Our work was built based on AERO (<https://github.com/slp-rl/aero>). Thanks for their great work.
