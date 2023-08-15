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

"Science has profoundly altered the conditions of man's life both materially and in ways of the spirit as well." - J. Robert Oppenheimer

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/1_pr.wav" type="audio/wav"></audio>

Spectrogram: 

<img src="img\real_1.png" alt="real_1" style="zoom: 50%;" /><img src="img\real_1_pr.png" alt="real_1_pr" style="zoom: 50%;" />

### Sample 2

"So first of all, let me assert my firm belief that the only thing we have to fear is fear itself." - Franklin D. Roosevelt

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/2_pr.wav" type="audio/wav"></audio>

Spectrogram: 

<img src="img\real_4.png" alt="real_4" style="zoom:50%;" /><img src="img\real_4_pr.png" alt="real_4_pr" style="zoom:50%;" />

### Sample 3

"We choose to go to the Moon in this decade and do the other things, not because they are easy, but because they are hard; because that goal will serve to organize and measure the best of our energies and skills, because that challenge is one that we are willing to accept, one we are unwilling to postpone, and one we intend to win, and the others, too." - John F. Kennedy

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/3_pr.wav" type="audio/wav"></audio>

Spectrogram:

<img src="img\real_5.png" alt="real_5" style="zoom: 33%;" /><img src="img\real_5_pr.png" alt="real_5_pr" style="zoom: 33%;" />

## Settings of Each Layer

Layers are listed in order of precedence, from top to bottom.

<img src="img\Network Settings.PNG" alt="Network Settings" style="zoom:100%;" />

## Acknowledgement

Our work was built based on AERO (https://github.com/slp-rl/aero). Thanks for their great work.
