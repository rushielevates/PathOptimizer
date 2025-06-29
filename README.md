# Shortest Path Calculator

A brief description of what this project does and who it's for.

## Features

- **Displays the shortest distance** between source and destination.
- **Shows the shortest path** to reach the destination with minimum distance.

## API Reference

**Get shortest distance between node A and node B**  
`GET /shortd/<int:A>/<int:B>`

**Parameters**  
- `source` (integer): Required  
- `destination` (integer): Required

## Tech Stack

**Client**  
React

**Server**  
Flask, Python

## Used By

This project is used by the following:  
- **Students of IIT Guwahati**

## FAQ

**How will I obtain my shortest path from source to destination?**  
Every possible source and destination is mapped with a number ranging from **1 to 64**.  
The application will display the nodes **in order** to reach the destination with the shortest path.
