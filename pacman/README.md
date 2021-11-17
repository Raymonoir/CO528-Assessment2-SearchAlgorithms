# Search problems and algorithms for Pacman

## Files in pacman

Files you'll edit:
1. `GraphSearch.java` Where all of your search algorithms will reside.
2. `SearchProblem.java` Where all of your formalisations of search problems and search heuristics will reside.

Files you should not need to modify: 
3. `Pacman.java` The main file that runs search algorithms for Pacman search problems. 
4. `Maze.java` The class describing maze with some useful functionality and a dedicated maze parser.
5. `Util.java` Useful data structures for implementing search algorithms.

Instructions to run pacman (from command line).
1. Compile all files
```bash
javac @compile_list.txt
```
2. Run the main file
```bash
java Pacman
```
By default it will run depth-first search on `mediumMaze`.  It will throw an exception because DFS is not implemented.
3. You can run pacman with the following parameters to see that the code is working and to familiarize yourself with the command line interface.
```bash
java Pacman -l testMaze -f gowest -a
```
It runs pacman on `testMaze` with a simple search function `gowest` that always tells Pacman to go west. The parameter `-a` enables animation in the console of the Pacman actions.

If you do not want to animate the solution, but want to visualise, you can use the option `-s`
```bash
java Pacman -l testMaze -f gowest -s
```

The available mazes can be found in the folder `mazes`.

Now it is time to implement the search problem formalisations and the search algorithms! Good luck and have fun.

