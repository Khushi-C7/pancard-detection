# PAN Card Tampering Detection

This repository contains Python code for detecting tampering in PAN (Permanent Account Number) card images using image similarity and contour detection techniques.

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Dependencies](#dependencies)
* [Output](#output)

## Overview

This project compares two PAN card images (an original and a potentially tampered one) to identify differences. It utilizes the Structural Similarity Index (SSIM) to quantify the similarity between the images. Differences are highlighted using contour detection, visually indicating areas of potential tampering.

## Features

* **Image Similarity Comparison:** Calculates the SSIM between two PAN card images.
* **Tampering Detection:** Identifies and highlights areas of difference using contour detection.
* **Visual Output:** Displays the original and tampered images with detected differences outlined.
* **Difference and Threshold Visualization:** Shows the raw difference and thresholded difference images.
* **Image Resizing:** Resizes input images to a consistent size for comparison.

