# Steganography Implementation Project
![STEGANOGRAPHY](https://github.com/rajeev-cyber/Implementation_of_Stegnography/assets/136923593/70950259-49d9-453d-b3fa-61b74e4718bc)

## Project Overview

The Implementation of Steganography project is a collaborative effort by three members to create an open-source website that supports various types of steganography, including image, audio, text, and video.

## Table of Contents

- [Introduction](#introduction)
- [Technologies to be Used](#technologies-to-be-Used)
- [Features](#features)
- [Supported Steganography Types](#supported-steganography-types)
- [Usage](#usage)
- [License](#license)

## Introduction

Steganography is the practice of concealing information within other non-secret text or data. This project provides a user-friendly web interface to experiment with different steganography methods, including image, text, video, and audio steganography.

## Technologies to be Used:

**Programming Languages:**  Python, C Languages
**Libraries:** Steno, pipenv, opencv
**Development Tools:** Visual Studio Code, Notepad,Python IDLE
**Version Control:** Git
**Database (Optional):** MySQL

## Features

- User-friendly web interface
- Support for multiple steganography techniques
- Accessibility to image, text, video, and audio steganography
- Open-source and customizable

## Supported Steganography Types

1. **Image Steganography**: Hide text or other images within an image.
2. **Text Steganography**: Conceal text within other text, such as using whitespace or special characters.
3. **Video Steganography**: Embed information within video files without compromising visual and auditory quality.
4. **Audio Steganography**: Hide data within audio files without perceptible changes to the audio.

## Steps for Using Image Steganography

Here are the typical steps for using image steganography:
1. Select a cover image: Choose an innocuous-looking image file such as a photo to hide secret data within. Using a complex image with more data (e.g. photo vs. simple graphic) makes detection harder.
2. Convert secret message to binary: Transform the text, audio, or video file to a series of 0s and 1s according to its ASCII/binary representation.
3. Embed data in cover image: Use a steganography tool/library and algorithm like LSB insertion to modify the least significant bits of pixels in the cover image according to the binary secret data.
4. Save the resulting stego-image: This is the cover image with the secret message embedded and indistinguishable to human eyes or basic analysis.
5. Extract hidden data: Open the stego-image in a tool that can detect and extract the hidden binary data using the same algorithm.
6. Convert extracted data to original form: Transform the extracted binary data back to the original text, image, audio or video file format.

## Flowchart

![WhatsApp Image 2023-11-04 at 00 02 06](https://github.com/rajeev-cyber/Implementation_of_Stegnography/assets/136923593/36fb8059-ba83-4f15-be79-bfa255f906e7)

## Usage

Visit the [website link] to access the Steganography Implementation Project.<br>
Choose the steganography type you want to experiment with.

Follow the on-screen instructions to hide or extract information.


## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries, please contact:

- [Rajeev](https://github.com/rajeev-cyber)
- [Abhinav Rajpati](https://github.com/Surventurer)
- [Vibhas Dutta](https://github.com/vibhasdutta)

## Badges

[![Build Status](badge-url)](link-to-build-status)
[![License](badge-url)](link-to-license)
