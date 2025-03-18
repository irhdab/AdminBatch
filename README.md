# AdminBatch

A Batch script utility for executing .bat files with administrator privileges on Windows systems.

![Batchfile](https://img.shields.io/badge/Batchfile-4D4D4D?logo=windowsterminal&logoColor=white)

## Features
- Elevate batch file execution to administrator level
- Simple single-file implementation
- Compatible with Windows 7/8/10/11
- No external dependencies required

## Installation
1. Download the script:
   ```
   curl -O https://raw.githubusercontent.com/irhdab/AdminBatch/main/AdminBatch.bat
   ```
2. Place in your script directory
3. Call from other batch files or command line

## Usage
```
@echo off
AdminBatch.bat "your_script.bat"
```

For direct command execution:
```
AdminBatch.bat "net start YourService"
```

## Security Note
⚠️ Always verify the contents of batch files before granting administrative privileges. This tool should only be used with trusted scripts[1].

## Project Structure
```
AdminBatch/
├── AdminBatch.bat      # Core elevation script
└── README.md           # Documentation
```

## Contributing
This project welcomes:
- Security improvements
- Windows version compatibility updates
- Error handling enhancements

Follow standard GitHub workflow:
1. Fork repository
2. Create feature branch
3. Submit pull request
