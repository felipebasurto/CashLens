# CashLens

## Description

CashLens is a state-of-the-art computer vision application powered by YOLOv8 and the Ultralytics hub. The primary function of CashLens is to detect and identify coins on a counter, then aggregate their total value in real-time. This powerful tool is highly beneficial for quick tallying of loose change, improving the efficiency and accuracy of your daily transactions.

## Features

1. **Real-Time Coin Detection and Value Calculation**: The application identifies various coin denominations on a counter in real-time and calculates the total sum, thus making cash counting a breeze.

2. **Integration with YOLOv8**: Leveraging the advanced capabilities of YOLOv8, CashLens provides high accuracy in coin detection.

3. **Built on Ultralytics Hub**: CashLens is built on the Ultralytics hub which offers superior ease of use and seamless experience.

## Installation

Ensure your system meets the following requirements:
- Python 3.7 or later
- PyTorch 1.7 or later

You can install CashLens by cloning the repository and installing the required dependencies:

```bash
git clone https://github.com/<your_username>/CashLens.git
cd CashLens
pip install -r requirements.txt
```

## Usage

To use CashLens, simply run the following command:

```bash
python cashlens.py --source <source_image>
```
Replace `<source_image>` with the path to your image containing coins.

## Contribution

Contributions to CashLens are very welcome! Whether it's bug reports, code improvements, or new features, your input is highly valuable to us. Please feel free to open an issue or a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Support 

If you have any questions or run into any trouble, please reach out through GitHub issues. We'll be more than happy to assist you with your queries.

## Acknowledgements

Big thanks to the Ultralytics team and the creators of YOLOv8 for their amazing work which has made the development of CashLens possible and much easier.
