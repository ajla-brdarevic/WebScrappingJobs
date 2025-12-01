# Jobs Web Scrapping

## Overview

The **Jobs Web Scrapping** is is my personal initiative, born out of frustration with having to manually check a huge number of company and job advertiser websites every single day during my exhausting search for employment. To make this process more efficient, I decided to automate it.

I am building the project in Python, which not only helps me streamline my job hunt but also allows me to improve my skills in web scraping, Python programming, and automation techniques. In this way, the project serves a dual purpose: easing the burden of job searching while simultaneously strengthening my technical knowledge.

## Features


## Technologies Used
- **Python 3.x**
- **requests:** For sending HTTP requests.
- **beautifulsoup4 (Beautiful Soup):** For parsing HTML/XML documents.
- **lxml:** A fast parser for Beautiful Soup.

## Installation

### Prerequisites

- Python 3.x
- pip (Python Package Installer)

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/ajla-brdarevic/WebScrappingJobs.git
    cd WebScrappingJobs
    ```

2. Install Python dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Create **config.json** and **rezultati.csv**
- Create a file named **config.json** and **rezultati.csv** in the root directory.
- Note: These files are ignored in the Git repository **(.gitignore)** and is used for privately storing URLs and specific CSS selectors for the websites you are monitoring, and storing results.

## Usage

1. Update **config.json** with the URLs and selectors for the websites you want to monitor.
2. Run the script:
   ```bash
   python scraper.py
   ````
3. Check the generated file **rezultati.csv** for the list of collected job postings.

## Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 

## Contact

For any questions or suggestions, please contact ajlabrdarevic@gmail.com(mailto:ajlabrdarevic@gmail.com).

