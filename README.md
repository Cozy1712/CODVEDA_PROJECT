# CODVEDA_PROJECT
create python scripts for codveda intern

This project provides a simple command-line tool to **encrypt** and **decrypt** text files using **Fernet encryption**, a symmetric encryption method from the `cryptography` library.

## 📦 Features

- 🔑 Auto-generates and stores a secure encryption key (`secret.key`)
- 🔒 Encrypts any text file into a secure format
- 🔓 Decrypts the encrypted file back to its original form
- 💬 Interactive CLI for selecting encryption or decryption

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/file-encryption-tool.git
cd file-encryption-tool
```

### 2. Install Dependencies

This project requires the `cryptography` library:

```bash
pip install cryptography
```

### 3. Run the Script

```bash
python encrypt_decrypt.py
```

You'll be prompted to choose:
- Whether to **encrypt** or **decrypt**
- The input file name
- The output file name

## 🔐 How It Works

- **Encryption:** The script reads the input file, encrypts the content using a Fernet key, and writes it to a new file.
- **Decryption:** The script reads the encrypted file, decrypts it using the same key, and restores the original content.

> ⚠️ The same key (in `secret.key`) must be used for both encryption and decryption. Keep this file safe!

## 🛡️ Security Note

Fernet encryption is a strong and modern symmetric encryption standard, but this tool is intended for learning and light use cases. For critical data, ensure proper key management and secure environments.

## 🧑‍💻 Author

**Kabiru Kolawole**  
[GitHub](https://github.com/Cozy1712) • [LinkedIn](https://linkedin.com/in/yourprofile)

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
