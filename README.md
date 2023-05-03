![Image goes here](/mdimage.png)
# Jonathan's OCR
This project shows a major application of neural networks in Optical Character Recognition (OCR) programs. The primary purpose of an OCR is to take an image of text as input, typed or handwritten, and transcribe that into editable text, which in this case uses a neural network.

## Intro
While document scanning for computers has existed since the 1950's, they always yield images rather than text. Until recently, to edit documents their content would have to be manually transcribed into a text editor to have full reign over it. Entire jobs are dedicated to data entry for this purpose. An optical character recognition program can do the same thing, 'reading' the document line-by-line and giving a character-by-character output of the text.

## How does this work?
After an image is given to the program, it takes several steps to process it before the neural network is even brought out. 
1. An algorithm tries to detect and isolate individual lines of text and separates them into images
2. The lines are resized to fit the neural network's size
3. Individual characters are isolated through another algorithm made to detect centered letters
4. Finally, the isolated characters are sent through the neural network in order to get its best predicitons at what letters they are

## Potential Applications
Besides data entry, optical character recognition has potential uses in a few other areas of society. For example, if combined with text-to-speech software, it can be used to assist those with visual impairments with reading, or to more easily read and record license plates of cars for law enforcement purposes.

## Links
### Slides
[Optical Character Recognition Presentation](https://docs.google.com/presentation/d/1dIJkuKfhJOnO3VB-USG3ehLedF0QdfkLc2Te0dXiRb0/edit?usp=sharing)
### YouTube
[How to use this yourself]()
### Notebooks (run in order)
[Data Generator](https://colab.research.google.com/drive/1wfdl94u4X1igQXAmDT3_938Z9CkuV5az?usp=sharing)

[Neural Network Trainer](https://colab.research.google.com/drive/1vE2kGFQ-nWHHI8ZM71D01czNPJu9eGK0?usp=sharing)

[OCR Implementation](https://colab.research.google.com/drive/1C4L0XzkFBwRljJ8TlpsS-3q34N5cz-bB?usp=sharing)
### Supplemental Files
[Fonts (for Data Generator)](https://drive.google.com/drive/folders/1Bs7ARDcBtNf9CIhqb6UO_tECjTPBSIJA?usp=sharing)

[3-line test image (for OCR Implementation)](https://drive.google.com/file/d/1iiKrQHQDww1vL3D9aYItFXc3pom93Ymy/view?usp=share_link)

[4-line test image (for OCR Implementation)](https://drive.google.com/file/d/1PFLTumb_rULhX4h8d58G4LJWFS5_wcBa/view?usp=sharing)
