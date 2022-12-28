## py4Nav
*Navigation code in Python*

### Intro
- This repo is for my personal study of some navigation concepts
- Jupyter Notebooks have some markdown cells which contain explanations in LaTeX which are sometimes rendered incorrectly by GitHub. So, it is sometimes better to study locally
- All code and all examples are prone to all kinds of errors
- Any corrections, suggestions, improvements, etc. are welcome

### Contents
- [/topics/trajectory/trajectory.ipynb](https://github.com/serhatsoyer/py4Nav/blob/main/topics/trajectory/trajectory.ipynb)
    - Draw 2D or 3D trajectories
    - Some [*matplotlib*](https://matplotlib.org) settings for publication
- [/topics/scipy_spatial_transform/rotation.ipynb](https://github.com/serhatsoyer/py4Nav/blob/main/topics/scipy_spatial_transform/rotation.ipynb) using [*scipy.spatial.transform.Rotation*](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.transform.Rotation.html)
    - Random rotation generation
    - Chain of rotations
    - Rotate vectors
    - Conversion among *quat*, *matrix*, *rotvec*, *euler* representations of rotations
    - Estimate the rotation between vectors using *align_vectors*
    - Magnitude of a rotation
- [/topics/scipy_spatial_transform/slerp.ipynb](https://github.com/serhatsoyer/py4Nav/blob/main/topics/scipy_spatial_transform/slerp.ipynb) using [*scipy.spatial.transform.Slerp*](https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.transform.Slerp.html)
    - Interpolation and/or resampling of rotations
- [/topics/sensor_characterization/allan.ipynb](https://github.com/serhatsoyer/py4Nav/blob/main/topics/sensor_characterization/allan.ipynb) using [*allantools*](https://pypi.org/project/AllanTools/)
    - Read real sensor data from an iPhone7 using [*pandas*](https://pandas.pydata.org)
    - Plot gyro and accelerometer allan deviation curves

### To Do List
- Compare the results with the indicated values from datasheets for [/topics/sensor_characterization/allan.ipynb](https://github.com/serhatsoyer/py4Nav/blob/main/topics/sensor_characterization/allan.ipynb)
    - Read ARW, VRW, and bias instability values from the plots if possible
    - Try to find the iPhone7 or a similar smartphone's IMU specs
    - Study ARW and VRW units
    - Convert the units correctly
- Study and demonstrate KF basics. Find a popular and stable library if any exists. Implement yourself otherwise
- Study and demonstrate extended KF basics
- Study and demonstrate unscented KF basics

### My Other Study Repos
- [py4DSP: DSP code on Python](https://github.com/serhatsoyer/py4DSP)
- [py4ML: ML code on Python](https://github.com/serhatsoyer/py4ML)
- [py4Me: Daily code on Python](https://github.com/serhatsoyer/py4Me)

Written by [*serhatsoyer*](https://github.com/serhatsoyer)