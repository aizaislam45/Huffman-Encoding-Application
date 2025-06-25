# Huffman Encoding Application

This project is a C++ implementation of Huffman Encoding—an efficient compression algorithm used to reduce the size of text files.

## 💡 Features

- Compresses text files using Huffman coding
- Decompresses encoded files back to original text
- Easy-to-use CLI (Command Line Interface)
- Modular codebase (`encode.cpp`, `decode.cpp`, `huffman.hpp`)


## 🛠️ How to Compile & Run

```bash
# Compile the encoder and decoder
g++ encode.cpp huffman.cpp -o encode
g++ decode.cpp huffman.cpp -o decode

# Run encoding (make sure inputFile.txt exists)
./encode

# Run decoding
./decode
