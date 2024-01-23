# Digital-Spirit-Level

# This is a course at Chalmers Univeristy within Digital Constructtion (EDA234) that is performed in groups 3-4 students. 

# Technical Report: EDA234 Hardware Analysis

This repository contains the technical report for the hardware analysis conducted in the EDA234 course, focusing on the development and functionality of a digital spirit level. The report, titled "Technical Report.pdf," provides a comprehensive examination of the hardware components tested, methods used for analysis, and the findings of the study.

## Abstract

The technical report presents the results of a detailed hardware analysis, emphasizing the design, implementation, and functionality of a digital spirit level. The study aims to evaluate the performance, reliability, and efficiency of the hardware under various conditions.

## Digital Spirit Level Functionality

### Overview

The digital spirit level is designed to measure the angle of slope in two axes: x (roll) and y (pitch). This is achieved by utilizing an accelerometer that senses gravitational pull in different dimensions. The data from the accelerometer is communicated to the FPGA via an SPI interface.

### Data Processing and Display

Once the data is received, the FPGA processes it to derive the angle from the gravitational pull. It then encodes these angles into binary encoded decimals suitable for display on both a 7-segment display and an LCD. A switch is provided to select between measuring the angle of pitch or roll, and there is also a reset button for resetting the system.

### Angle Measurement and Display Characteristics

- The angles are displayed without a sign, meaning both positive and negative angles are shown as positive values.
- The maximum measurable angle is 180 degrees. The display counts down towards 0 again beyond this angle.
- The display always shows the angle in three digits.

### Data Transmission

In addition to display on the 7-segment and LCD displays, the angle is also transmitted to a connected PC via a UART transmitter.

## Contents of the Report

The report includes the following sections:

- Introduction to the hardware system
- Objectives of the analysis
- Methodology employed for testing and evaluation
- Results and Discussion
- Conclusions drawn from the analysis
- Recommendations for future studies and development

## Usage

To view the report, download the "Technical Report.pdf" file from this repository and open it with a PDF reader.

## Contributing

This report is the result of a collaborative effort. Contributions to the analysis were made by Theodor Ahlgren, Baseer Qayoumi and Mahdi Haidari. 

Thank you for your interest.
