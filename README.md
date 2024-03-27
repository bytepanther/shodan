# Shodan API Extractor

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

The Shodan API Extractor is a tool written in Rust that allows you to extract information from Shodan.io using its API. Shodan.io is a search engine for Internet-connected devices, and its API provides programmatic access to its vast database of information.

This tool provides a convenient way to interact with the Shodan.io API, allowing you to retrieve information about specific devices, search for devices based on various criteria, and perform other operations supported by the API.

## Features

- Retrieve information about specific devices
- Search for devices based on various criteria
- Perform other operations supported by the Shodan.io API

## Installation

1. Install Rust and Cargo by following the instructions at [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).

2. Clone this repository:

    ```shell
    git clone https://github.com/bytepanther/shodan.git
    ```

3. Build the project:

    ```shell
    cd shodan
    cargo build --release
    ```

4. Run the tool:

    ```shell
    cargo run --release
    ```

## Usage

To use the Shodan API Extractor, you will need an API key from Shodan.io.