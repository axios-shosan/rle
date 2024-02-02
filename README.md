# Image Compression (RLE) and QR Code Generation

This project focuses on image compression using the Run-Length Encoding (RLE) algorithm and the generation of QR codes for the compressed images. The implemented code utilizes Python with libraries such as OpenCV, NumPy, and Pillow for image processing and QR code generation, as well as the pyqrcode library for creating QR codes.
Features

    Image Compression (RLE): The project provides a method to encode grayscale images using the Run-Length Encoding (RLE) algorithm. This algorithm is a simple yet effective way to compress consecutive runs of identical pixel values.

    Compression Rate Calculation: The compression rate, representing the percentage reduction in file size achieved by the encoding process, is calculated and displayed.

    Decoding: A decoding function is implemented to revert the compressed image back to its original form.

    QR Code Generation: For convenience and sharing, QR codes are generated for the compressed image files. Users can scan these codes to retrieve the encoded information.

# Usage

    Encoding and Compression: The script includes examples of encoding and compressing predefined grayscale images (image1_np, image2_np, image3_np) and user-provided images (image1.jpg). The compression rate is calculated and displayed.

    QR Code Generation: The script generates QR codes for the compressed files (FBQRcode.png, IGQRcode.png) using the pyqrcode library. These QR codes can be scanned to retrieve the encoded information.

    Decoding: The script also demonstrates the decoding process, where the compressed images are successfully decoded back to their original form.

# Prerequisites

    Python installed on your machine.
    Required Python libraries: qrcode, PIL, numpy, opencv-python.
