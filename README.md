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

4. **Connect your RF module**:

    Make sure to connect your RF module to the Raspberry Pi as follows:
![380674785-970074c6-fee1-4666-a7c3-4374f292859c](https://github.com/user-attachments/assets/51f4adcf-dc5b-438c-a5d7-f2d7136b79fd)
![380675023-b1be9c1f-1ffb-4e3c-b1d6-8d63ceecb1ec](https://github.com/user-attachments/assets/326a92bd-7021-41b4-931b-6490143e124c)


## Usage

Modify main.py file according to your needs and run the software with:

```sh
python3 main.py
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
