# Underwater Image Enhancement

Welcome to the Underwater Image Enhancement project! This repository contains code and resources for enhancing the quality of underwater images. Underwater images often suffer from issues such as color distortion, low contrast, and blurriness due to the absorption and scattering of light in water. This project aims to address these challenges and improve the visual quality of underwater images.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Underwater Image Enhancement is crucial for various applications such as marine biology, underwater robotics, and underwater photography. This project implements several techniques to enhance underwater images, making them clearer and more visually appealing.

## Features

- Color correction to address color distortions.
- Contrast enhancement to improve visibility.
- Dehazing to reduce blurriness caused by water particles.
- Noise reduction to remove unwanted artifacts.
- Support for multiple image formats.

## Installation

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### Steps

1. Clone the repository:
    ```bash
   https://github.com/Abhish-akp/UnderWater-Image-Enhancement-.git
    cd underwater-image-enhancement
    ```
## Usage

### Command Line Interface

You can use the command line interface to enhance underwater images. Run the following command to see the available options:

```bash
Underwater_Image_Enhancement(Project).ipynb --help
```
### Script

You can also use the provided Python script in your own projects. Here is an example:

```python
from enhancement import enhance_image

input_image = "path/to/your/image.jpg"
output_image = "path/to/save/enhanced_image.jpg"

enhance_image(input_image, output_image)
```

## Contributing

We welcome contributions to the Underwater Image Enhancement project! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.
---

Feel free to customize this README file according to your project's specific requirements and details.
