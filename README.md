# Quick Start

[PyInstaller documentation](https://pyinstaller.org/en/stable/#using-pyinstaller)

1. Write a working Python script

2. Install pyinstaller:<br />
`pip install -U pyinstaller`

3. Generate files with pyinstaller:<br />
`pyinstaller your_file_name.py`

4. This command will generate a *your_file_name*.spec file. Include the dll required by the application and any custom settings ([Using spec files](https://pyinstaller.org/en/stable/#using-spec-files))

5. Once done, generate standalone binary:<br />
`pyinstaller --onefile your_file_name.py`

The binary can be found in the `dist` folder and ran using `./your_file_name`
