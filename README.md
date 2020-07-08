# Histogram-Equalization-project
this program uses Python 3 library and Numpy to perform Histogram Equalization 
the code first opens image followed by the given path,
Process it with Equation:
img = np.array(image)
L = np.max(img) +1
there are Four Part to perform all this project:
Part 1:plot image Histogram
Part 2: plot image cummulative Frequencies
Part 3: Image Histogram Equalization
Part 4: perform image Equalization
the code first opens image followed by the given path.

#Part 1: plot image Histogram

plot the image histogram; first checks the error if any and then go for thy dimensions and intensity Frequency and Calculate it with Equation:
r = img[i, j]
hist[r] += 1

#Part 2: plot image cummulative Frequencies
Next it plots image cummulative frequecy , checks error, go for dimensions and intensity Frequency array .
in this part it will detemines the probability of mass function and then do the cummulative Frequency Calculation

#Part 3: Image Histogram Equalization
similary in Histogram equalization first checks error, go for image dimensions and multiply them scale the cummulative frequency with equation scaledFreq = cumFreq * (L - 1) and Equalize them.

#Part 4: perform image Equalization
Last but not least, image equalization is done and comparison is done among original histogram original CF, Equalized histogram and Equalized CF and their respective graphs are then plotted 
