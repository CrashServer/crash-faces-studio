# Crash/Faces Studio

A tool used that randomize jpg > put in  movie format and allows for some freeze frame and black & white
## Quick Start

### Prerequisites
- Python 3.7 or higher
- tkinter (usually included with Python)

python crash_faces_studio.py


### Usage
1. **Select Images** - Click "Browse" to choose a folder with JPG/PNG images
2. **Configure Settings** - Set duration, FPS, and image timing

## Configuration Options

### Basic Settings
- **Video Duration**: Total length of output video (1-300 seconds)
- **Frame Rate**: Video FPS (1-60 fps, recommended: 24-30)
- **Image Duration**: How long each image appears (0.1-10 seconds)

### Advanced Timing
- **Freeze Frame Chance**: Probability of freeze effects (0-100%)
- **Freeze Duration Range**: Multiplier range for freeze frames (1x-20x)
- **Random Seed**: For reproducible results (optional)

### Animation Style
- **Black & White**: Convert images to grayscale
- **Use Cache**: Speed up processing with image cache (have to be rendered a first time)
- **Advanced Timing**: Enable freeze frame effects

## Timeline Legend

## File Requirements

### Supported Formats
- **Images**: JPG, JPEG, PNG
- **Output**: MP4 video format

## Advanced Usage

## Troubleshooting

### Common Issues

**"No images found"**
- Check that your folder contains JPG, JPEG, or PNG files
- Verify file permissions and folder access

**"Timeline not updating"**
- Ensure you have selected a valid image folder
- Try adjusting settings to trigger a refresh

**Interface appears broken**
- Ensure you're using Python 3.7+
- Try running: `python -m tkinter` to test tkinter installation

### Performance Tips
- Use the cache option for faster processing
- Reduce image count for smoother timeline updates


## License

MIT License - see LICENSE file for details

## Credits

**Created by**: crashserver.fr  
**Version**: 1.0.0  
**Python**: 3.7+  

## Support

- **Website**: https://crashserver.fr


