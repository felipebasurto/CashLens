# CashLens

**Project on Ultralytics Hub: https://hub.ultralytics.com/projects/TReoJx1IozQRQS2Vjy2J** 

<a href="https://universe.roboflow.com/felipe-cam6q/cashlens-18xas">
    <img src="https://app.roboflow.com/images/download-dataset-badge.svg"></img>
</a>
<a href="https://universe.roboflow.com/felipe-cam6q/cashlens-18xas/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg"></img>
</a>

## Description

CashLens is a computer vision application developed as a student project, powered by YOLOv8 and the Ultralytics hub. The primary function of CashLens is to detect and identify coins on a counter, then aggregate their total value in real-time. 

Despite having certain limitations, it's a useful tool for those looking to experiment with computer vision and machine learning techniques. Anyone interested in expanding the dataset and improving the model's accuracy is highly encouraged to contribute.

## Features

1. **Real-Time Coin Detection and Value Calculation**: The application identifies various coin denominations on a counter in real-time and calculates the total sum.

2. **Integration with YOLOv8**: Leveraging the capabilities of YOLOv8, CashLens aims at coin detection.

3. **Built on Ultralytics Hub**: CashLens is built on the Ultralytics hub, providing a magnificient starting point for those exploring computer vision. It makes everything so easy.

## System Requirements

For optimal performance, it is recommended to run this project on a computer with a GPU and CUDA installed. Without these, the video output might not be as smooth as expected.

## Installation

Ensure your system meets the following requirements:
- Python 3.7 or later
- PyTorch 1.7 or later
- A GPU and CUDA for optimal performance

You can install CashLens by cloning the repository and installing the required dependencies:

```bash
git clone https://github.com/<your_username>/CashLens.git
cd CashLens
pip install -r requirements.txt
```

## Usage

The model file is named `cashlens.pt` and the Jupyter notebook that runs the model shares the same name `cashlens.ipynb`.

To use CashLens, open the `cashlens.ipynb` notebook and execute the cells.

## Contribution

Contributions to CashLens are very welcome! Whether it's bug reports, code improvements, new features, or expanding the dataset, your input is highly valuable to me. Please feel free to open an issue or a pull request.

## Support 

If you have any questions or run into any trouble, please reach out through GitHub issues. We'll be more than happy to assist you with your queries.

## Acknowledgements

Big thanks to the @ultralytics team and the creators of YOLOv8 for their work which has made the development of CashLens possible. I missed the chance to chat with them in South Summit in Madrid, and i really think they are an amazing company (With offices in Madrid!)
