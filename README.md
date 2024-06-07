# LLM-GEMINI
make LLM using gemini api key 


![Screenshot from 2024-06-07 18-16-04](https://github.com/surenoobster/LLM-GEMINI/assets/154669584/c4123a9c-6a4c-4f30-a0e8-cbb167cdac69)

open this link https://ai.google.dev/

create a new api key of gemini

then do 


echo 'export GOOGLE_API_KEY=your_api_key_here' >> ~/.bashrc
source ~/.bashrc

(FOR LINUX)

then do streamlit run file_name.py


To write documentation for your project on GitHub, you will create a `README.md` file in your repository. This file will serve as the primary source of information about your project, including how to set it up, run it, and any other relevant details.

Here is a step-by-step guide to create a comprehensive `README.md` for your project:

### Step 1: Create a README.md File

1. In your project directory (`~/Documents/workspace`), create a file named `README.md`.

### Step 2: Write the Documentation

Here is a template for a `README.md` file, customized for your project:

```markdown
# Gemini Bot

This project is a Streamlit application that uses Google Generative AI to provide responses to user queries. The application is containerized using Docker.

## Table of Contents

- [Gemini Bot](#gemini-bot)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
    - [Docker Installation](#docker-installation)
    - [Clone the Repository](#clone-the-repository)
    - [Set Up Environment Variables](#set-up-environment-variables)
  - [Building and Running the Docker Container](#building-and-running-the-docker-container)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)

## Features

- Text-based user interface using Streamlit.
- Integration with Google Generative AI for providing responses.
- Containerized using Docker for easy deployment.

## Prerequisites

- Docker installed on your local machine.
- A Google API key with access to Google Generative AI services.

## Installation

### Docker Installation

- **Windows & macOS:** Download and install Docker Desktop from [Docker's official website](https://www.docker.com/products/docker-desktop).
- **Linux:** Follow the instructions on [Docker's official installation page](https://docs.docker.com/engine/install/).

### Clone the Repository

```sh
git clone https://github.com/your-username/LLM-GEMINI.git
cd LLM-GEMINI
```

### Set Up Environment Variables

Create a `.env` file in the project directory and add your Google API key:

```sh
echo "GOOGLE_API_KEY=your_google_api_key_here" > .env
```

## Building and Running the Docker Container

1. **Build the Docker image**:

    ```sh
    sudo docker build -t gemini-bot .
    ```

2. **Run the Docker container**:

    ```sh
    sudo docker run -p 8501:8501 --env-file .env gemini-bot
    ```

## Usage

- Open a web browser and go to `http://localhost:8501`.
- Enter your query in the input box and click on "Ask the question" to get a response from the Gemini Bot.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request to add features or fix bugs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact:

- **Chirag Chawla**
  - Email: chirag.chawla.chy22@iitbhu.ac.in
  - LinkedIn: [linkedin.com/in/chirag-chawla-888025254](https://www.linkedin.com/in/chirag-chawla-888025254)
  - GitHub: [github.com/surenoobster](https://github.com/surenoobster)
```










![Screenshot from 2024-06-07 19-44-33](https://github.com/surenoobster/LLM-GEMINI/assets/154669584/d1e4e68a-4d49-4198-b845-266db068de72)

