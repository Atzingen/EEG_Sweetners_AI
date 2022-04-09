<!-- PROJECT SHIELDS -->
<!--
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->

<!-- PROJECT LOGO -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<br />
<p align="center">
  <a href="https://github.com/Atzingen/EEG_Sweetners">
    <img src="EEG.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">EEG Signal Dataset and </h3>

  <p align="center">
    Dataset and Deep Learning models created for comparison of the effect diferent sweetners ans sugar on the EEG signal
    <br />

  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#abstract">Abstract</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

### Introduction

This is a repository for the dataset and NN models for comparison of the effect diferent sweetners ans sugar on the EEG signal. This results where published in <a href="https://github.com/Atzingen/EEG_Sweetners"> not yet available </a>

### Abstract

This study evaluated brain signals from 11 healthy subjects when they tasted passion fruit juice equivalently sweetened with sucrose (9.4 g/100 g), sucralose (0.01593 g/100 g), and aspartame (0.05477 g/100 g). The type of sweetener can influence sensory properties and consumer acceptance and preference of low-calorie products. The ideal sweetener does not exist and it is necessary to use each one in situations that it is best suited for. Aspartame and sucralose can be good substitutes for sucrose in passion fruit juice. Despite the interest in artificial sweeteners, little is known about how artificial sweeteners are processed in the human brain. Herein, electroencephalography (EEG) was recorded from two places in the gustatory cortex (i.e., C3 and C4). Data with artifacts were disregarded and the artifact-free data fed a CNN. The results indicated that the brain responses distinguished juice sweetened with sucrose from that one sweetened with aspartame but not that sweetened with sucralose.

### Installation

1. Install and/or update <a href="https://www.anaconda.com/products/individual">anaconda</a>

2. Clone this <a href="https://github.com/Atzingen/EEG_Sweetners">repository</a>

```sh
git clone https://github.com/Atzingen/EEG_Sweetners.git
```

3. Create the enviroment using the requirements.txt file

  ```sh
  conda create --name eeg --file requirements.txt

  conda activate eeg
  ```

4. Open the notebooks to test the dataset
 
  ```sh
  cd <this_repo_folder>
  jupyuter lab
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

## Contact

Ana Carolina de Sousa Silva - anacss@usp.br 

Gustavo Voltani von Atzingen - gustavo.von.atzingen@gmail.com
 



[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Atzingen/EEG_Sweetners/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/Atzingen/EEG_Sweetners/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Atzingen/EEG_Sweetners/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Atzingen/EEG_Sweetners/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/Atzingen/EEG_Sweetners/blob/master/LICENSE.txt