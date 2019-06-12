# Final Project

Megan Visaya, mvisaya@ucsd.edu

## Abstract Proposal

In the spirit of this class, of my identity as an engineer, and of my faith, I wanted to highlight the relationship between the 
aesthetics of patterns found in nature using imagery that is often studied by biologists, astronomers, physicists, etc. 
I hope to create outputs that reflect the consistency, stability, and beauty of these structures, and start a conversation on how they 
can be used as a confirmation of the mastery of a Creator or evidence against Their existence. I plan to use a visual GAN to
produce images that emphasize these patterns by training a discriminator with alike images that depict different objects (e.g., cells 
vs. supernovas, neural pathways vs. superclusters, honeycombs vs. turtle shells), and will display my results digitally for our final 
presentations.

EDIT: Clarification on final results, in contrast with this abstract proposal, can be found in the report include in the repository.

## Project Report

Included as ECE188_FinalProject_Report.pdf

## Model/Data

- Included are the scripts for downloading data using the Google Image scraper and for running the GAN.
- Please download the dataset here (400~ MB): https://drive.google.com/file/d/1ccJBDSJXagpVSkpvbKEyB5NzlrAROBLJ/view?usp=sharing 

## Code

For generating training data:
- Python: img_downloads.ipynb
To run the GAN:
- Python: FinalProjectGAN.py

## Results

In the Results folder are examples that I chose to print for my final presentation. 

## Technical Notes

PIL and the Google Image Scraper (see references) can be pip installed and must be imported for script to run.

## References

https://github.com/hardikvasa/google-images-download : Google Image scraper
https://github.com/t0nberryking/DCGAN256.git : Base GAN to produce 256x256 images
