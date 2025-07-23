# Excel Summary Tool

A high-performance desktop application for comparing .fac files and generating detailed Excel summaries of differences.

## 🚀 Features

- **75x Performance Optimization** - Dramatically faster than traditional file comparison methods
- **Professional Desktop GUI** - User-friendly interface with real-time progress tracking
- **Batch Processing** - Compare multiple file pairs automatically
- **Comprehensive Logging** - Detailed processing logs with timestamps
- **Smart File Detection** - Only creates summary files when differences are found
- **Cross-Platform** - Works on Windows, Mac, and Linux

## 📥 Quick Start

### Option 1: Download Executable (No Python Required)
1. Go to [Releases](https://github.com/CapnBloodBeard/excel-summary-script/releases)
2. Download `gui_app.exe`
3. Double-click to run - no installation needed!

### Option 2: Run from Source
```bash
git clone https://github.com/CapnBloodBeard/excel-summary-script.git
cd excel-summary-script
python gui_app.py
```

## 🎯 How It Works

The tool compares two .fac files or folders containing .fac files and generates Excel summaries showing:

- **New Lines** - Data present in File 2 but not in File 1
- **Removed Lines** - Data present in File 1 but not in File 2  
- **Changed Values** - Side-by-side comparison showing `old_value -> new_value`
- **Identical Files** - Logged but no summary file created (saves space)

## 🖥️ User Interface

The desktop application provides:

1. **File/Folder Location 1** - Select source files or folder
2. **File/Folder Location 2** - Select comparison files or folder  
3. **Summary Folder Name** - Choose output location
4. **Real-time Progress** - Live updates during processing
5. **Processing Log** - Detailed information about each file comparison

## 📊 Performance

- **Original Processing**: <10ms per row
- **Optimized Processing**: ~0.4ms per 

## 🛠️ Technical Details

### Core Technologies
- **Python 3.10+** - Main programming language
- **pandas** - Data manipulation and analysis
- **openpyxl** - Excel file creation and editing
- **numpy** - High-performance array operations
- **tkinter** - Cross-platform GUI framework

### Key Optimizations
- **Batch Excel Operations** - Eliminates repeated file I/O
- **Efficient Set Operations** - Fast data matching and filtering
- **Optimized Memory Usage** - Streaming data processing
- **Smart Caching** - Reduces redundant calculations


```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you encounter any issues:

1. Check the processing log for detailed error messages
2. Ensure your .fac files are properly formatted
3. Verify file paths are correct and accessible
4. Create an issue on GitHub with error details

## 🏆 Acknowledgments

- Built for high-performance financial data comparison
- Optimized for large-scale batch processing
- Designed with user experience in mind

---

## 👥 Development Stats

- **Human coded**: 55%~
- **AI coded**: 45%~
- **AI Optimized**: 100% (i was lazy)

**Made with ❤️ for efficient data analysis**
