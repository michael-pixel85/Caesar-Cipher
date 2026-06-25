# Caesar Cipher Tool
A lightweight, fast Python script to encrypt and decrypt text using the classic Caesar Cipher algorithm.


<img width="927" height="619" alt="Screenshot 2026-06-24 200400" src="https://github.com/user-attachments/assets/1d412b9d-b4de-43e7-853b-a79b3fc86254" />

## If you'd like to try it:
I've attached a public Google Colab notebook that runs the script: https://colab.research.google.com/drive/1uRbsP4nsbZ5X5DmZHSfRITGMux8AMVRQ

## How it works
Instead of changing each individual letter one by one, the code creates an alphabet map to swap all the original letters at the same time, leaving all non-letter untouched. It takes the first (shift) numbers and places them at the back of the alphabet. Then the code uses Python's translate tool to replace the given characters with those from the map, revealing the encrypted or decrypted text. 
