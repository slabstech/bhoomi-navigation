# ಭೂಮಿ / Bhoomi / Navigation

#### Perpetual Autonomous Habitat System

* Navigation module for UAV 

* [Demo - https://mangala.earth](https://mangala.earth)

* Algorithm 
  * We propose a novel replication algorithm for exploration and mapping of the habitat. From the
    Swarm drones, replica's are created at intersection to solve sub-problems and the drones return to
    the start point/ way point if goal is not reached. Information is stored in graph nodes and the
    replicated data is updated in individual drones on reaching the waypoint. Memory access is global
    read for instances and local write on reaching the waypoint. The graph is updated globally with
    delta information when an instance reaches the waypoint. We propose to test the Hypothesis to
    solve a Maze and to interpret the efficiency of the algorithm compared to other SLAM methods.


* 3 step process - Project 
  * Download
      ````
       git clone --depth 1 https://github.com/slabstech/bhoomi-navigation --branch main
      ````
  * Build
    * docker
      ````
      docker build --rm . -t slabstech/bhoomi-garuda-navigation -f src/navigation/Dockerfile
      ````
    * cpp
       ````     
        cd src/navigation
        cmake -S . -B build
        cmake --build build
        cd build && ctest
      ````
      
  * Run 
      ````
      docker run --rm -it slabstech/bhoomi-garuda-navigation
      ````

* 3 step process - Research
  * Measure  
  * Build  
  * Intervene


* Reference
  * https://github.com/googleapis/google-cloud-cpp

### Powered by
* [S Labs Solutions, India.](https://slabstech.com)

<!-- Embed Generator https://www.labnol.org/embed/google/drive/ 
Manifest - https://www.mozilla.org/en-US/about/manifesto/

Drive https://drive.google.com/drive/folders/18G5hCIlTgJR4C71wIoHms6DEFuJpF5Gk
>

