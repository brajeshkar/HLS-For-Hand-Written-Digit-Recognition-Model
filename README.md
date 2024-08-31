# Handwritten Digit Recognition Model Optimization

This repository contains files and scripts for optimizing an existing Handwritten Digit Recognition model by converting it to C and optimizing it using High-Level Synthesis (HLS) techniques.

## Files in this Repository

- **my_model.h5**: The pre-trained Handwritten Digit Recognition model on MNIST Dataset in HDF5 format.
- **final1.c**: The main C code generated from the original model using keras2c.
- **final_test_suite.c**: A test suite for the Vivado HLS test bench, designed to validate the performance and accuracy of the optimized model.

## Overview

This project focuses on optimizing a pre-trained Handwritten Digit Recognition model to improve performance on hardware platforms. The optimization process involves:

1. **Model Conversion**: Converting the original Keras model (`my_model.h5`) into C code using the keras2c tool.
2. **Code Optimization**: Enhancing the generated C code (`final1.c`) using High-Level Synthesis (HLS) pragma operations and other optimization techniques to improve execution speed and efficiency.
3. **Testing and Validation**: Utilizing `final_test_suite.c` to test and validate the optimized code in Vivado HLS, ensuring functionality and performance improvements.

## Usage

### Prerequisites

- **Keras2C**: A tool to convert Keras models to C. [link](https://github.com/PlasmaControl/keras2c)
- **Vivado HLS**: A software tool for C-based design and verification.

### Steps to Run the Code
1. Open Vivado HLS and Create a New Project. 
2. Put this c files in the project
3. Run the test bench.