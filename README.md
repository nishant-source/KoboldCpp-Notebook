# KoboldCpp-Notebook

This repository contains the official **KoboldCpp Colab Notebook**, which allows you to run **KoboldCpp** in Google Colab easily. The notebook lets you load models, run text generation, and connect through a Cloudflare tunnel.

## Features

- Load and run KoboldCpp models directly in Colab.
- Supports GGUF models from Hugging Face or custom URLs.
- Cloudflare tunnel for remote access to the KoboldCpp API.
- Optional saving of generated stories to Google Drive.
- GPU acceleration support if available in Colab.

## Getting Started

1. Open the notebook [`colab.ipynb`](colab.ipynb) in Google Colab.
2. Run all cells sequentially.
3. Enter your model URL or select from the dropdown.
4. Wait for the model to download and initialize.
5. Use the remote API URL provided at the end of the notebook to interact with the model.

## Saving Your Work

- To save the notebook to GitHub, use the **File → Save a copy in GitHub** option in Colab.
- Make sure you select the `main` branch or any branch you want to save to.
- Specify a file path and commit message.

## Notes

- GPU is recommended for faster performance.
- Ensure you occasionally check for captchas to prevent disconnections.
- Large models may take several minutes to download and initialize.

## License

This repository is open-source and available under the MIT License.
