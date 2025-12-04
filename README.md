📦 KurdNet – Kurdish Handwritten Character & Digit Recognition (Open-Source OCR)

KurdNet is an open-source deep learning system designed to recognize handwritten Kurdish (Sorani) characters and digits.
It supports 35 letters and 10 numerical digits (0–9) and is built using a custom modified AlexNet-style CNN optimized for lightweight deployment and browser-based inference.

KurdNet provides a complete OCR pipeline, including preprocessing, segmentation, model inference, and web-based interaction. The project aims to advance Kurdish language technology, support academic research, and enable educational and document-digitization applications.

🚀 Features

✔ Recognizes all 35 Kurdish Sorani characters and 10 digits

✔ Custom CNN architecture optimized for handwriting recognition

✔ Full preprocessing pipeline: binarization, smoothing, segmentation

✔ Real-time inference in the browser using TensorFlow.js

✔ Image upload + interactive canvas drawing interface

✔ Modular Python/PyTorch training code

✔ Optional web and mobile integration

✔ Open-source and extendable

🧠 Model Architecture

KurdNet uses a modified AlexNet-style convolutional neural network, including:

5 convolutional blocks

Batch normalization for training stability

Max-pooling layers for spatial reduction

Fully connected layers (2048 → 2048 → 800 → 35)

Dropout for regularization

Softmax output for classification

The architecture is tailored to the visual properties of Kurdish handwriting in Perso-Arabic script, including diacritics, dot variations, and writing-style diversity.

🌐 Interactive Web Demo

The repository includes a fully interactive web-based handwriting recognition tool:

Draw Kurdish characters/digits directly on an HTML5 canvas

Upload handwritten images for classification

View the probability distribution of predicted classes

All processing runs locally—no server required

This makes KurdNet suitable for education, demonstrations, and lightweight deployment.

🤝 Contributions

Contributions are welcome!
You can help by:

Adding additional Kurdish handwriting datasets

Improving model architecture or preprocessing

Creating enhanced UI/UX for web or mobile apps

Optimizing runtime performance

Translating documentation

Pull requests and issues are encouraged.

📜 License

This project is released under the MIT License, allowing free use, modification, and redistribution for research and development purposes.

📬 Contact

For collaborations or academic inquiries:

📧 peshraw.abdalla@uoh.edu.iq
