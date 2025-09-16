# Installation Guide - Crash/Faces Studio

Complete installation instructions for all platforms.

## Quick Installation (Recommended)

### Step 1: Check Python
```bash
python --version
```
**Required**: Python 3.7 or higher

### Step 2: Install Dependencies
```bash
# Install required Python package for image processing
pip install Pillow
```

### Step 3: Download & Run
```bash
# Download the files
git clone <repository-url>
cd crash-faces-studio

# Run the complete application
python crash_faces_studio.py
```

**Full rendering functionality included!** All features are now enabled.

---

## Detailed Installation by Platform

### 🐧 Linux (Ubuntu/Debian)

```bash
# Update system
sudo apt update

# Install Python, tkinter, and FFmpeg
sudo apt install python3 python3-tk python3-pip ffmpeg

# Install Python dependencies
pip3 install Pillow

# Download Crash/Faces Studio
git clone <repository-url>
cd crash-faces-studio

# Run the application
python3 crash_faces_studio.py
```

### 🍎 macOS

```bash
# Install dependencies via Homebrew
brew install python-tk ffmpeg

# Install Python dependencies
pip3 install Pillow

# Download Crash/Faces Studio
git clone <repository-url>
cd crash-faces-studio

# Run the application
python3 crash_faces_studio.py
```

### 🪟 Windows

1. **Install Python**:
   - Download from [python.org](https://www.python.org/downloads/)
   - ✅ Check "Add Python to PATH" during installation
   - tkinter is included automatically

2. **Install FFmpeg**:
   - Download from [ffmpeg.org](https://ffmpeg.org/download.html)
   - Extract to `C:\ffmpeg`
   - Add `C:\ffmpeg\bin` to your system PATH

3. **Install Dependencies & Run**:
   ```cmd
   # Open Command Prompt or PowerShell
   pip install Pillow
   
   git clone <repository-url>
   cd crash-faces-studio
   
   # Run the application
   python crash_faces_studio.py
   ```

---

## ✅ Full Rendering Enabled

**All features are now included and functional!**

The repository now contains:
```
crash-faces-studio/
├── crash_faces_studio.py    # Main application with full rendering
├── blackwhite.py             # Advanced rendering with freeze frames  
├── script.py                 # Basic rendering
├── README.md                 # User guide
├── INSTALL.md               # This installation guide
└── ...                      # Documentation files
```

**What works:**
- ✅ Visual timeline preview
- ✅ Full video rendering 
- ✅ Progress tracking with percentage
- ✅ Real-time log output
- ✅ Stop rendering functionality
- ✅ All advanced timing features
- ✅ Black & white conversion
- ✅ Cache system for speed
- ✅ Cross-platform compatibility

---

## Alternative Installation Methods

### Method 1: Direct Download
1. Download `crash_faces_studio.py` directly
2. Save to any folder
3. Run: `python crash_faces_studio.py`

### Method 2: Virtual Environment (Recommended for developers)
```bash
# Create virtual environment
python -m venv crash-faces-env

# Activate it
# Linux/macOS:
source crash-faces-env/bin/activate
# Windows:
crash-faces-env\Scripts\activate

# Download and run
git clone <repository-url>
cd crash-faces-studio
python crash_faces_studio.py
```

---

## Verification

### Test Basic Installation
```bash
python crash_faces_studio.py
```
✅ **Expected**: GUI window opens with dark theme

### Test Timeline Features
1. Click "Browse" and select a folder with images
2. Adjust duration/FPS settings
3. Watch timeline update in real-time
✅ **Expected**: Green/red blocks appear representing frames

### Test Full Rendering (if installed)
1. Configure settings
2. Click "CREATE ANIMATION"
✅ **Expected**: Progress bar shows rendering progress

---

## Troubleshooting

### "python: command not found"
- **Linux**: `sudo apt install python3`
- **macOS**: Install via Homebrew or python.org
- **Windows**: Reinstall Python with "Add to PATH" checked

### "tkinter not found" or GUI doesn't appear
```bash
# Linux
sudo apt install python3-tk

# macOS
brew install python-tk

# Windows - tkinter should be included, try reinstalling Python
```

### "No module named 'PIL'" or similar
This app only uses standard library modules. If you see this error:
- Make sure you're running the correct file
- Try in a fresh Python environment

### Timeline not responding
- Ensure image folder contains JPG/PNG files
- Try with a smaller number of images first
- Check console for error messages

### Performance issues
- Use folders with < 1000 images
- Close other applications
- Try reducing video duration/FPS

---

## System Requirements

### Minimum
- **OS**: Windows 7+, macOS 10.9+, Linux (any modern distribution)
- **Python**: 3.7+
- **RAM**: 512MB available
- **Storage**: 50MB for application + space for image cache

### Recommended
- **OS**: Windows 10+, macOS 11+, Ubuntu 20.04+
- **Python**: 3.9+
- **RAM**: 2GB available
- **Storage**: 1GB+ for larger projects
- **CPU**: Multi-core for faster rendering

---

## Uninstall

Since this is a portable application:
1. Close the application
2. Delete the `crash-faces-studio` folder
3. (Optional) Remove any created video files or cache folders

---

## Getting Help

### Check Installation
```bash
python -c "import tkinter; print('✅ tkinter OK')"
python -c "import sys; print(f'✅ Python {sys.version}')"
```

### Common Commands
```bash
# Check Python version
python --version

# Test tkinter
python -m tkinter

# Run application with error output
python crash_faces_studio.py 2>&1 | tee error.log
```

### Support Resources
- **Documentation**: README.md in the project folder
- **Website**: https://crashserver.fr
- **Issues**: GitHub repository issue tracker

---

**Happy installing!** 🚀