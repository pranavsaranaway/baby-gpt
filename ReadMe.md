# Baby-GPT

Baby-GPT is a minimalistic implementation of GPT (Generative Pre-trained Transformer) for educational purposes. This project aims to provide a simple and clear understanding of how GPT models work. We implement a simple version of the architecure described in the Attention is All You Need Paper. 
![image](https://github.com/user-attachments/assets/e03b6bfc-14ed-43b2-9da3-5a4d04259766)

- we implemented:
- character tokenizer
- decoder
- self attention
- multi headed attention
- adam


## Installation

To get started with baby-gpt, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/nano-gpt.git
cd nano-gpt
pip install -r requirements.txt
```

## Usage

To train the model, run the following command:

```bash
python train.py
```

It should automitcally generate the following text. Please increase the hyperparemeters for more accuracy but make sure you have a strong gpu

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://www.openai.com/) for the original GPT model
- Andrej Karpathy's Make More Series
