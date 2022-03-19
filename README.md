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
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL-3.0][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/0wlyW00d/MISP-Research-helper">
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Misp-logo.png" alt="Logo" width="266" height="195">
  </a>

<h3 align="center">MISP Research Helper</h3>

  <p align="center">
   Modification and improvement of the Person object of MISP.<br />
   Improving research capacities of physical and body description, as well as adding cloth description.
    <br />
    <a href="https://www.misp-project.org/documentation/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/0wlyW00d/MISP-Research-helper/issues">Report Bug</a>
    ·
    <a href="https://github.com/0wlyW00d/MISP-Research-helper/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <!--
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
-->
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)
<p align="left">
MISP is an open source software solution for collecting, storing, distributing and sharing cyber security indicators and threats about cyber security incidents analysis and malware analysis. MISP is designed by and for incident analysts, security and ICT professionals or malware reversers to support their day-to-day operations to share structured information efficiently.

The objective of MISP is to foster the sharing of structured information within the security community and abroad. MISP provides functionalities to support the exchange of information but also the consumption of said information by Network Intrusion Detection Systems (NIDS), LIDS but also log analysis tools, SIEMs ...
</p>
For more information checkout official [MISP Github Repository](https://www.misp-project.org)

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [MISP Documentation](https://www.misp-project.org)
* [Google Search Bar](https://www.google.com)
* [Creativity](https://pointerpointer.com)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Object Description -->
## MISP Objects extended

The goal of this project is to extend research capabilities and information about natural person and their appearence. For this we decided to create three new object dedicated to better describe what their looks like.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Object fields description -->
***MISP Object name :*** `personification` - *Describes a person or an identity.*

***Attributes :***
* `portrait` : *portrait of the person*
* `age-range` : *Age range that the person appears to be*
* `weight` : *Weight of a person in Kg*
* `height` : *Height of a person in cm*
* `body-type` : *Body type of a person*
* `shoe-size` : *Shoe size of a person*
* `color-of-eyes` : *Description of a person’s colour of eyes*
* `shape-of-eyes` : *Description of a person’s eye shape*
* `skin-complexion` : *Skin tone and complexion of a person*
* `skin-characteristics` : *Traits or features of a person's skin*
* `other-facial-features` : *Description of other facial features such as nose, cheeks, lips etc...*
* `hair-color` : *Description of a person’s colour of hair*
* `hair-characteristics` : *Description of the characteristics of someones hairs*
* `haircut` : *Description of the characteristics of someones hairs*
* `birthmark` : *An object which describes a person or an identity*


***MISP Object name :*** `tattoo` - *Describes tattoos on a natural person's body.*

***Attributes :***
* `tattoo-body-part` : *Describe the body part where the tattoo is located*
* `tattoo-description` : *Description of the tattoo,its composition*
* `tattoo-style` : *Style of the tattoo*
* `tattoo-color` : *Colors of the tattoo*
* `tattoo-picture` : *Picture of the tattoo*
* `tattoo-size` : *Size of the tattoo*

***MISP Object name :*** `cloth` - *Describes clothes a natural person wears.*

***Attributes :***
* `description` : *Cloth's Description of a natural person*
* `head-accessories` : *Cloth and accessories on the head*
* `top-accessories` : *Cloth and accessories on the top part of the body*
* `bottom-accessories` : *Cloth and accessories on the bottom part of the body*
* `cloth-color` : *Cloth's colors*
* `cloth-picture` : *Cloth's pictures*

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.
-->

<!-- ROADMAP -->
## Roadmap

- [x] Research in the different MISP objects
- Object "person" already exists (But missing fields)
- [x] Merge of similar object
- "interpol-notice" and "person" objects have similarities
- [x] Add tattoo object
- [x] Add cloth object
- [x] Add personification object
- [] Pull Request to the MISP Project
- [] Validation of the MISP objects
- [] End of Project


See the [open issues](https://github.com/0wlyW00d/MISP-Research-helper/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GPL-3.0. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

* Guillaume - [@Github](https://github.com/0wlyW00d)
* Quentin - [@Github](https://github.com/QuentinDuflot)

Project Link: [https://github.com/0wlyW00d/MISP-Research-helper](https://github.com/0wlyW00d/MISP-Research-helper)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
Great teachers, director of our project:
* Alexandre Dulaunoy - [@Github](https://github.com/adulau)
* VINOT Raphaël - [@Github](https://github.com/Rafiot)

</br>without forgetting : 
* My Mom
* My Dad
* [My Pets](https://www.emergencykitten.com)

Are you lost ?
[Find out](https://www.perdu.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/0wlyW00d/MISP-Research-helper.svg?style=for-the-badge
[contributors-url]: https://github.com/0wlyW00d/MISP-Research-helper/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/0wlyW00d/MISP-Research-helper.svg?style=for-the-badge
[forks-url]: https://github.com/0wlyW00d/MISP-Research-helper/network/members
[stars-shield]: https://img.shields.io/github/stars/0wlyW00d/MISP-Research-helper.svg?style=for-the-badge
[stars-url]: https://github.com/0wlyW00d/MISP-Research-helper/stargazers
[issues-shield]: https://img.shields.io/github/issues/0wlyW00d/MISP-Research-helper.svg?style=for-the-badge
[issues-url]: https://github.com/0wlyW00d/MISP-Research-helper/issues
[license-shield]: https://img.shields.io/github/license/0wlyW00d/MISP-Research-helper.svg?style=for-the-badge
[license-url]: https://github.com/0wlyW00d/MISP-Research-helper/blob/master/LICENSE.txt
[product-screenshot]: https://upload.wikimedia.org/wikipedia/commons/9/91/Misp-logo.png
