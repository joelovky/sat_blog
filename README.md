# Separating Axis Test Code for SAT Blog 🌟

![GitHub release](https://img.shields.io/badge/Release-v1.0.0-blue.svg)  
[Download Latest Release](https://github.com/joelovky/sat_blog/releases)

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [How to Use](#how-to-use)
- [Features](#features)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This repository contains the code related to the blog post on the Separating Axis Test (SAT). The SAT is a fundamental algorithm used in collision detection for 2D and 3D shapes. It helps determine if two convex shapes overlap by projecting them onto potential separating axes. This repository aims to provide a practical implementation of the SAT, along with explanations and examples.

## Getting Started

To get started with the code, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/joelovky/sat_blog.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd sat_blog
   ```

3. **Download the latest release**: Visit the [Releases section](https://github.com/joelovky/sat_blog/releases) to download the necessary files. You will need to execute the downloaded file to run the program.

## How to Use

After setting up the project, you can use the SAT implementation in your own projects. Here’s a brief guide on how to implement the code:

1. **Import the SAT module**:

   ```python
   from sat import SAT
   ```

2. **Create shapes**: Define the shapes you want to test for collisions.

   ```python
   shape1 = SAT.Rectangle(x=0, y=0, width=50, height=50)
   shape2 = SAT.Circle(x=25, y=25, radius=20)
   ```

3. **Check for collisions**:

   ```python
   if SAT.collides(shape1, shape2):
       print("Shapes collide!")
   else:
       print("Shapes do not collide.")
   ```

## Features

- **Simple API**: Easy to integrate into existing projects.
- **Support for multiple shapes**: Includes rectangles, circles, and polygons.
- **Efficient performance**: Optimized for real-time applications.
- **Clear documentation**: Each function and class is well-documented.

## Code Structure

The code is organized into several key files and directories:

- **/src**: Contains the main implementation of the SAT algorithm.
- **/tests**: Includes unit tests to ensure the functionality of the code.
- **/examples**: Provides example usage of the SAT implementation.
- **README.md**: This file, containing instructions and information about the repository.

### Example Code Structure

```
sat_blog/
│
├── src/
│   ├── sat.py
│   └── shapes.py
│
├── tests/
│   ├── test_sat.py
│   └── test_shapes.py
│
├── examples/
│   ├── example1.py
│   └── example2.py
│
└── README.md
```

## Contributing

We welcome contributions to improve this repository. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please ensure your code follows the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to the repository owner:

- **Joel Ovky**  
- GitHub: [joelovky](https://github.com/joelovky)  
- Email: joelovky@example.com  

Feel free to visit the [Releases section](https://github.com/joelovky/sat_blog/releases) for the latest updates and downloads.