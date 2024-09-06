# Online Assessment Algorithm Project

## Overview
This project aims to solve a problem from an online assessment related to customer service complaints handling. The solution is written in Java and focuses on optimizing service times while adhering to given constraints.

## Problem Statement

#### OA | Minimum Straight Lines to cover all points | hard problem

An airline company wishes to establish a flight service in a new country. The company wants to provide flight service in such a way that will cover all the cities in the country with a minimum number of flights. Given the coordinates of all the cities in the country, the company has to determine the minimum number of straight routes necessary to cover all the cities. Write an algorithm to help the company find the minimum number of straight routes necessary to cover all the cities.

Input
The first line of the input consists of: two space-separated integers: numCities, representing the number of cities in the country(N). The next N lines consist of two space-separated integers: coordX and coordY representing the X and Y coordinates of the cities, respectively.

Output
Print an integer representing the minimum number of straight routes necessary to cover all the cities.

Constraints
0 <= numCitiess <= 10^4
-100 <= coordX, coordY <= 100

Example
Input:
8
1 4
2 3
2 1
3 2
4 1
5 0
4 3
5 4

Output:
2

Explanation:
The points (2,1)(3,2)((4,3)(5,4) fall on a straight line and the points (1,4)(2,3)(3,2)(4,1)(5,0) fall on another straight line.

## Solution Approach
The algorithm uses:
- **Greedy strategy** for complaint prioritization.
- **Dynamic programming** for optimizing the travel route between zones.
- **Java Collections Framework** to handle inputs efficiently.

## Setup and Running the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
