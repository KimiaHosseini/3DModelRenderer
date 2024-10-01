# 3DModelRenderer

## Overview
This is a Python project developed for an applied linear algebra course at AmirKabir University of Technology. The primary focus of this project is to render a 3D cube by transforming its geometric representation into a 2D visual format. This project serves as an introduction to computer graphics, illustrating fundamental concepts of rendering 3D objects using mathematical transformations.

## Features

    3D Model Representation: Define and manipulate 3D models using vertices, positions, scales, and rotations.
    Geometric Transformations: Implement translation, rotation, and scaling transformations to modify 3D models.
    Visualization: Render and visualize the models and their transformations using Matplotlib.

## Introduction to Rendering

Rendering is the process of converting a 3D model, represented as a list of points in three-dimensional space, into a two-dimensional image that can be displayed. In this project, we explore some of the steps involved in this process. For consistency, we use a left-handed coordinate system with the Y-axis oriented upwards.

To achieve rendering, we need to define three different spaces:

    Object Space: This is the local space of the object, defined by its vertices.
    World Space: This space defines the object's position, orientation, and scale in the world.
    Screen Space: This is the 2D representation of the world space that can be displayed on the screen.

### Model Representation

The Model class represents a 3D object. It holds the vertices of the object, its position, scale, and rotation:

### Geometric Transformations

The project implements several geometric transformations, including:

    Translation: Moving the object to a new position.
    Rotation: Rotating the object around its axes.
    Scaling: Changing the size of the object.

These transformations are represented as matrices that are applied to the object's vertices.

### Visualization

The final step is to visualize the transformed model. The raster function takes care of rendering the triangles that form the model on a 2D screen.
