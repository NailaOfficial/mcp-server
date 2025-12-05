# Gemini CLI Installation Steps

This guide provides the necessary commands to install the Gemini CLI on your system.

## Prerequisites

Before you begin, ensure you have Python 3.8 or higher installed on your system. You can check your Python version by running:

```bash
python --version
```

Or on some systems:

```bash
python3 --version
```

You will also need `pip`, the package installer for Python. It is usually installed by default with Python.

## Installation

The recommended way to install the Gemini CLI is by using `pip`.

1.  **Install the package:**

    Open your terminal or command prompt and run the following command to install the Gemini CLI from the Python Package Index (PyPI):

    ```bash
    pip install google-gemini-cli
    ```

    *Note: Depending on your system configuration, you might need to use `pip3` instead of `pip`.*

    ```bash
    pip3 install google-gemini-cli
    ```

2.  **Verify the installation:**

    After the installation is complete, you can verify that the Gemini CLI is installed correctly by checking its version:

    ```bash
    gemini --version
    ```

## Basic Usage

To get started with the Gemini CLI, you can use the `help` command to see a list of available commands and options:

```bash
gemini --help
```
