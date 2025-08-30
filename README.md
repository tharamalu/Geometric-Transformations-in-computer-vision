# Geometric-Transformations-in-computer-vision

1. Euclidean Transformations

Operations: Translation + Rotation (sometimes reflection).

Property: Distances and angles stay the same → figure just moves or turns.

Representation: Rotation matrix combined with a shift vector.

Example: A triangle rotated around a point and moved to a new position.



---

2. Similarity Transformations

Operations: Translation + Rotation + Uniform scaling.

Property: Shape is unchanged, but the size may increase or decrease.

Special Note: It is an affine transform with equal scale factor in all directions.

Example: A circle shifted, rotated, and resized equally in x and y directions.



---

3. Affine Transformations

Operations: Translation, Rotation, Scaling (uniform or non-uniform), Shearing.

Property: Keeps straight and parallel lines intact, but lengths/angles may distort.

Representation: Described by a 2×3 affine transformation matrix.

Example: A square turned into a parallelogram by skewing.



---

4. Projective Transformations (Homography)

Operations: Translation, Rotation, Scaling, Shear, Perspective distortion.

Property: Straightness of lines is preserved, but parallel lines may intersect at a vanishing point.

Representation: Expressed using a 3×3 homography matrix in homogeneous coordinates.

Example: A square appearing like a trapezoid in a perspective view (like in a photo).
