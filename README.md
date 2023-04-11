<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ajbrumleve/domain_classification_alas">
  </a>

  <h3 align="center">Alas Domain Classification</h3>

  <p align="center">
    Crowdsourced data in the Alas language to be used for Low-Resource domain classification.
    <br />
    <a href="https://github.com/ajbrumleve/domain_classification_alas"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/ajbrumleve/domain_classification_alas/issues">Report Bug</a>
    ·
    <a href="https://github.com/ajbrumleve/domain_classification_alas/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
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

This dataset was created by PT Intercultural Technology Solutions in partnership with International Literacy and Development. Intek Solutions tested their crowdsourced language dataset creation app, ikata, in the [Alas language](https://en.wikipedia.org/wiki/Alas_language) of Southeast Aceh in Indonesia. This data was contributed by individual users responding in Alas in the Android app to open ended prompts given in Indonesian. As users earn points they are compensated with micropayments based on the amount of data contributed which is confirmed to be Alas. There is also some data which was collected manually from a separate project which has been included in the dataset. This data was contributed by Pak Samsidin Selian. 

The data was contributed by 

The nature of the data collection process lends itself to messy data. Alas is spoken by approximately 90,000 speakers, but is rarely written and the orthography is not standardized. As such, this dataset will require a layer of standardization prior to use. The data was collected with open ended questions designed to elicit responses in one of four domains:
*  Story/narrative
*  History
*  Instructions
*  Culture/tourism
  
If the domain is unknown the domain column is left null. In some cases ikata was able to also elicit the Indonesian back translation. In that case the back translation was included as well. The purpose of this project was to test the ikata data collection tool and to see if the dataset created could be used for training a Domain Classification model in a low to no-resource language context. 

An example of the necessary standardization is that Alas typically uses 'kh' in place of 'r'. However, due to influence from Indonesian, both occur throughout the dataset. There are also a number of words which are often abbreviated, for example malet becomes mlt, etc. 



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [ ] Create standardization script to standardize spelling variations
- [ ] Fill in missing domain informaton


See the [open issues](https://github.com/ajbrumleve/domain_classification_alas/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

In particular if you are an Alas speaker and see sentences which could be corrected to be more accurate or consistent, please consider contributing.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. See `LICENSE.md` for more information.

[![MIT License][license-shield]][license-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Andrew Brumleve - [linkedin][linkedin-url] - andrew@intekindonesia.com

Project Link: [https://github.com/ajbrumleve/domain_classification_alas](https://github.com/ajbrumleve/domain_classification_alas)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This project would not have been possible without several partners. 

* [README Template](https://github.com/othneildrew/Best-README-Template)
* [International Literacy and Development](https://ilad.ngo)
* [Majelis Adat Aceh Tenggara](https://maa.acehprov.go.id/)
* The entire Alas community for trying out this new app and working through the bugs with us. May the results of this data support continued development and inclusion of Alas and other Indonesian languages in language technology globally. 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ajbrumleve/domain_classification_alas.svg?style=for-the-badge
[contributors-url]: https://github.com/ajbrumleve/domain_classification_alas/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ajbrumleve/domain_classification_alas.svg?style=for-the-badge
[forks-url]: https://github.com/ajbrumleve/domain_classification_alas/network/members
[stars-shield]: https://img.shields.io/github/stars/ajbrumleve/domain_classification_alas.svg?style=for-the-badge
[stars-url]: https://github.com/ajbrumleve/domain_classification_alas/stargazers
[issues-shield]: https://img.shields.io/github/issues/ajbrumleve/domain_classification_alas.svg?style=for-the-badge
[issues-url]: https://github.com/ajbrumleve/domain_classification_alas/issues
[license-shield]: https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg
[license-url]: https://github.com/ajbrumleve/domain_classification_alas/blob/master/license.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/andrew-brumleve-574239227/

