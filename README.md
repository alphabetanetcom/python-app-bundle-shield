# Python App Bundle Shield Script Documentation

[![License](https://img.shields.io/badge/license-Custom-blue.svg)](LICENSE.md)
[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)](https://www.python.org/downloads/)
[![Cross-Platform](https://img.shields.io/badge/cross--platform-yes-brightgreen.svg)](#1-introduction)
[![App Protection](https://img.shields.io/badge/app-protection-brightgreen.svg)](#1-introduction)
[![Source Protection](https://img.shields.io/badge/source-protection-brightgreen.svg)](#1-introduction)
[![Code Security](https://img.shields.io/badge/code-security-brightgreen.svg)](#7-recommendations-and-best-practices)
[![Python Obfuscator](https://img.shields.io/badge/python-obfuscator-blue.svg)](#2-key-features)
[![Executable Creation](https://img.shields.io/badge/executable-creation-green.svg)](#6-detailed-description-of-each-function)
[![License Management](https://img.shields.io/badge/license-management-blue.svg)](#3-main-functions-of-the-script)
[![Secure Distribution](https://img.shields.io/badge/secure-distribution-green.svg)](#7-recommendations-and-best-practices)

*Version: 1.3 GUI  
© 2024 αβ.net (alphabetanet.com) - Alpha Beta Network. All Rights Reserved.*

---

**Note:** This project is currently in **Beta Testing** and available for free.

**Table of Contents**

- [1. Introduction](#1-introduction)
- [2. Key Features](#2-key-features)
- [3. Main Functions of the Script](#3-main-functions-of-the-script)
- [4. Installation](#4-installation)
  - [4.1 Installing Required Packages](#41-installing-required-packages)
  - [4.2 System Requirements](#42-system-requirements)
- [5. User Interface Overview](#5-user-interface-overview)
- [6. Detailed Description of Each Function](#6-detailed-description-of-each-function)
  - [6.1 Packaging Python Source Files](#61-packaging-python-source-files)
  - [6.2 Packaging Compiled Python Files](#62-packaging-compiled-python-files)
  - [6.3 Embedding the Full Python Runtime](#63-embedding-the-full-python-runtime)
  - [6.4 Additional Protection Layers](#64-additional-protection-layers)
- [7. Usage Instructions](#7-usage-instructions)
  - [7.1 Basic Packaging of a Source File](#71-basic-packaging-of-a-source-file)
  - [7.2 Packaging with Full Python Runtime](#72-packaging-with-full-python-runtime)
  - [7.3 Packaging with Cloud-Protected Scripts](#73-packaging-with-cloud-protected-scripts)
- [8. Recommendations and Best Practices](#8-recommendations-and-best-practices)
- [9. Integration with Alpha Beta Network Tools](#9-integration-with-alpha-beta-network-tools)
- [Appendix A: Installation of Required Packages](#appendix-a-installation-of-required-packages)
- [Appendix B: Cross-Platform Compatibility](#appendix-b-cross-platform-compatibility)
- [Appendix C: Contact Information](#appendix-c-contact-information)

---

# 1. Introduction

The **Python App Bundle Shield Script** is a powerful, user-friendly tool designed to help developers create **standalone protected applications** and executable files based on Python scripts of varying complexity. This cross-platform solution supports Python versions 3.6 and above, allowing you to package your Python code into self-contained executables for secure distribution.

Key benefits of using this script include:

- **Secure Code Sharing**: Utilize advanced encryption and obfuscation methods to protect your Python code during distribution.
- **Source Code Protection**: Prevent unauthorized access to your code with multi-level protection mechanisms.
- **Seamless Application Updates**: Update your applications without requiring end-users to reinstall them when using **Alpha Beta Network** cloud platform protection tools.
- **Usage Restrictions**: Implement restrictions on each instance of your application, such as expiration dates, hardware-bound licensing, usage frequency limits, and more.
- **Cross-Platform Compatibility**: Create applications that work on Windows, macOS, Linux/Unix, and other operating systems where Python 3.6+ is installed.
- **Ease of Use**: Package applications with just a few clicks using a simple graphical interface, without the need for complex configurations.

By combining the **Python App Bundle Shield** with other tools from the **Alpha Beta Network** cloud platform, developers can achieve the widest and most flexible possibilities for **secure distribution** of their applications.

# 2. Key Features

1. **Unique Code Analysis Technology**: Automatically analyzes and collects data about imported modules and dependencies, allowing the use of obfuscated `.py` code and compiled `.pyc` files from Python version 3.6 onwards.

2. **Automatic Embedding of Python Environment**: Embeds your complete configured Python environment with all imported modules and packages installed via `pip` into the application build.

3. **Additional Protection Layers**: Implements code obfuscation and encryption of created executable files for enhanced security.

4. **Seamless Updating of Applications**: Allows updating of created applications (fixing bugs, adding functionality) without the need to reinstall them when using Alpha Beta Network cloud protection tools like the [Secure Python Code Manager Script](https://github.com/alphabetanetcom/secure-python-code-manager).

5. **Usage Restrictions**: Enables the implementation of restrictions on the use of each instance of your program (by expiration date, allowed user hardware, usage frequency, and more) when using Python scripts with Alpha Beta Network cloud protection tools ([Python Obfuscator Online](https://obfuscator.alphabetanet.com/) and [Secure Python Code Manager Script](https://github.com/alphabetanetcom/secure-python-code-manager)), as well as local protection tools that do not require internet access ([Local Python Code Protector Script](https://github.com/alphabetanetcom/local-python-code-protector) and [Python Binary Optimization Compiler](https://github.com/alphabetanetcom/python-binary-optimization-compiler)).

6. **Support for Cloud-Protected Scripts**: Provides extensive capabilities to use Python scripts protected by the Alpha Beta Network cloud platform, facilitating secure code sharing and source code protection.

7. **Ease of Use**: Features a simple, user-friendly graphical interface that requires no complex configurations, allowing you to create secure standalone applications with minimal effort.

# 3. Main Functions of the Script

- **Packaging Python Scripts into Executables**: Converts Python source files (`.py`) and compiled files (`.pyc`) into standalone executables, making them runnable on systems without requiring Python installation.

- **Embedding Full Python Runtime**: Optionally embeds the entire Python runtime environment and all necessary dependencies into the executable, ensuring functionality even on systems without Python installed.

- **Code Obfuscation and Encryption**: Applies multi-level protection with dynamic encryption and obfuscation techniques to enhance Python code security.

- **Integration with Cloud Protection Tools**: Facilitates the use of scripts protected by Alpha Beta Network cloud platform tools, enabling seamless updates and implementation of usage restrictions.

# 4. Installation

Before using the **Python App Bundle Shield Script**, ensure that you have **Python 3.6+** installed on your system.

## 4.1 Installing Required Packages

The script requires the following Python packages:

- `requests`
- `psutil`
- `cryptography`
- `decompyle3`
- `xdis`
- `astor`
- `pyinstaller`
- `tkinter` (usually included with Python)

You can install them using `pip`:

```bash
pip install requests psutil cryptography decompyle3 xdis astor pyinstaller
```

> **Note:** For Windows users, `tkinter` may not be included by default. You may need to run the Python installer again and select the option to install `tkinter`.

Ensure that you are using the correct version of `pip` associated with your Python 3 installation. If you are using a virtual environment, activate it before installing the packages.

## 4.2 System Requirements

- **Operating System**: Windows, macOS, Linux/Unix, or any OS where Python 3.6+ is installed.
- **Python Version**: Python 3.6 or higher.
- **Dependencies**: As listed above.

# 5. User Interface Overview

The **Python App Bundle Shield** features a graphical user interface (GUI) with the following components:

- **File Selection**: Browse and select the Python file (`.py` or `.pyc`) you wish to package.
- **Options**:
  - **Embed Full Python Runtime**: Includes the full Python environment and all installed `pip` packages in the build. Useful when your script uses additional modules or cloud-protected scripts.
  - **Disable Console Window**: Hides the console window when running the application (useful for GUI applications).
  - **Create a One-File Bundled Executable**: Packages everything into a single executable file.
- **Additional Modules**: Specify any additional modules (comma-separated) that need to be included.
- **Progress Display**: Shows the progress of the packaging process.
- **Messages**: Displays logs and messages during the process.

# 6. Detailed Description of Each Function

## 6.1 Packaging Python Source Files

The script packages Python source files (`.py`) into standalone executables. It performs the following steps:

- **Code Analysis**: Automatically analyzes the code to detect imported modules and dependencies.
- **Code Obfuscation**: Applies multi-level obfuscation and encryption to the code.
- **Dependency Inclusion**: Includes necessary modules and packages in the build.
- **Executable Creation**: Uses PyInstaller to create the executable file.

## 6.2 Packaging Compiled Python Files

The script can also package compiled Python files (`.pyc`), including those from Python version 3.6 onwards without available decompilers. It handles:

- **Version Detection**: Determines the Python version used to compile the `.pyc` file.
- **Code Handling**: Converts the `.pyc` file back to a safe code representation and re-protects it.
- **Executable Creation**: Packages the code into an executable, ensuring compatibility with the required Python version.

## 6.3 Embedding the Full Python Runtime

By activating the **Embed Full Python Runtime** option, the script:

- **Includes Python Interpreter**: Embeds the Python interpreter into the application build.
- **Includes Installed Packages**: Automatically includes all modules and packages installed via `pip` in your current environment.
- **Creates Universal Environment**: When using cloud-protected scripts, it creates a special universal environment to maximize functionality and ensure smooth interaction with imported modules.

## 6.4 Additional Protection Layers

The script enhances security by:

- **Code Obfuscation**: Implements multi-level code obfuscation techniques.
- **Encryption**: Encrypts the code within the executable.
- **Execution Restrictions**: Supports usage restrictions when used in conjunction with Alpha Beta Network protection tools.

# 7. Usage Instructions

## 7.1 Basic Packaging of a Source File

To package a Python source file into an executable without additional options:

1. **Launch the Script**: Run the `python_app_bundle_shield.py` script.
2. **Select Your File**: Click "Browse" and select your `.py` file.
3. **Click "Start"**: The script will package your file into an executable in the `dist` directory.

## 7.2 Packaging with Full Python Runtime

If your script uses additional modules or packages installed via `pip`, or you are using cloud-protected scripts, it is recommended to embed the full Python runtime:

1. **Select Your File**: As above.
2. **Enable "Embed Full Python Runtime"**: Check the option.
3. **Optional**: Specify any additional modules in the "Additional Modules" field. If your application requires additional modules that are not automatically detected, you can specify them (comma-separated) in the **Additional Modules** field.
4. **Click "Start"**: The script will package your file into an executable, including the full Python runtime.

## 7.3 Packaging with Cloud-Protected Scripts

When using scripts protected by Alpha Beta Network cloud tools:

1. **Obtain Cloud-Protected Script**: Use the [Python Obfuscator Online](https://obfuscator.alphabetanet.com/) or [Secure Python Code Manager Script](https://github.com/alphabetanetcom/secure-python-code-manager) to obtain your protected script.
2. **Select Your File**: Choose the cloud-protected `.py` file.
3. **Enable "Embed Full Python Runtime"**: Check the option.
4. **Click "Start"**: The script will create an executable optimized for cloud-protected scripts.

**Note**: If your cloud-protected script uses external programs (besides packages installed via `pip`), you can try copying these programs to the `_internal` directory of the created application and verify functionality.

# 8. Recommendations and Best Practices

- **Use Separate Environments**: When embedding the full Python runtime, it's recommended to use a separate environment configured specifically for your script to keep the build size compact.

- **Test on Clean Systems**: Test your application's autonomy on a clean virtual machine or sandbox where only the operating system is installed.

- **Use Cloud Protection for Enhanced Security**: Consider using the [Alpha Beta Network cloud platform](https://alphabetanet.com) protection tools for advanced code encryption and secure distribution.

- **Match Operating Systems**: Create standalone applications on the operating system where future use is planned and with the same architecture.

- **Use Appropriate Python Version**: Use the tool in an environment with the Python version that is directly required for your script's operation.

- **Handle External Dependencies**: If your script uses external programs, include them in the `_internal` directory of the application build.

- **Avoid Untrusted Scripts**: Do not use this tool to create applications based on Python scripts from unreliable or unknown sources, as the code is automatically executed for analysis.

- **Leverage Alpha Beta Network Tools**: Combine this script with other Alpha Beta Network tools for multi-layered protection.

# 9. Integration with Alpha Beta Network Tools

Combining the **Python App Bundle Shield** with other tools from the **Alpha Beta Network** cloud platform provides the widest and most flexible possibilities for secure distribution:

- **[Python Obfuscator Online](https://obfuscator.alphabetanet.com/)**: Use for advanced cloud-based code obfuscation and protection.

- **[Secure Python Code Manager Script](https://github.com/alphabetanetcom/secure-python-code-manager)**: Manage licenses, implement usage restrictions, and seamlessly update applications.

- **[Local Python Code Protector Script](https://github.com/alphabetanetcom/local-python-code-protector)**: Apply local protection without requiring internet access.

- **[Python Binary Optimization Compiler](https://github.com/alphabetanetcom/python-binary-optimization-compiler)**: Compile Python code into native machine code executables for performance optimization and code protection.

By integrating these tools, you can enhance **secure code sharing**, enforce **source code protection**, and implement flexible licensing and usage restrictions.

# Appendix A: Installation of Required Packages

Ensure the following packages are installed:

```bash
pip install requests psutil cryptography decompyle3 xdis astor pyinstaller
```

If you encounter issues related to package versions or compatibility, consider creating a virtual environment for your project.

# Appendix B: Cross-Platform Compatibility

The **Python App Bundle Shield** supports packaging applications for:

- **Windows**
- **macOS**
- **Linux/Unix**

**Notes**:

- Create the executable on the target operating system for best compatibility.
- For Windows, the executable will have a `.exe` extension.
- On macOS and Linux, you may need to run `chmod +x` on the executable to make it runnable.

# Appendix C: Contact Information

If you experience issues or have questions, please contact the **Alpha Beta Network Research Team**.

- **Website**: [https://alphabetanet.com](https://alphabetanet.com) | [https://αβ.net](https://xn--mxac.net)
- **Official Telegram Channel**: [https://t.me/alphabetanetcom](https://t.me/alphabetanetcom)

Stay connected to receive updates, provide feedback, and get early access to extended functionality.

---

© 2024 αβ.net (alphabetanet.com) - **Alpha Beta Network**. All Rights Reserved.
