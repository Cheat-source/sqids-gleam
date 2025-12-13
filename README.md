# Sqids Gleam 🚀

![Gleam](https://img.shields.io/badge/Gleam-1.0.0-blue)
![ID Generator](https://img.shields.io/badge/ID%20Generator-Short%20Unique%20IDs-green)
![GitHub Releases](https://img.shields.io/badge/Releases-Check%20Now-orange)

Welcome to **Sqids Gleam**, the official Gleam port of Sqids. This tool generates short, unique IDs from numbers, making it easy to create concise identifiers for your applications. Whether you need unique IDs for URLs, database entries, or any other purpose, Sqids Gleam provides a simple and effective solution.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Examples](#examples)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## Features

- **Short Unique IDs**: Generate compact IDs that are easy to read and use.
- **Fast Performance**: Designed for speed, Sqids Gleam can handle large volumes of requests.
- **Simple Integration**: Easy to integrate into your existing projects.
- **Gleam Language**: Built with Gleam, leveraging its performance and safety features.

## Installation

To get started with Sqids Gleam, download the latest release from our [Releases page](https://github.com/Cheat-source/sqids-gleam/releases). After downloading, follow the instructions to execute the file.

```bash
# Example command to run the downloaded file
./sqids-gleam
```

## Usage

Using Sqids Gleam is straightforward. Once installed, you can generate unique IDs by calling the appropriate functions in your code. Here’s a simple example of how to use it:

```gleam
import sqids

let id = sqids.generate(12345)
```

This will produce a unique short ID based on the number `12345`.

## Examples

### Generating a Short ID

```gleam
import sqids

let id = sqids.generate(98765)
println("Generated ID: " + id)
```

### Batch ID Generation

You can also generate multiple IDs at once:

```gleam
import sqids

let ids = sqids.batch_generate([1, 2, 3, 4, 5])
println("Generated IDs: " + ids)
```

## Contributing

We welcome contributions to Sqids Gleam! If you have ideas for new features or improvements, please feel free to submit a pull request. Here’s how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes.
4. Submit a pull request.

Please ensure your code follows the existing style and includes tests where applicable.

## License

Sqids Gleam is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, feel free to reach out. You can open an issue on GitHub or contact the maintainers directly.

To keep up with the latest updates, visit our [Releases page](https://github.com/Cheat-source/sqids-gleam/releases).

Thank you for checking out Sqids Gleam! We hope it helps you generate unique IDs easily and efficiently. Happy coding!