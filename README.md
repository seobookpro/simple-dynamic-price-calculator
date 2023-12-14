# Dynamic Price Calculator Beta
Dynamic Price Element Documentation
# Dynamic Price Element Documentation

The dynamic price element is designed to provide a flexible pricing structure with the ability to customize prices based on user selections. The element consists of four fixed prices that serve as a base for calculations.

## Fixed Prices

The following are the initial fixed prices:

1. **$0,00**
2. **$799,00**
3. **$1599,00**
4. **$2999,00**

## Usage

To utilize the dynamic price element, follow these steps:

1. Include the dynamic price element component in your application.

2. Create an unordered list (`ul`) containing checkboxes for various features or options.

    ```html
    <ul>
        <li><input type="checkbox" id="brandAudit"> Brand Audit</li>
        <!-- Add more checkboxes for other features -->
    </ul>
    ```

3. When a checkbox is checked, the associated value will be added to all four fixed prices.

    For example:

    - If the "Brand Audit" checkbox is checked, an additional **$29.99** will be added to each of the fixed prices.

    - Customize the checkboxes and values based on your specific requirements.

## Example

```html
<!-- Include the dynamic price element component in your HTML -->
<div id="dynamicPriceElement"></div>

<!-- Create a list of checkboxes for features -->
<ul>
    <li><input type="checkbox" id="brandAudit"> Brand Audit</li>
    <li><input type="checkbox" id="feature2"> Feature 2</li>
    <!-- Add more checkboxes for other features -->
</ul>

 ```


# A brief description of Dynamic Price Calculator Beta project.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

Explain what your project is about and what problem it solves. Provide a high-level overview of its features and functionality.

## Features

List the key features of your project. For example:

- Feature 1: Description
- Feature 2: Description
- ...

## Getting Started

Provide instructions on how to set up and run your project locally.

### Prerequisites

List any software, tools, or dependencies that users need to install before running your project.

### Installation

Step-by-step instructions on how to install and configure your project.

