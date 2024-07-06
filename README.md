# Social_Network_Analysis_-Recommendation_Algorithm-

This project aims to develop a recommendation algorithm for social media networks using the concept of strongly connected components (SCCs). By generating a random directed graph, we simulate a social network and identify SCCs using Tarjan's and Kosaraju's algorithms to provide mutual friend and add-back recommendations.

## Table of Contents
- [Introduction](#introduction)
- [Project Aim](#project-aim)
- [Features](#features)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [Algorithms](#algorithms)
  - [Kosaraju's Algorithm](#kosarajus-algorithm)
  - [Tarjan's Algorithm](#tarjans-algorithm)
- [Output](#output)
- [Build and Run](#build-and-run)
- [License](#license)

## Introduction

In social media networks, recommending friends and connections is crucial for enhancing user engagement. This project uses strongly connected components to find mutual and add-back friend recommendations. By generating a random graph, we simulate the structure of a social network and apply SCC algorithms to identify potential connections.

## Project Aim

The aim of this project is to find a recommendation algorithm for social media networks by:
- Generating a random directed graph to represent a social network.
- Identifying strongly connected components in the graph.
- Using SCCs to provide mutual friend and add-back recommendations.

## Features

- Generate a random directed graph with up to 100 vertices and 1000 edges.
- Find strongly connected components using Kosaraju's algorithm.
- Find strongly connected components using Tarjan's algorithm.
- Provide mutual friend recommendations.
- Provide add-back recommendations.

## Usage

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/social_network_analysis_recommendation_algorithm.git
   cd social_network_analysis_recommendation_algorithm

2. **Build and Run**:
   ```sh
   gcc project.c -o project
   ./project.exe
  
3. **Follow the prompts** to choose between Tarjan's and Kosaraju's algorithms and view the SCCs and recommendations.

