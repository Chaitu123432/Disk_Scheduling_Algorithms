
# Disk Scheduling Algorithms Simulation

This project is a web application that simulates various disk scheduling algorithms commonly used in operating systems. Users can interactively visualize how different algorithms handle input/output requests on a disk.

## Table of Contents

- [About the Project](#about-the-project)
- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [License](#license)

## About the Project

The project aims to provide a user-friendly platform for understanding and comparing different disk scheduling algorithms. It allows users to select from six algorithms: FCFS, SSTF, LOOK, C-LOOK, SCAN, and C-SCAN. Users can input a request sequence, initial disk head position, and choose the direction of the sequence (left or right). The application then dynamically illustrates how each algorithm processes these requests and moves the disk head accordingly.

## Demo

You can access the live demo of the project [here](https://chaitu123432.github.io/Disk_Scheduling_Algorithms/).

## Features

- Select from six disk scheduling algorithms.
- Input custom request sequences and initial disk head position.
- Choose the direction of the sequence (left or right).
- Visualize disk head movement and request servicing in real-time.
- Interactive graphs generated using Plotly.js.

## Tech Stack

- HTML
- CSS
- JavaScript
- Plotly.js

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Chaitu123432/Disk_Scheduling_Algorithms.git
   ```

2. Open the `index.html` file in your web browser.

3. Select a disk scheduling algorithm from the dropdown menu.

4. Enter a request sequence, initial disk head position, and choose the direction of the sequence.

5. Click on the "Solve" button to visualize the algorithm in action.


## License

This project is licensed under the [MIT License](LICENSE).
