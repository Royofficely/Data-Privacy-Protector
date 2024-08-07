# 🛡️ Privacy Protector

Privacy Protector is a Python tool designed to replace sensitive information in text with fake data. It utilizes regular expressions to identify and replace various types of sensitive information, such as names, phone numbers, email addresses, and more.

## 🚀 Features

- 🔎 Automatic detection of sensitive information
- 🎭 Generation of realistic fake data
- 📄 Support for multiple data types (e.g., names, emails, phone numbers)
- 🔧 Easily extensible for custom data types

## 🛠️ Installation

### Option 1: Install from PyPI (coming soon)

```bash
pip install privacy-protector
```

### Option 2: Install from source

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/privacy-protector.git
   cd privacy-protector
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the package in editable mode:
   ```bash
   pip install -e .
   ```

## 💻 Usage

### Command Line Interface

Run Privacy Protector from the command line:

```bash
privacy-protector
```

You'll be prompted to enter the input and output file names. Default values are `input.txt` and `output.txt`.

### Python API

Integrate Privacy Protector into your Python projects:

```python
from privacy_protector.main import process_text

input_file = "input.txt"
output_file = "output.txt"

processed_text = process_text(input_file, output_file)
```

## 🧪 Testing

Run the test suite to ensure everything is working correctly:

```bash
python -m unittest discover tests
```

## 🔧 Development

To set up the project for development:

1. Clone the repository and navigate to the project directory.
2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install the package in editable mode:
   ```bash
   pip install -e .
   ```

Now you can make changes to the code and test them immediately.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to all the contributors who have helped shape Privacy Protector.
- Inspired by the need for better data privacy tools in the open-source community.

---

Built with ❤️ by Roy Nativ @Officely AI