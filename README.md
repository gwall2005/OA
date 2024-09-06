# Online Assessment Algorithm Project

## Overview
This project aims to solve a problem from an online assessment related to customer service complaints handling. The solution is written in Java and focuses on optimizing service times while adhering to given constraints.

## Problem Statement
Adison works for a client servicing company whose head office is located in zone "1" in a city. He needs to service `Q` complaints in the order in which they are assigned. For each complaint, he is given:
- The zone `X` where the complaint is filed.
- The time limit `K` within which the complaint must be addressed.

The goal is to optimize the service route and time taken to address all complaints within the given constraints.

## Solution Approach
The algorithm uses:
- **Greedy strategy** for complaint prioritization.
- **Dynamic programming** for optimizing the travel route between zones.
- **Java Collections Framework** to handle inputs efficiently.

## Setup and Running the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
