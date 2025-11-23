# EigenRisk_Assessment

### Build Instructions ###

Prerequisite:
1. A c++17 compiler (g++, clang)
2. Cmd to unzip data.7z :
        7z x data.7z

Build:
g++ -std=c++17 car_sales_analysis car_sales_analysis.cpp

Run: ./car_sales_analysis {unzipped_datafile}
Ex- ./car_sales_analysis data.csv