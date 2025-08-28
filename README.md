# Drowsiness Detection - Eye State Classification (Course Project)

This repository contains the implementation of a Convolutional Neural Network (CNN) that classifies eye state (open or closed) from images.

It was developed as part of a university course project, intended to serve as a subsystem within a larger driver drowsiness detection system.
The full system (out of scope for this project) would:

- Capture frames of a driver’s face in real-time

- Use this model to classify each frame as open or closed

- Track the rate of eye closure over time

- Compare it to the normal blinking rate

- Raise a drowsiness alert if the closure rate increases beyond a safe threshold

## Overview

This repo does not implement the drowsiness logic itself.
Instead, it focuses on eye state classification.

- Task: Binary classification (eye open vs. closed)

- Purpose: Support higher-level drowsiness detection by providing reliable eye state predictions per frame

- Dataset: Folder-structured image dataset (open/, closed/) split into training & validation sets

- Model: Lightweight CNN trained on RGB eye images resized to 640×480
