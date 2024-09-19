<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">IMG2TEXT_PYTESSERACT</h1>
</p>
<p align="center">
    <em>Transform Images into Text, Effortlessly and Accurately.</em>
</p>
<p align="center">
	<!-- Shields.io badges not used with skill icons. --><p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<a href="https://skillicons.dev">
		<img src="https://skillicons.dev/icons?i=md,py">
	</a></p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [📍 Overview](#-overview)
- [🧩 Features](#-features)
- [🗂️ Repository Structure](#️-repository-structure)
- [📦 Modules](#-modules)
- [🚀 Getting Started](#-getting-started)
  - [⚙️ Installation](#️-installation)
  - [🤖 Usage](#-usage)
  - [🧪 Tests](#-tests)
- [🛠 Project Roadmap](#-project-roadmap)
- [🤝 Contributing](#-contributing)
- [🎗 License](#-license)
- [🔗 Acknowledgments](#-acknowledgments)
</details>
<hr>

## 📍 Overview

The Img2Text_Pytesseract project is a robust software tool designed to convert images to text using optical character recognition (OCR) technology, facilitated by the pytesseract library. It features a user-friendly web interface built with Streamlit, allowing users to upload images and view the extracted text. The project simplifies the process of handling various image formats and enhances text detection and organization. It includes a Jupyter notebook for demonstration and educational purposes, helping users set up and understand the OCR process. This makes Img2Text_Pytesseract invaluable for digitizing printed documents and making them editable and searchable, catering to both educational and professional needs.

---

## 🧩 Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | Based on Python, uses pytesseract for OCR, Streamlit for UI, pillow_heif for image handling, and pyngrok for tunneling. Structured with main app and separate processing script. |
| 🔩 | **Code Quality**  | Code is modular and follows Pythonic conventions. The use of comments in scripts aids understandability. |
| 📄 | **Documentation** | Documentation through comments in code is present. Lacks a comprehensive README for overall project setup and usage. |
| 🔌 | **Integrations**  | Integrates pytesseract for OCR, Streamlit for web interface, and pyngrok to expose local server to the internet. |
| 🧩 | **Modularity**    | High modularity with clear separation between image processing and user interface logic. Enhances maintainability and scalability. |
| 🧪 | **Testing**       | No explicit testing frameworks or tools mentioned or included in the repository. |
| ⚡️  | **Performance**   | Performance largely depends on pytesseract's OCR capabilities and image processing efficiency. Not benchmarked in the repository. |
| 🛡️ | **Security**      | No specific security measures or data protection techniques documented. Use of pyngrok may require security considerations. |
| 📦 | **Dependencies**  | Uses pytesseract, Streamlit, pillow_heif, and pyngrok. Dependencies are listed in `requirements.txt` for easy setup. |
| 🚀 | **Scalability**   | Scalable in terms of functionality through Streamlit and potential cloud deployment but lacks explicit scaling strategy. |
```

---

## 🗂️ Repository Structure

```sh
└── Img2Text_Pytesseract/
    ├── Files
    │   └── scanned_textfile
    ├── IMG2TEXTe.ipynb
    ├── app.py
    ├── image_processing.py
    └── requirements.txt
```

---

## 📦 Modules

<details closed><summary>.</summary>

| File                                                                                                        | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ---                                                                                                         | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [requirements.txt](https://github.com/codereyinish/Img2Text_Pytesseract/blob/master/requirements.txt)       | Requirements.txt specifies dependencies essential for the Img2Text_Pytesseract project, ensuring the application can perform image processing and text extraction by utilizing libraries such as pytesseract, streamlit for web app interface, pillow_heif for image format handling, and pyngrok for public URL provisioning.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [app.py](https://github.com/codereyinish/Img2Text_Pytesseract/blob/master/app.py)                           | App.py` serves as the user interface for the Img2Text_Pytesseract repository, utilizing Streamlit to facilitate image uploads and display extracted text. The script integrates image processing functionalities and offers a user-friendly sidebar with instructions and file upload capabilities, enhancing accessibility and interactivity.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [IMG2TEXTe.ipynb](https://github.com/codereyinish/Img2Text_Pytesseract/blob/master/IMG2TEXTe.ipynb)         | The file `IMG2TEXTe.ipynb` within the `Img2Text_Pytesseract` repository appears to serve as a Jupyter notebook designed for setting up version control and possibly documenting or demonstrating the usage of the repositorys capabilities. The notebook includes sections dedicated to git setup, suggesting an instructional or setup guide role within the broader architecture of the repository. This file likely complements the operational components of the repository, such as `app.py` and `image_processing.py`, by providing a user-friendly interface to interact with the underlying codebase. It may include examples of how to use the software to convert images to text using the Pytesseract library, as indicated by the repository's name and structure. The inclusion of version control setup instructions also signifies its utility for guiding new users in configuring their development environment to contribute to or utilize the repository effectively. Overall, `IMG2TEXTe.ipynb` acts as an educational or demonstration tool within the repository, enhancing the accessibility and usability of the software for image-to-text conversion tasks. |
| [image_processing.py](https://github.com/codereyinish/Img2Text_Pytesseract/blob/master/image_processing.py) | Image_processing.py` extracts text from images using optical character recognition (OCR) with pytesseract, processes the image for better text detection, and organizes the output text in a structured format by saving it to a file within the Img2Text_Pytesseract project.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |

</details>

<details closed><summary>Files</summary>

| File                                                                                                        | Summary                                                                                                                                                                                                                                                                                     |
| ---                                                                                                         | ---                                                                                                                                                                                                                                                                                         |
| [scanned_textfile](https://github.com/codereyinish/Img2Text_Pytesseract/blob/master/Files/scanned_textfile) | Contains a scanned image of a text, likely used by the Img2Text_Pytesseract repository to demonstrate or test the OCR capabilities of the system, converting image-based text into editable and searchable text. This aligns with the projects focus on image-to-text conversion processes. |

</details>

---

## 🚀 Getting Started

**System Requirements:**

* **Python**: `version x.y.z`

### ⚙️ Installation

<h4>From <code>source</code></h4>

> 1. Clone the Img2Text_Pytesseract repository:
>
> ```console
> $ git clone https://github.com/codereyinish/Img2Text_Pytesseract
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd Img2Text_Pytesseract
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

### 🤖 Usage

<h4>From <code>source</code></h4>

> Run Img2Text_Pytesseract using the command below:
> ```console
> $ python main.py
> ```

### 🧪 Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```

---

## 🛠 Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/codereyinish/Img2Text_Pytesseract/issues)**: Submit bugs found or log feature requests for the `Img2Text_Pytesseract` project.
- **[Submit Pull Requests](https://github.com/codereyinish/Img2Text_Pytesseract/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/codereyinish/Img2Text_Pytesseract/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/codereyinish/Img2Text_Pytesseract
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/codereyinish/Img2Text_Pytesseract/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=codereyinish/Img2Text_Pytesseract">
   </a>
</p>
</details>

---

## 🎗 License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 🔗 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---
