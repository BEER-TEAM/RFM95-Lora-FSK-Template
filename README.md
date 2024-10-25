# RFM95-Lora-FSK-Template

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)

## Introduction
This project is a simple template for the RFM95 module, which can be used in either LoRa or FSK modulation. It was developed by a team of students from the Warsaw University of Technology. The project was created as part of the course BIR at the Faculty of Electronics and Information Technology. 

The project uses the [pyLoraRFM9x 1.0.2](https://pypi.org/project/pyLoraRFM9x/) library which is included in the repository. 

The project was tested on the Raspberry Pi Zero 2W.

## Installation
To install this project on your Raspberry Pi, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/BEER-TEAM/RFM95-Lora-FSK-Template.git
    cd RFM95-Lora-FSK-Template
    ```

2. **Ensure Python is installed and the version is >= 3.5**:
    ```sh
    python3 --version
    ```

    If Python is not installed or the version is lower than 3.5, install the latest version:
    ```sh
    sudo apt-get update
    sudo apt-get install python3
    ```

3. **Install the required Python packages**:
    ```sh
    pip3 install -r requirements.txt
    ```

4. **Connect your RF module**:

    Make sure to connect your RF module to the Raspberry Pi as follows:
   
    ![462551593_1099644291793191_4015406996148201914_n](https://github.com/user-attachments/assets/e6436a19-be00-4c16-a0ee-e50048611e3e)


## Usage

TODO - add usage instructions (highlight variables in main file)

```python

```

## Requirements
- Python >= 3.5

## Contributing

We welcome contributions from the community! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors
- [@Piotr Polnau](https://github.com/Vortarin)
- [@Jan Sosulski](https://github.com/jan-sosulski)
- [@Piotr Baprawski](https://github.com/pbaprawski)
