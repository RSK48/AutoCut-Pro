# Auto-Editor GUI Client

![Auto-Editor GUI Screenshot](https://i.imgur.com/JviStmf.png)

A graphical user interface for the powerful [auto-editor](https://github.com/WyattBlue/auto-editor) command-line tool, making automated video editing simpler for Windows users with Premiere Pro integration.

## Features

- User-friendly interface for auto-editor's cutting capabilities
- Select and process multiple files at once
- Supports .mp4 (video) and .wav (audio) file formats
- Generates Premiere Pro-compatible .xml files for advanced editing
- Simple silence-based cutting with adjustable parameters
- Windows-only optimized interface

## Installation

1. Download the zip file (61KB) from: [AutoCut Pro.zip](https://github.com/RSK48/Auto-editor-mint-/blob/main/AutoCut%20Pro.zip)
2. Unzip the downloaded file
3. Read the "!READ ME.txt" file for complete installation instructions

## Usage

### Basic Editing
1. **Set Parameters**:  
   ![Step 1](https://i.imgur.com/nkHghyE.png)  
   Enter your desired silence duration/margin

2. **Select Output**:  
   ![Step 2](https://i.imgur.com/l1Rcnp0.png)  
   Choose your output format (one at a time)

3. **Select Files**:  
   ![Step 3](https://i.imgur.com/uqwqzDd.png)  
   Choose .mp4 or .wav files to process (multiple files supported)

4. **Run Program**:  
   ![Step 4](https://i.imgur.com/8XUhCsl.png)  
   Click to execute the auto-editing process

### Premiere Pro Integration
1. **Locate XML File**:  
   ![XML File](https://i.imgur.com/qOB1uV5.png)  
   The .xml file is created in your selected file's folder

2. **Right-click XML**:  
   ![Right Click](https://i.imgur.com/IJXV4TG.png)  
   Right-click the generated .xml file

3. **Open With**:  
   ![Open With](https://i.imgur.com/ejiJnqs.png)  
   ![Open With Menu](https://i.imgur.com/CbGOdKV.png)  
   Select "Open with" from the context menu

4. **Find Premiere Pro**:  
   ![Browse](https://i.imgur.com/gfssKaw.png)  
   ![Premiere Path](https://i.imgur.com/yhb57UD.png)  
   ![Select EXE](https://i.imgur.com/GQV6aQO.png)  
   Navigate to:  
   `C:\Program Files\Adobe\Adobe Premiere Pro [version]`  
   Select the Premiere Pro executable

5. **Import XML**:  
   ![Import](https://i.imgur.com/HNyC4M0.png)  
   Double-click the .xml file or import it manually in Premiere Pro

## Development

The Python source code is available for modification:  
[auto_editor_gui.py](https://github.com/RSK48/Auto-editor-mint-/blob/main/auto_editor_gui.py)

Feel free to fork and modify the code to suit your needs.

## Credits

- **Auto-Editor Core**: [WyattBlue/auto-editor](https://github.com/WyattBlue/auto-editor) - The powerful command-line tool that makes this possible
- **GUI Development**: RSK  
  - YouTube: [Aakano-RSK](https://www.youtube.com/@aakano-rsk)  
  - YouTube: [RSK48](https://www.youtube.com/@RSK48)  

## License

MIT License

Copyright (c) 2023 RSK

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
