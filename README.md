# Google Colab CLI Tool

A simple tool to automate running and managing Google Colab notebooks directly from the command line.

## Features

- Launch a Colab notebook from the command line.
- Run specific cells or the entire notebook.
- Download updated notebooks after execution.

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
pip install -r requirements.txt
python colab_tool.py launch <notebook_url>
python colab_tool.py download --file <notebook_name>
