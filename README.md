[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]





<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">Conways Game Of Life (Python Implementation)</h1>

  <p align="center">
    Conways’s Game Of Life is a Cellular Automation Method created by John Conway.
    <br />
    <a href="https://github.com/AlexAlvarez092/PY-Conways-Game"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/AlexAlvarez092/PY-Conways-Game">View Demo</a>
    ·
    <a href="https://github.com/AlexAlvarez092/PY-Conways-Game/issues">Report Bug</a>
    ·
    <a href="https://github.com/AlexAlvarez092/PY-Conways-Game/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Conways’s Game Of Life is a Cellular Automation Method created by John Conway. This game was created with Biology in mind but has been applied in various fields such as Graphics, terrain generation,etc..

![screenshot](https://media.geeksforgeeks.org/wp-content/uploads/life_game.gif)


### Built With

* [Python3][python-url]



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites
1. **numpy:** For 2D array (matrix) manipulation.
2. **matplotlib^:** For update the simulation or in easy words to make stuffs move.
3. **argparse:** To pass command line arguments in the code


### Installation

1. Clone the repo


```sh
git clone https://github.com/AlexAlvarez092/PY-Conways-Game.git
```


2. Execute


```sh
python animation.py --grid-size 32 --interval 500 --glider
```



<!-- USAGE EXAMPLES -->
## Usage

Because the Game of Life is built on a grid of nine squares, every cell has eight neighboring cells,as shown in the given figure. A given cell (i, j) in the simulation is accessed on a grid [i][j], where i and j are the row and column indices, respectively. The value of a given cell at a given instant of time depends on the state of its neighbors at the previous time step. Conway’s Game of Life has four rules.

1. If a cell is ON and has fewer than two neighbors that are ON, it turns OFF
2. If a cell is ON and has either two or three neighbors that are ON, it remains ON.
3. If a cell is ON and has more than three neighbors that are ON, it turns OFF.
4. If a cell is OFF and has exactly three neighbors that are ON, it turns ON.

So since we know how it works, the next thing we need to figure it out that how to make it work.

### Approach
1. Initialize the cells in the grid.
2. At each time step in the simulation, for each cell (i, j) in the grid, do the following:
  a. Update the value of cell (i, j) based on its neighbors, taking into account the boundary conditions.
  b. Update the display of grid values.

After we done here lets get our hands on code.



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/AlexAlvarez092/PY-Conways-Game/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Alex Alvarez - <alexalvarez@mail.com>

Project Link: [https://github.com/AlexAlvarez092/PY-Quiz-Generator/][https://github.com/AlexAlvarez092/PY-Quiz-Generator/]

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* Book *Python Playground: Geeky Projects for the Curious Programmer*
* [docs-numpy](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html)
* [docs-matplotlib](https://matplotlib.org/users/pyplot_tutorial.html)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AlexAlvarez092/PY-Conways-Game.svg?style=for-the-badge
[contributors-url]: https://github.com/AlexAlvarez092/PY-Conways-Game/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AlexAlvarez092/PY-Conways-Game.svg?style=for-the-badge
[forks-url]: https://github.com/AlexAlvarez092/PY-Conways-Game/network/members
[stars-shield]: https://img.shields.io/github/stars/AlexAlvarez092/PY-Conways-Game.svg?style=for-the-badge
[stars-url]: https://github.com/AlexAlvarez092/PY-Conways-Game/stargazers
[issues-shield]: https://img.shields.io/github/issues/AlexAlvarez092/PY-Conways-Game.svg?style=for-the-badge
[issues-url]: https://github.com/AlexAlvarez092/PY-Conways-Game/issues
[license-shield]: https://img.shields.io/github/license/AlexAlvarez092/PY-Conways-Game.svg?style=for-the-badge
[license-url]: https://github.com/AlexAlvarez092/PY-Conways-Game/blob/master/LICENSE.txt


[python-url]: https://www.python.org/


[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alejandro-%C3%A1lvarez-garc%C3%ADa-365593124/
