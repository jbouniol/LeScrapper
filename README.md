# Le Scrapper

## Overview

Le Scrapper is a state-of-the-art AI model designed to perfectly read websites and generate scraping code for users. Developed during the Mistral AI Fine Tuning Hackathon, this project leverages the Mistral API to fine-tune their model, aiming to deliver highly efficient and accurate code generation for web scraping tasks.

## Features

- **Advanced Web Scraping**: Le Scrapper excels at interpreting various website structures and generating precise scraping scripts.
- **User-Friendly**: Simplifies the process of extracting data from websites, making it accessible even to those with minimal coding experience.
- **High Performance**: Optimized for speed and accuracy, ensuring reliable scraping results.
- **Mistral API Integration**: Utilizes the powerful Mistral API for fine-tuning and enhancing the model's capabilities.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Access to the Mistral API
- Basic understanding of web scraping concepts

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Le-Scrapper.git
    cd Le-Scrapper
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up your environment variables for the Mistral API:
    ```sh
    export MISTRAL_API_KEY='your_api_key_here'
    ```

### Usage

To generate scraping code for a specific website, follow these steps:

1. Run the script and provide the website URL:
    ```sh
    python le_scrapper.py --url https://example.com
    ```

2. The generated scraping code will be saved in the `output` directory with a timestamp.

### Example

```sh
python le_scrapper.py --url https://example.com

# Output
# Scraping code generated and saved to output/scraper_20230607.py
