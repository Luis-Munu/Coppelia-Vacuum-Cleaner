<br/>
<p align="center">
  <a href="https://github.com/Valkam-Git/Coppelia-Vacuum-Cleaner">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Vacuum cleaner</h3>

  <p align="center">
    Personal cleaner used to wipe the floor of CoppeliaSim environments
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/Valkam-Git/Coppelia-Vacuum-Cleaner?color=dark-green) ![Issues](https://img.shields.io/github/issues/Valkam-Git/Coppelia-Vacuum-Cleaner) ![License](https://img.shields.io/github/license/Valkam-Git/Coppelia-Vacuum-Cleaner) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

Vacuum cleaner that automates the movement of a Giraff robot to wipe the floor in a Coppelia simulated environment.
Here's how:

* It makes use of an inverse spiral movement to maximize the covered area.
* The robot is capable of dodging obstacles thanks to a Dynamic Window Approach algorithm (DWA) developed by [@pbustos](https://github.com/pbustos).
* It's able to unstuck itself.

## Built With

The project makes extensive use of [Robocomp](https://github.com/robocomp/robocomp) and [CoppeliaSim](https://www.coppeliarobotics.com/)

## Getting Started

First, you will need to fulfill the prerequisites:

### Prerequisites

The project is based on many Robocomp related components that need to be installed:
 - [Main Robocomp module](https://github.com/robocomp/robocomp)
 - [Giraff robot](https://github.com/robocomp/robocomp-giraff)
 - [Prebuilt environments](https://github.com/pbustos/beta-robotica-class)
 - [CoppeliaSim](https://www.coppeliarobotics.com/)
It is quite tricky to install Robocomp correctly, therefore it is recommended to read the docs carefully.


### Installation

Move this repository to the Components folder of Robocomp.

## Usage

Build the project with CMake and run it.

Make sure both CoppeliaSim and Yolo are running.

## License

Distributed under the MIT License. See [LICENSE](https://github.com/Valkam-Git/Coppelia-Vacuum-Cleaner/blob/main/LICENSE.md) for more information.

## Authors

* **Valkam** - ** - [Valkam](https://github.com/Valkam-Git/) - **
* **AGonzalezLoro** - ** - [AGonzalezLoro](https://github.com/AGonzalezLoro) - **
* **zeta1201** - ** - [zeta1201](https://github.com/zeta1201) - **

## Acknowledgements

* [ShaanCoding](https://github.com/ShaanCoding/)
* [Othneil Drew](https://github.com/othneildrew/Best-README-Template)
* [ImgShields](https://shields.io/)
