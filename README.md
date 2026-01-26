# SatSchool Outreach Programme 🛰️ 🌍

**Bringing Earth Observation into the Classroom**

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fsatschool-outreach.github.io)](https://satschool-outreach.github.io)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## 📖 About SatSchool

**SatSchool** is an outreach programme designed to introduce lower secondary school pupils (S1-S3 / KS3) to the fascinating world of Earth Observation (EO). 

Initially setup by PhD students from the **SENSE CDT** (Centre for Satellite Data in Environmental Science), our goal is to inspire the next generation of scientists by showing them how we use satellites to monitor our changing planet. 

We provide **12+ hours of freely available, interactive resources** tailored to the STEM curriculum, covering Physics, Geography, Computer Science, Maths, Biology, and Chemistry.

👉 **Visit the website:** [satschool-outreach.github.io](https://satschool-outreach.github.io)

---

## 📚 Modules

Our resources are divided into six core modules, each designed to be self-contained and interactive:

| Module | Description | Key Subjects |
| :--- | :--- | :--- |
| **Introduction to EO** | The basics of satellites, orbits, and sensors. | Physics, Geography |
| **Hands on with Data** | Learn to manipulate and understand real satellite data. | CS, Maths, Geography |
| **Cryosphere** | Explore the frozen parts of our planet from space. | Geography, Maths, Physics |
| **Biosphere** | Monitoring vegetation, forests, and life on land. | Biology, Geography |
| **Atmosphere** | Investigating air quality and weather patterns. | Chemistry, Physics, Geography |
| **Oceans** | Studying sea surface temperature and ocean currents. | Geography, Biology, Physics |

---

## 👩‍🏫 For Teachers & Educators

All our materials are **open access** and free to use. You can download lesson plans, presentations, and activity sheets directly from our [website](https://satschool-outreach.github.io/Modules).

If you use our resources, we kindly ask that you credit **SatSchool**.

---

## 🚀 Get Involved

### Become an Ambassador
Are you a PhD student or researcher in Earth Observation? We are always looking for ambassadors to help deliver these modules in schools. It’s a great way to gain public engagement experience.
* Check out our [Ambassador Guide](https://satschool-outreach.github.io/Ambassador) on the website.

### Contact Us
* **Email**: [satschool.outreach@gmail.com](mailto:satschool.outreach@gmail.com)
* **LinkedIn**: [SatSchool Outreach](https://uk.linkedin.com/company/satschool-outreach)

---

## 💻 Technical / Development

This website is built using **Jekyll** and hosted on **GitHub Pages**. If you want to preview changes on your own computer before pushing them to the live site, follow these steps.

### 1. Prerequisites (Installation)

You need **Ruby** installed on your machine.
* **Windows:** Download [RubyInstaller](https://rubyinstaller.org/downloads/) (use the **Ruby+Devkit** version).
    * ⚠️ **Important:** During installation, ensure you check the box that says **"Add Ruby executables to your PATH"**.
    * if you missed this you can add to path like ```export PATH=$PATH:/c/Ruby32-x64/bin``` (adjust for your version and installation path).
* **Mac:** 🚧 I haven't tried, please create pull requests if you have improvements! 
* **Linux:** 🚧 I haven't tried, please create pull requests if you have improvements!

### 2. Initial Setup

Open your terminal (Git Bash on Windows) and run the following commands:

1.  **Clone the repository** (download the files):
    ```bash
    git clone [https://github.com/satschool-outreach/satschool-outreach.github.io.git](https://github.com/satschool-outreach/satschool-outreach.github.io.git)
    cd satschool-outreach.github.io
    ```

2.  **Install the Jekyll builder**:
    ```bash
    gem install jekyll bundler
    ```

3.  **Install site dependencies**:
    ```bash
    bundle install
    ```

### 3. Running the Website Locally

Whenever you want to work on the site:

1.  Open your terminal in the project folder.
2.  Start the local server:
    ```bash
    bundle exec jekyll serve
    ```
3.  Open your web browser and go to: `http://127.0.0.1:4000`

<!-- ### 🔧 Troubleshooting

* **"Webrick" Error:** If you get an error saying `cannot load such file -- webrick`, run this command to fix it:
    ```bash
    bundle add webrick
    ```
* **Gemfile missing:** If `bundle install` fails because of a missing Gemfile, create one by running:
    ```bash
    echo "source '[https://rubygems.org](https://rubygems.org)'" > Gemfile
    echo "gem 'github-pages', group: :jekyll_plugins" >> Gemfile
    ``` -->

---

## 🤝 Partners & Funding

SatSchool is supported by:
* **SENSE CDT** (Centre for Satellite Data in Environmental Science)
* **NERC** (Natural Environment Research Council)
* **ESERO-UK**
* **The Ogden Trust**

---

## 📄 License

The content of this project created by SatSchool is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.

You are free to use and adapt these materials for **non-commercial** educational purposes, provided you credit **SatSchool**.

**Third-Party Content Disclaimer:**
Some materials (slides, worksheets) may contain images or data from third-party sources (e.g., NASA, ESA, Copernicus) which are used here for educational purposes. These assets retain their original copyright and license terms. Please refer to individual slides/documents for specific image credits.