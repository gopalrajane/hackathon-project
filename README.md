Project Title

Offroad Autonomy Segmentation

Team Name

Tech Sorcerer

Team Members
Aditya Waje
Girish Unde
Gopal Rajane

Problem Statement

Autonomous vehicles work well on normal roads, but they fail in off-road areas like deserts and rough land.

These environments do not have clear paths or lanes. There are obstacles like rocks, bushes, and logs that are difficult to detect.

Current systems depend on real-world data, which is expensive and limited. They also fail to detect small but important obstacles, which can cause accidents.

Because of this, unmanned ground vehicles cannot safely move in off-road environments.

Solution

We built a system that helps vehicles understand off-road environments at a very detailed level.

The model looks at an image and identifies every part of the scene, such as rocks, grass, sky, and ground.

We used synthetic data instead of real-world data to train the model. This helps in creating many different scenarios without high cost.

Features
Identifies objects at pixel level
Works on desert and off-road environments
Fast prediction speed suitable for real-time use
High accuracy in detecting terrain types
Fully built and tested in Jupyter Notebook
Tech Stack

AI and Machine Learning
Python
YOLO segmentation model
OpenCV

Data Platform
Duality AI Falcon

Development
Jupyter Notebook

How It Works

First, synthetic images of desert environments are generated.

These images are labeled so that every pixel has a category.

The model is trained using this data.

After training, the model can take a new image and identify all parts of the scene.

This helps a vehicle detect obstacles and decide a safe path.
