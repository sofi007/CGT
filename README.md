            *************************************************************************************
    Description of OS, Language, Data and Code for Triangle counting and enumerating Algorithm on Prime Graph

* Paper: An efficient exact algorithm for triangle listing in large graphs. Data Mining and Knowledge Discovery, Volume 30

(5): 1350-1369 (2016)
* Authors: Sofiane Lagraa, Hamida Seba:

           *************************************************************************************




OPERATING SYSTEM & SOFTWARES
----------------------------
- Ubuntu1~12.04 x86_64 GNU/Linux, All
  the program is run from terminals
- the program is compiled with the g++ complier version 4.8.1
- The compilation is performed with the following flags options:  -O3  -Wall std=c++11 


PROGRAMMING LANGUAGE
--------------------
C++


/**********************************/
How to run the binairy program ?
/**********************************/

for running:
./TriangleOnPrime -f graphName [-c|-e]
for counting: 
./TriangleOnPrime -f graphName -c
for enumerating:
./TriangleOnPrime -f graphName -e
	it creates automaticaly a file that contain a list of all trinangles. The name of this file is "graphName_all_triangles.dat"

DATASET
--------
The folder dataset represents the graph used in experiments.
The modular decomposition graph file is composed of two parts:

The first part contains the prime graph represented by its corresponding tree. The tree is composed of modules and their sub-modules. The first column represent the level of tree and the second column represents the module.

The second part contains the edges of prime graph.

The two parts are separated by the symbole '#'.

Example of prime graph:

0 Premier  
1 Parallele  
2 11  
2 12  
1 Parallele  
2 Serie  
3 8  
3 9  
2 10  
1 7  
1 Premier  
2 6  
2 5  
2 3  
2 4  
1 0  
1 Serie  
2 2  
2 1  
#  
1 4  
10 16  
11 12  
12 14  
13 14  
15 16  
4 9  
9 10  
