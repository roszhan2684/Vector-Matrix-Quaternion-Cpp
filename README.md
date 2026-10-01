# 3D Vector, Matrix & Quaternion Library (C++)

Header-only, templated 3D math types written for CSUF's computer graphics coursework:

- `vector3dT.h` — `vector3d<T>`: arithmetic, dot/cross products, norms, angles
- `matrix3dT.h` — `matrix3d<T>`: 3×3 matrix algebra, determinants, inverses, matrix–vector products
- `quaternion_T.h` — `quaternion<T>`: Hamilton products, conjugate, inverse, norm, and 3D rotation

Each type has a built-in `run_tests()` with assertions. `main-1.cpp` is the test driver.

```sh
clang++ -std=c++17 main-1.cpp -o vector_matrix && ./vector_matrix
```
