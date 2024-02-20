# MeMoS Study (Memory, Money, & Self)

Welcome to the MeMoS Study repository! This repository contains materials and documentation related to the MeMoS Study, which investigates the impact of intrinsic and extrinsic motivation on decision strategies in memory-based tasks.

## About the Study

The MeMoS Study aims to determine whether intrinsically or extrinsically directed behavior may impact decision strategies for a memory-based task. The study compares behavior between four performance-based recognition memory tasks: baseline, "do better," memory-focused, and money-focused. This task is adapted from the classic criterion shifting task by Sara Leslie in 2023.

## Repository Structure

- `memos-study-baseline/`: Materials and documentation related to the baseline task condition.
- `memos-study-do-better/`: Materials and documentation related to the "do better" task condition.
- `memos-study-memory/`: Materials and documentation related to the memory-focused task condition.
- `memos-study-money/`: Materials and documentation related to the money-focused task condition.

Each folder contains specific materials, such as code, data, documentation, and analysis scripts, relevant to the corresponding task condition.

## Experiment Order

1. Baseline Task
2. Do Better Task
3. Memory Task or Money Task
4. Money Task or Memory Task

In each task it is possible to earn up to $5, except $5 in the second task if you earned $5 in the first task, because it is the only of the 4 tasks that pay a reward based on your improvement from your baseline task performance. 

As of 2/20/24, the 'm' key no longer will be used to add in the score manually for the do better task, instead, there will be a section on the experiment prompt that is below the id that says baseline_score, that is where the baseline_score will be added. Before, the score would be entered manually after setting up the task, so hopefully this makes in-person facilitation easier. See below for an example of entering a score of 550 for participant 001:

<img src="https://github.com/alex-t-reed/MeMoS-Study/blob/main/MeMoS_Do_Better_Prompt.png" width="300" alt="Image of Code Routine">

## How to Use

You must download [PsychoPy](https://www.psychopy.org/download.html) and use version 2021.2.3. Code blocks can be altered using Python or JavaScript.

Each `.psyexp` experiment file in each folder contains a code block that allows you to switch between actual and testing mode. In testing mode, you can debug the experiment without viewing all the stimuli. See the image below (each task has this code block):

<img src="https://github.com/alex-t-reed/MeMoS-Study/blob/main/Code_Routine.png" width="300" alt="Image of Code Routine">

There is a "Code" routine in each experiment that I have added a "mode" variable to that can be set to "actual" or "testing". Changing to a testing mode makes the experiment signficantly faster by reducing stimuli numbers and blocks. Why? To fix bugs and add in new features in a more timely manner.

Each experiment can be commenced with the green play button near the top of the experiment. Then you will be prompted to enter participant info such as ID and session, then hit OK and the experiment will begin. See below for example in the Baseline task:

<img src="https://github.com/alex-t-reed/MeMoS-Study/blob/main/MeMoS_Baseline_Taskbar.png" width="600" alt="Image of Baseline Taskbar">

## Video Compression

Due to GitHub's 100 MB limit, these videos have been heavily compressed using [FFmpeg](https://ffmpeg.org/) via the terminal as well as [FreeConvert](https://www.freeconvert.com/video-compressor/) for videos that were still over the 100 MB limit. Please see below for the before and after compression sizes for each video found in the */resources/videos/ folder of each experiment.
- Baseline Task video: 416.9 MB to 67.6 MB (FFmpeg and FreeConvert)
- Do Better Task video: 116.7 MB to 34.4 MB (FFmpeg)
- Memory Task video: 362.8 MB to 73.8 MB (FFmpeg and FreeConvert)
- Money Task video: 361.5 MB to 70.8 MB (FFmpeg and FreeConvert)

## Contributors

- [Alex Reed](https://www.linkedin.com/in/alextreed/): Research Assistant, Miller Memory Lab, UCSB, Senior Biopsychology Major (Developer of MeMoS Study code)
- [Sara Leslie](mailto:sara.leslie@psych.ucsb.edu): Original Task Developer & MeMoS Study Planner, Graduate Student in the Miller Memory Lab
- [Courtney Durdle](mailto:courtney.durdle@psych.ucsb.edu): MeMoS Study Planner, Graduate Student in the Miller Memory Lab

## Contact

For inquiries about the MeMoS Study or this repository, please contact Alex Reed at [alexreed.atr@gmail.com](mailto:alexreed.atr@gmail.com). You can also reach out to Sara Leslie at [sara.leslie@psych.ucsb.edu](mailto:sara.leslie@psych.ucsb.edu) and Courtney Durdle at [courtney.durdle@psych.ucsb.edu](mailto:courtney.durdle@psych.ucsb.edu).

For more information about the Miller Memory Lab, please visit [https://labs.psych.ucsb.edu/miller/michael/](https://labs.psych.ucsb.edu/miller/michael/).