# c2m2.github.io
Documentation site repo for Temple University's C2M2 Virtual Reality Computational Simulation Interface Project

## How to update the documentation using Doxygen
### Prerequisites
[Download](https://www.doxygen.nl/download.html) and install Doxygen.
[Download](https://graphviz.org/download/) and install GraphViz.
### Steps to produce documentation
**1.** Clone this repo onto your local machine.
**2.** Open Doxygen -> File -> Open -> c2m2.github.io/Doxyfile
**3.** Navigate to the "Wizard" tab.
**4.** Make sure that the working directory is set to "c2m2.github.io":

![Set current working directory to "c2m2.github.io" in Doxygen's Step 1](https://github.com/c2m2/c2m2.github.io/blob/master/media/working_directory.PNG)

**5.** Clone the [C2M2 virtual-reality project](https://github.com/c2m2/virtual-reality)
**6.** Set Doxygen's source code directory to "virtual-reality\Assets\Scripts\C2M2":

![Set source code directory to "virtual-reality\Assets\Scripts\C2M2"](https://github.com/c2m2/c2m2.github.io/blob/master/media/source_directory.PNG)

**7.** Set Doxygen's destination directory to c2m2.github.io:

![Set destination directory to "c2m2.github.io"](https://github.com/c2m2/c2m2.github.io/blob/master/media/destination_directory.PNG)

**8.** Find where GraphViz installed, then navigate to the "Expert" tab.
**9.** Navigate to Expert -> Dot and make sure that DOT_PATH is set to "Graphviz2.38\bin". The number might change depending on your version of GraphViz:

![Set DOT_PATH to "Graphviz2.38\bin](https://github.com/c2m2/c2m2.github.io/blob/master/media/DOT_PATH.PNG)

**10.** Navigate to the "Run" tab. Click "Run Doxygen" and let it run.
**11.** If no fatal errors occur, commit and push the changes to this repo.
