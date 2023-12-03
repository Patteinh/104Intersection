# 104Intersection 🔮

Welcome to **104intersection**.

This project explores the intersections of light rays with various 3D surfaces, a key concept in the creation of synthesis images, such as those used in ray tracing.

## Language and Tools 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

- **Language:** Python
- **Binary Name:** 104intersection

## Project Overview 🔎

The aim of this project is to compute potential intersection points between light rays and certain 3D surfaces, specifically spheres, cylinders, and cones. This involves formulating a 3D equation of the surface and a quadratic equation to find the intersection points.

### Usage

`./104intersection opt xp yp zp xv yv zv p`

#### DESCRIPTION
- `opt`: Surface option (1 for a sphere, 2 for a cylinder, 3 for a cone).
- `(xp, yp, zp)`: Coordinates of a point the light ray passes through.
- `(xv, yv, zv)`: Coordinates of a vector parallel to the light ray.
- `p`: Parameter (radius of the sphere/cylinder, angle for the cone).

### Examples

#### Example 1

`Input: ./104intersection 1 0 0 2 1 1 0 1`<br>
`Output: Sphere of radius 1, no intersection point.`<br>

#### Example 2

`Input: ./104intersection 2 0 0 2 1 1 0 1`<br>
`Output: Cylinder of radius 1, 2 intersection points.`<br>


*Note: Precision in calculations is crucial for accurate intersection point determination.*

## Installation and Usage 💾

1. Clone the repository.
2. Compile the program using the provided Makefile.
3. Run the program: `./104intersection opt xp yp zp xv yv zv p`.
4. For detailed guidelines, refer to `104intersection.pdf`.

## License ⚖️

This project is released under the MIT License. See `LICENSE` for more details.

