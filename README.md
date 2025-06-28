# PRODIGY_CS_02
# 🖼️ Image Encryption Tool 🔐

A simple Python tool to encrypt and decrypt images using basic pixel manipulation techniques. The script uses XOR operations on pixel values to provide reversible encryption with a user-defined key.

## 💡 How It Works

This tool performs encryption and decryption by applying a bitwise XOR operation with a secret key to each pixel's RGB values. The operation is reversible — applying it again with the same key restores the original image.

## 🛠 Features

- 📷 Encrypt and decrypt images using XOR-based pixel manipulation
- 🔐 Uses a numeric key (0–255) for encryption
- ♻️ Reversible encryption (symmetric)
- 🧱 Built using Python and Pillow (PIL)
