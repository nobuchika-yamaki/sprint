README – Supplementary Code S1
Overview

This repository contains Supplementary Code S1, which estimates sprint split times by detecting virtual line-crossing events from a single lateral video using MediaPipe Pose. The code computes reproducible timing estimates based on image-space virtual markers and is intended for research and methodological validation purposes.

What this code does

Extracts 2D human pose landmarks from video frames using MediaPipe Pose

Tracks the horizontal positions of selected anatomical landmarks (lead ankle and hip center)

Detects when these landmarks cross predefined virtual vertical lines in the image
