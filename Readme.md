# SiteCrawl

SiteCrawl is a powerful Python-based website accessibility analysis tool designed to crawl websites and provide insights into page accessibility and asset availability. With its intuitive interface and robust functionality, SiteCrawl helps website owners and developers identify and address issues related to broken links and missing assets like images and PDF files.

## Features

- Crawls websites and extracts links
- Checks the availability of web pages and assets
- Generates reports on broken links and missing assets
- Supports parallel crawling for improved performance
- Utilizes Scrapy, a popular web crawling framework in Python
- Deployable on AWS serverless infrastructure

## Project Structure

The project follows a well-organized structure to maintain code readability and modularity. Here's an overview of the project's structure:

```bash
SiteCrawl/
├── sitecrawl/
│ ├── spiders/
│ │ ├── site_crawler.py
│ │ └── ...
│ ├── items.py
│ ├── pipelines.py
│ └── ...
├── tests/
├── README.md
├── requirements.txt
└── ...
```

## Getting Started

Follow these steps to set up and run the SiteCrawl project locally:

1. Clone the repository: git clone <repository_url>
2. Navigate to the project directory: cd SiteCrawl
3. Create a virtual environment: python -m venv venv
4. Activate the virtual environment:

- For Windows:
  ```
  venv\Scripts\activate
  ```
- For macOS/Linux:
  ```
  source venv/bin/activate
  ```

5. Install the dependencies: pip install -r requirements.txt
6. Run the crawler: scrapy crawl <crawler-file-name.py>
7. Check the generated reports in the output directory.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.
