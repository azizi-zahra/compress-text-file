# Compress Text File

This repository contains a C program for compressing and decompressing text files using Huffman coding. [Huffman coding](https://www.programiz.com/dsa/huffman-coding) is a lossless data compression algorithm that assigns variable-length codes to input characters, with shorter codes assigned to more frequent characters.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [TODO](#todo)
- [License](#license)


## Features

- **Huffman Coding:** Implements Huffman coding for compressing text files.
- **File Compression:** Compresses input text files to reduce their size.
- **Decompression:** Decompresses the compressed files to restore the original text. (⚠ _currently doesn't work_)

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/ZahraAziziGit/compress-text-file.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd compress-text-file
    ```
3. **Compile the C program:**
    ```sh
    gcc compress.c -o run
    ```

## Usage

### Help Menu
To see the help menu, use the following command:
```sh
./run help
```
### Compressing a Text File
To compress a text file, use the following command:

```sh
./run compress path/to/your/file.txt
```

- `compress`: Command to compress the file.
- `path/to/your/file.txt`: Path to the text file you want to compress.

Example:

```sh
./run compress file.txt
```

If your file is located in a different folder, for example on drive D: (windows)

```sh
./run compress D:\\path\\to\\your\\file.txt
```

### Decompressing a Text File (⚠ _currently doesn't work_)

To decompress a text file, use the following command:

```sh
./run decompress path/to/your/file.txt
```

- `decompress`: Command to decompress the file.
- `path/to/your/file.txt`: Path to the compressed file you want to decompress.

Example:

```sh
./rune decompress file.txt
```

If your file is located in a different folder, for example on drive D: (windows)

```sh
./run decompress D:\\path\\to\\your\\file.txt
```

## Project Structure

```plaintext
compress-text-file/
├── LICENSE.txt
├── README.md
└── compress.c
```

- **src/compress.c:** The main program file that handles input arguments and compresses and decompresses the file

## TODO 
⬜  Implement decompression code.

⬜ Separate Huffman code from the main code.

⬜ Refactor compressing function.

⬜ Refactor decompressing function.

## License
This project is licensed under the [MIT](https://github.com/ZahraAziziGit/compress-text-file?tab=MIT-1-ov-file#) License.

---

Thank you for checking out the Compress Text File project! If you have any questions or feedback, feel free to reach out.
