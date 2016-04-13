#ifndef DORK_H
#define DORK_H

//Header files used
#include <iostream>
#include <cstring>
#include <fstream>
#include <ncurses.h>
#include <string>
#include <chrono>
#include <thread>
#include <vector>
#include <cstdlib>
#include <random>
#include <unordered_map>

//Namespaces
using namespace std;
using namespace std::this_thread; // sleep_for, sleep_until
using namespace std::chrono; // nanoseconds, system_clock, seconds


//Function prototype

//Display functions
void display_init(); //Function to initialize ncurses terminal
void display_close(); //Function to close ncurses terminal
void intro_display();
void displaytext (std::ifstream&); 
void displaytext_delay(std::ifstream& );
void clearDisplay(int);


#endif
