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
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Terraforming Moon</h3>

  <p align="center">
    An infrastructure as code project to terraform the moon!
    <br />
    <a href="https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali"><strong>Explore the project »</strong></a>
    <br />
    <br />
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
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project aims to terraform the moon for human settlement. It utilizes infrastructure as code principles to provision necessary resources on the moon.

Here's why:
* It allows for reproducible and scalable infrastructure deployment.
* It streamlines the setup process, reducing manual configuration errors.
* It enables version control and collaboration on infrastructure changes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Terraform][Terraform-url]][Terraform.io]
* [![AWS][AWS-url]][AWS.com]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

* Terraform
* AWS account with appropriate permissions

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali.git
   ```
2. Enter the project directory
   ```sh
   cd terraforming-moon-general-SavolyLali
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE -->
## Usage

Use Terraform commands to apply the infrastructure configuration defined in the `main.tf` file.

```sh
terraform init
terraform plan
terraform apply
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Add modules for more complex infrastructure setups.
- [ ] Implement monitoring and logging configurations.
- [ ] Integrate with CI/CD pipelines for automated deployments.

See the [open issues](https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali/issues) for a list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Lajos Daniel Savoly - [GitHub Profile](https://github.com/SavolyLali)

Project Link: [https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali](https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/CodecoolGlobal/terraforming-moon-general-SavolyLali.svg?style=for-the-badge
[contributors-url]: https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/CodecoolGlobal/terraforming-moon-general-SavolyLali.svg?style=for-the-badge
[forks-url]: https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali/network/members
[stars-shield]: https://img.shields.io/github/stars/CodecoolGlobal/terraforming-moon-general-SavolyLali.svg?style=for-the-badge
[stars-url]: https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali/stargazers
[issues-shield]: https://img.shields.io/github/issues/CodecoolGlobal/terraforming-moon-general-SavolyLali.svg?style=for-the-badge
[issues-url]: https://github.com/CodecoolGlobal/terraforming-moon-general-SavolyLali/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/company/codecool-global
[Terraform.io]: https://www.terraform.io/
[Terraform-url]: https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white
[AWS.com]: https://aws.amazon.com/
[AWS-url]: https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white
