# 2021-2022-BOUKEZZATA-BERTON-MESLOUH

<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Smart Device</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Lora</a>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


after the manufacture of the gas sensor an AIME, we would like to design a system from a microcontroller ESP32 to collect the data from the sensor and communicate the presence of a certain gas on a server with a LoRA module

Use the `BLANK_README.md` to get started.

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- GETTING STARTED -->
## LoRA

we connected the Lora module to the TTN server "The Things Network" with the library <a href="https://github.com/jpmeijers/RN2483-Arduino-Library.git"> RN2483@jpmeijers </a>

We've connected the 3 pins of the LoRA module to the ESP32
<br/>
```cpp
#define RST 21 //Pin de reset du module LORA
#define RX 18  //Pin RX du module LORA
#define TX 19  //Pin TX du module LORA
```
