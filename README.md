### Invisibility Cloak
<hr>

* An invisibility cloak is a magical garment which rendered whomever or whatever it covered invisible.
* This effect can be produced using computer vision.
* In this program blue coloured objects used to produce invisibility cloak effect.

<hr>
<p align="center">
<a href=" ">
    <img src="example.png" alt="example1"/>
</a>
</p>
<hr>
### Pre-requisites
<hr>

1. Python (version 3.0.0 or above)
2. OpenCV
```
To install OpenCV, run following command in terminal:
pip install opencv-python
```
3. Numpy
```
To install Numpy, run following command in terminal:
pip install numpy
```
<hr>

### Workflow

<hr>

1. Import the necessary libraries.
2. Use webcam to capture the live feed of the person and the background.
3. Capture the initial background.
4. Set the values for the Cloak i.e. the cloth selected.
5. Making 2 masks and applying them to the frame.
6. Combine the masks and show them scimultaneously.
7. Display the final output.
