# Memory Management Chatbot
In this project you will see how to implement and run a little ChatBot program that can answer pbasic questions about Memory Management in C++, which is a very cool topic for fans of efficient coding!

<img src="images/chatbot_demo.gif"/>

In a simple GUI window you can ask the ChatBot about certain C++ Memory Management topics in free text form. The ChatBot creates a knowledge graph representation via loading a text file (the knowledge base). Here ChatBot answers represent the graph nodes and user queries represent the graph edges. After you entered a query and pressed enter, the query is sent to the ChatBot and it uses the [Levenshtein distance](https://en.wikipedia.org/wiki/Levenshtein_distance) to find the most probabl answer and displays it.

## Dependencies for Running Locally
* cmake >= 3.11
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* wxWidgets >= 3.0
  * Linux: `sudo apt-get install libwxgtk3.0-dev libwxgtk3.0-0v5-dbg`
  * Mac: There is a [homebrew installation available](https://formulae.brew.sh/formula/wxmac).
  * Installation instructions can be found [here](https://wiki.wxwidgets.org/Install). Some version numbers may need to be changed in instructions to install v3.0 or greater.

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./membot`.

## Project Structure

<img src="images/project-structure-1.png"/>

<img src="images/project-structure-2.png"/>

## Files of Interest
Fiels that might be most interesting for you from a Memory Management perspective are:
- `chatlogic.h` and `chatlogic.cpp`
- `graphnode.h` and `graphnode.cpp`
- `chatbot.h` and `chatbot.cpp`

A cool exercise would be to clone the original repository from Udacity which can be found [here](), try to solve the tasks yourself and then compare with this solution. Have fun coding!

## Aknowledgements
This is the project for the third course in the [Udacity C++ Nanodegree Program](https://www.udacity.com/course/c-plus-plus-nanodegree--nd213): Memory Management. If you are interested in C++ programming, or just want to freshen up your game, I can highly recommend the course!