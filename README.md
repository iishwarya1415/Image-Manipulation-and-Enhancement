# GRIME: Graphical Image Manipulation and Enhancement

This project is part of the **Master’s in Computer Science** program, specifically from the **Programming Design Paradigm (PDP)** course. The goal of the project is to build an image manipulation and enhancement tool that allows users to perform various operations on images through a graphical user interface (GUI) or command-line interface (CLI).

## Overview

**GRIME** follows the **Model-View-Controller (MVC)** architecture and offers a variety of image manipulation operations like resizing, compression, color manipulation, and many others. Users can load images, apply different effects, and save the results. The application can be used both via a GUI or a command-line interface, with the flexibility to execute a series of operations using a script.

## Features

### Exposed in both UI and Command-Line Interface:
- Load and save images
- Apply blur, sharpen, sepia, and color-correction
- Extract individual red, green, blue, luma, and value components
- Resize image (downscaling)
- Compress image
- Histogram generation
- Adjust image levels

### Exposed only in UI:
- Resize Image (Image Downscaling) feature available via GUI for manual input.

### Exposed only in Command Line:
- Intensity component extraction
- RGB split and combine operations
- Brighten (positive or negative value to modify brightness)
- Split view feature for various operations like blur, sharpen, etc.

## How to Run

### Running via IntelliJ or an IDE:
1. Open **Main.java**.
2. Run the application, and the **Graphical User Interface (GUI)** will open.
3. Load an image by selecting the "Load" button.
4. Manipulate the image by selecting available operations.
5. Save the final image after processing.

### Running via JAR:
To run using the JAR file, you can use any of the following commands:

#### 1. To open the GUI:
```bash
java -jar Program.jar
