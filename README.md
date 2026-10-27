# Engineering Mathematics: Fourier Series and the 2-D DFT

My computer assignment for Engineering Mathematics at the University of Tehran, Spring 2025. The statement (in Persian) is `CA.pdf` and the solution is `EngMath_CA.ipynb`.

The notebook has two parts:

1. **Fourier series in 1-D.** Computes the discrete Fourier coefficients of a square wave, checks the first ones against the values worked out by hand, and rebuilds the signal from 2, 5 and 50 terms to show how the approximation improves.
2. **2-D DFT on images.** A 2-D discrete Fourier transform written directly in NumPy (without `np.fft`), applied to a 64×64 grayscale image and then to each channel of a colour image. The images are compressed by keeping only a fraction of the coefficients, and the reconstructions are compared for several fractions.

## Running

Open the notebook in Jupyter. It needs NumPy, Matplotlib and OpenCV, and reads the test image `download.jpg` from the same folder.
