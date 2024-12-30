# Universal C++ Compiler Script (runcpp.bat)

A simple yet powerful Windows batch script that allows you to compile and run C++ files with a single command. This script streamlines the C++ development workflow by eliminating the need to type lengthy compile and execute commands repeatedly.

## Features

- Single command compilation and execution of C++ files
- Universal compatibility with any C++ source file
- Simplified workflow for C++ development
- Command available system-wide once configured

## Requirements

- Windows Operating System
- g++ compiler (part of the GCC suite)
  - Can be installed through MinGW or MSYS2 if not already present

## Installation

### 1. Script Setup

1. Download the `runcpp.bat` script
2. Place it in your preferred scripts directory (e.g., `C:\Users\<YourName>\cppscript`)

### 2. PATH Configuration

Add the script's directory to your system's PATH to make it accessible from anywhere:

1. Open Environment Variables:
   - Press `Win + R`
   - Type `sysdm.cpl` and press Enter
   - Navigate to the **Advanced** tab
   - Click **Environment Variables**

2. Edit PATH:
   - Under **User variables**, select `Path`
   - Click **Edit**
   - Click **New**
   - Add the full path to your scripts folder (e.g., `C:\Users\<YourName>\cppscript`)
   - Click **OK** to save changes

### 3. Terminal Restart

- Close and reopen any command prompt or PowerShell windows for changes to take effect

## Usage

Once installed, you can use the script with any C++ file using the following syntax:

```bash
runcpp <filename.cpp>
```

### Example

```bash
runcpp mock.cpp
```

This command will:
1. Compile your C++ file using g++
2. Execute the resulting program automatically

## Troubleshooting

### Common Issues

1. **"'runcpp' is not recognized as an internal or external command"**
   - Verify that the script's directory is correctly added to PATH
   - Ensure you've restarted your terminal after PATH modifications

2. **"'g++' is not recognized as an internal or external command"**
   - Confirm that g++ is properly installed
   - Check if g++ is available in your system's PATH
   - Consider reinstalling MinGW or MSYS2 if needed

## Contributing

Contributions are welcome! If you have suggestions for improvements or bug fixes:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Open a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- GCC team for the g++ compiler
- Windows batch scripting community

## Support

If you encounter any issues or need assistance:
1. Check the troubleshooting section above
2. Open an issue in the repository
3. Contact the maintainer

---

**Note**: This script is designed for Windows environments only. For Linux/Mac users, consider creating an equivalent shell script suited for your operating system.