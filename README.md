# Sorting-Algorithms-Blender
A Sorting Algorithms Visualizer built to help users understand how different sorting algorithms work through real-time visual animations. This tool provides an interactive and educational experience for students, developers, and anyone interested in learning sorting techniques.
Sorting-Algorithms-Visualizer

3D visualization of sorting algorithms using Blender and Python API

📑 Table of Contents
Overview

Project Description

Features

Installation & Usage

Visualization Types

Implemented Algorithms

Big O Complexity

Future Enhancements

License

🔹 Overview
This project provides animated visualizations of sorting algorithms inside Blender. Using Python scripts, it creates 3D objects and dynamically animates their movements to represent how sorting works step-by-step.

📝 Project Description
Generates 3D objects in Blender

Inserts keyframes dynamically for each swap and comparison

Offers multiple visualization styles (rotation, color, scale)

Helps learners understand algorithm behavior intuitively

⚡ Features
✅ Visualizes 7+ sorting algorithms
✅ 3D animations with Blender Python API
✅ Displays element comparisons and access counts
✅ Multiple visualization styles (color, rotation, scale, 3D cube)
✅ Lightweight and beginner-friendly

🛠️ Installation & Usage
Install and launch Blender

Open any .py file from the repository in Blender’s Text Editor

Click Run Script

Play the animation timeline to see the sorting in action

🎨 Visualization Types
Mode	Color Representation	Index Representation	Extra Features
circle_view	HSV material coloring	Object rotation	Circular hue visualization
color_view	Gradient-based colors	Plane positioning	Custom color gradients
scale_view	Scaling effect	Cuboid positioning	Shows array access and comparisons
combined_3D	Mixed color coding	3D cube arrangement	Multiple arrays visualized together

📋 Implemented Sorting Algorithms
Bubble Sort

Insertion Sort

Selection Sort

Heap Sort

Shell Sort

Merge Sort

Quick Sort

📊 Big O Complexity
Algorithm	Best Case	Average Case	Worst Case	Space Complexity
Quick Sort	O(n log n)	O(n log n)	O(n²)	O(log n)
Merge Sort	O(n log n)	O(n log n)	O(n log n)	O(n)
Heap Sort	O(n log n)	O(n log n)	O(n log n)	O(1)
Bubble Sort	O(n)	O(n²)	O(n²)	O(1)
Insertion Sort	O(n)	O(n²)	O(n²)	O(1)
Selection Sort	O(n²)	O(n²)	O(n²)	O(1)
Shell Sort	O(n log n)	O(n(log n)²)	O(n(log n)²)	O(1)

🚀 Future Enhancements
Add sound effects for comparisons and swaps

Include more algorithms (Radix, Bucket, Counting)

Dynamic camera setup for large datasets

Create custom UI panel for parameter selection

Optimize merge sort visualization

📜 License
Distributed under the GPL-3.0 License.
