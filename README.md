# Bonescan-Enhancer

An application for enhancing the raw bone-scans via the usage of *Parallel Computing* and *Image Processing principles*, on order to facilitate convenient and efficient diagnosis.

<img src="./screenshots/Output.png" alt="Application Output" />

---

## Performance Comparison

The following are the screenshots for the serial and parallel implementations of the application in consideration, which clearly show that the parallel implementation out-performs the serail code, with a *speed-up factor* of about **1.4**.

<img src="./screenshots/Serial.png" alt="Application Output" />
<img src="./screenshots/Parallel.png" alt="Application Output" />

---

## Step-by-Step Output analysis

1. Original Scan

    <img src="./screenshots/1.png" alt="Application Output" />

1. Action of the Laplacian Operator 

    <img src="./screenshots/2.png" alt="Application Output" />

1. Action of the Sobel Operator 

    <img src="./screenshots/3.jpg" alt="Application Output" />

1. Application of a 5&times;5 Smoothening filter on Step-3's Output

    <img src="./screenshots/4.jpg" alt="Application Output" />

1. Obtained Image Mask 

    <img src="./screenshots/5.png" alt="Application Output" />

1. Rendering of Enhanced Scan 

    <img src="./screenshots/6.png" alt="Application Output" />

1. Action of the Power-Law Transform 

    <img src="./screenshots/7.png" alt="Application Output" />