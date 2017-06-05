# Projects
This page gives an overview to projects that Peter Lee has contributed to.

1. [WFMO Program Finder](#wfmo)
2. [Snakes and Routers](#snakes)
3. [Cityscape Procedural Generation](#city)
4. [Pedestrian Traffic Simulator](#pedestrian)

<a name="wfmo"></a>
# WFMO Program Finder

https://github.com/plee03/comp20-plee/tree/master/comp20-f2015-team16

WFMO Program Finder is a web application that recommends programs for the Tufts-run radio station WFMO based on music genre. Genre statistics for each program were gathered by querying the Spinitron and Last.fm APIs to obtain songs played by the radio station and their genres. The statistics were stored in a MongoDB database that could be queried using an API to produce results for the front-end website.

![Home page and results of WFMO Program Finder](/Images/wfmo_genres2.png)

<a name="snakes"></a>
# Snakes and Routers

https://github.com/charleskwwan/snakes-and-routers

Snakes and Routers is a multiplayer rendition of the traditional game Snake over a network, written in Python. Snakes and Routers uses Pygame and PodSixNet, a networking library. The networking aspect of the game provided the most challenges, such in handling synchronizatinon. Synchronization was accomplished using the CMB algorithm, which uses queues with timestamped events for each client to determine when it is safe to execute an event. 

![Gameplay of Snakes and Routers](/Images/snake.png)


<a name="city"></a>
# Cityscape Procedural Generation

https://github.com/plee03/city

This project produces a procedurally generated cityscape using OpenGL, with options to move the camera via mouse and keyboard. This project has two main steps: procedurally generating a grid of buildings and associated data via a pseudorandom algorithm with constraints, and rendering this data in 3D using OpenGL.

![Image of generated cityscape](/Images/city_image.png)


<a name="pedestrian"></a>
# Pedestrian Traffic Simulator

https://github.com/plee03/comp50-pedestrian

This Erlang project produces results for a concurrent simulation of traffic given information about paths, locations, and pedestrian movement. The project includes a Javascript visualization based on the outputted JSON data. The project uses a message-based implementation in which entities such as pedestrians are separate processes, and communicate with other processes to obtain data on pathing and movement.


![Pedestrian traffic visualization](/Images/pedestrian.png)
