# Notebook to download Gmail Attachments using Python

This project provides a Python notebook that allows you to download attachments from Gmail using the Gmail API.

It is configured to store downloaded attachments in the following structure:
./output/{YYYY}/{MM_Month}/{domain of sender}/{YYYY_MM_DD}_{sender_email}_{filename}.{file_extension}

## Prerequisites

Before running the notebook, make sure you have the following prerequisites installed:

- Python 3.11
- Jupyter Notebook or Visual Studio Code with the Python extension

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/jimdix/gmail_attachment_downloader.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the `extract.ipynb` notebook in Jupyter Notebook or VS Code.

2. Follow the instructions in the notebook to authenticate with your Gmail account and specify the criteria for downloading attachments.

3. Run the notebook cells to start the download process.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
