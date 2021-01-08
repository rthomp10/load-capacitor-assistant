# load-capacitor-assistant

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/rthomp10/load-capacitor-assistant">
    <img src="https://abracon.com/assets/icons/abracon-logo.svg" alt="Logo">
  </a>
  <h3 align="center">Load Capacitor Assistant</h3>
  <p align="center">
    Assists in picking out appropriate load capacitors for MHz or kHz pierce oscillator circuits.
    <br />
    <a href="https://github.com/rthomp10/load-capacitor-assistant/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#necessary-tools">Necessary Tools</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](bin\images\output.png)

This tool was created to make the life of board design engineeers a bit easier when it comes time to couple a crystal to an IC. This program helps ensure that the gain margin (safety factor) and frequency tolerance of the crystal is within the project's constraints. 

Why:
* A lot of the math is lifted off your shoulders
* It takes the guess work out of the equation

The main thing that's needed for this program are the crystal parameters taken from the datasheet along with the current frequency read out by a buffered output from the board.

### Necessary tools
* [Jupyter Notebook](https://jupyter.org/)

<!-- GETTING STARTED -->
## Getting Started
Once Jupyter Notebook is installed, please run the command below within the directory.

### Usage
This is an example of how to list things you need to use the software and how to install them. This will launch the program in your primary browser.
  ```sh
  jupyter notebook cl-vs-frequency.ipynb
  ```

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
Ryan Thompson - [@rthomp10](https://www.linkedin.com/in/rthomp10/) - ryan.thompson@abracon.com

Project Link: [https://github.com/rthomp10/load-capacitor-assistant](https://github.com/rthomp10/load-capacitor-assistant)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [NumPy](https://numpy.org/)
* [MatplotLib](https://matplotlib.org/)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rthomp10/load-capacitor-assistant
[contributors-url]: https://github.com/rthomp10/load-capacitor-assistant/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rthomp10/load-capacitor-assistant
[forks-url]: https://github.com/rthomp10/load-capacitor-assistant/network/members
[stars-shield]: https://img.shields.io/github/stars/rthomp10/load-capacitor-assistant
[stars-url]: https://github.com/rthomp10/load-capacitor-assistant/stargazers
[issues-shield]: https://img.shields.io/github/issues/rthomp10/load-capacitor-assistant
[issues-url]: https://github.com/rthomp10/load-capacitor-assistant/issues
[license-shield]: https://img.shields.io/github/license/rthomp10/load-capacitor-assistant
[license-url]: https://github.com/rthomp10/load-capacitor-assistant/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/company/abracon/
<<<<<<< HEAD
[product-screenshot]: bin\images\output.png
=======
[product-screenshot]: bin\images\output.svg
>>>>>>> 3fda4d9a02b8c7a0dc7e0da05b82c98103fff83b
