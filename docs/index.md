[![Last PyPi Publish](https://github.com/OptionallyBlueStudios/PackageAPI/actions/workflows/publish.yml/badge.svg)](https://github.com/OptionallyBlueStudios/PackageAPI/actions/workflows/publish.yml)
[![CodeQL](https://github.com/OptionallyBlueStudios/PackageAPI/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/OptionallyBlueStudios/PackageAPI/actions/workflows/github-code-scanning/codeql)

# PackageAPI
An API For Installing Packages Inside Of Your Python Script

### This project is not actively maintained much. It does not need to be.

## How to use
1) Download the file
2) Put it in your project inside a folder called modules
```python
import modules.packageapi
```
Then you can use the GUI to generate a command OR install a package via the GUI
```python
packageapi.gui_package_manager() # Generate Commands
```
You can also use it in your CLI (If you have the PyPI package (being released soon)
```bash
packageapi-gui
```

[Release notes](https://github.com/OptionallyBlueStudios/PackageAPI/releases/latest)
