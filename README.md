# ECE648-HW9
Performance of Image and Video Compression Techniques<br />
The purpose of this exercise is to compare the performance of popular image and video compression techniques using *VCDemo* package.


# Image Compression
Open the image *Lena256B*. Use this image and __set the bit-rate to 1__ for the entire exercise (except in situations where it is not possible).
1. Perform image compression using DPCM using all four prediction models. Which is the best prediction model?
1. Perform image compression using VQ using all the four *codebooks* with bits per vector set to 12. What is the coded bit-rate? Which is the best codebook? Explain why.
1. Perform image compression using subband coding (SBC) using all six decompositions, and a 16-tap filter. Use default values for other parameters. What is the effect of increasing the number of subbands on the performance?
1. Perform image compression using subband coding (SBC) using the second decomposition and default values for other parameters. What is the effect of increasing the number of filter taps from 2 to 32 on the performance?
1. Comare the performance of the following compression schemes:
  1. JPEG <br />Use standard Y quantization and adjust the quality to get a coded bit-rate of 1.
  1. JPEG2000 or JPG2 <br />Use default values.
  1. SPHIT (Set Partitioning in Hierarchical Trees)<br />Use target bit-rate of 1 and no smoothing.
  1. EZW (Embedded Zerotree Wavelet) <br />Use resolution levels 2, 4, and 6, with encoder bit-rate set to 1.
# Video Compression
Open the video sequence *Vectra21Frames* from VCDemo. Compress the video sequence using __MPEG2__ and __H.264__ compression using default parameters. What are the compression ratios obtained using these schemes? (Hint: look at the size of the original vs the compressed file)

# Write-Up
1. Do not include print outs of the compressed images. Perform subjective evaluation of compressed images by observing them on the computer screen.
1. Answers to all the questions in the Procedure part.
1. Table of *mse* and *PSNR* values for all the techniques and all the compressed images.
1. If you were to choose a compression scheme for still images that would yield the best performance for
a given bit rate, which one will it be.
