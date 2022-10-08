# Python Fingerprint Recognition

Fingerprint recognition with SKimage and OpenCV

Requirements:
* NumPy
* SKimage
* OpenCV2


Works by extracting minutiae points using harris corner detection.

Uses SIFT (ORB) go get formal descriptors around the keypoints with brute-force hamming distance and then analyzes the returned matches using thresholds.

## Usage

1. Place 2 fingerprint images that you want to compare inside the database folder
2. Pass the names of the images as arguments in the console

## Credits
* Forked from [kjanko/python-fingerprint-recognition](https://github.com/kjanko/python-fingerprint-recognition).
* Using library [Utkarsh-Deshmukh/Fingerprint-Enhancement-Python](https://github.com/Utkarsh-Deshmukh/Fingerprint-Enhancement-Python).
