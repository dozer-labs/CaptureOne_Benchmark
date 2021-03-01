
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, @DozerLabs, ben@dozer-labs.com, Capture One Benchmarker, Benchmarking the Capture One processing pipeline with real-world input.
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <!-- <a href="https://github.com/dozer-labs/CaptureOne_Benchmark">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">Capture One Benchmarker</h3>

  <p align="center">
    Benchmarking the Capture One processing pipeline with real-world input.
    <br />
    <a href="https://github.com/dozer-labs/CaptureOne_Benchmark"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <!-- <a href="https://github.com/dozer-labs/CaptureOne_Benchmark">View Demo</a>
    · -->
    <a href="https://github.com/dozer-labs/CaptureOne_Benchmark/issues">Report Bug</a>
    ·
    <a href="https://github.com/dozer-labs/CaptureOne_Benchmark/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <!-- <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul> -->
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
    <!-- <li><a href="#acknowledgements">Acknowledgements</a></li> -->
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

This project is to provide a simple way to determine a sample "score" for Capture One's processing pipeline. This is chiefly meant for comparative purposes only.


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

The underlying code is based on Apple's OSAScript (via AppleScript). As Capture One provides scripting support solely via OSAScript, **this tool is only compatible with OSX/macOS-based systems.**
* Capture One version 20 or 21: www.captureone.com

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/dozer-labs/CaptureOne_Benchmark.git
   ```
   or manually download the .scpt files.
   
2. Copy the .scpt files to your Capture One Scripts folder at the user Library level:
   ```
   ~/Library/Scripts/Capture One Scripts/
   ```
   This can be accessed quickly via Finder's **Go > Go To Folder...** item, or via Capture One's **Scripts > Open Script Folder** item.

3. Open Capture One (or, if it's open aleady, choose **Scripts > Update Scripts Menu**). The benchmark scripts should be available in the Scripts menu.



<!-- USAGE EXAMPLES -->
## Usage
Choose a set of image files as your "baseline" input set. Select them and only them in the Browser, and run the script.

_For more examples, please refer to the [Documentation on our blog](https://dozer-labs.com)_.



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/dozer-labs/CaptureOne_Benchmark/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
<!-- ## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request -->



<!-- LICENSE -->
## License

See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Ben - Head of Product Development at Dozer Labs, LLC

[@DozerLabs](https://twitter.com/DozerLabs) - ben@dozer-labs.com

Project Link: [https://github.com/dozer-labs/CaptureOne_Benchmark](https://github.com/dozer-labs/CaptureOne_Benchmark)


