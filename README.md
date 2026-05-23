# 🔍 File Comparator Tool

A lightweight, standalone executable (`.exe`) tool built in Python for comparing files and directories to visualize differences. This tool allows you to quickly spot discrepancies between code, data, or folder structures and export the comparison results into a clean, interactive HTML format. 

**No installation required—just download and run.**

---

## 🚀 What's New in the Latest Version?

The tool has been completely overhauled from previous versions. Here are the major upgrades:

* **Directory Comparison Mode:** Recursively scan and compare entire folders. The UI displays `MODIFIED`, `LEFT_ONLY`, `RIGHT_ONLY`, and `SAME` files.
* **Diff Minimap:** A scrollable, clickable "bird's-eye view" canvas on the right edge shows red/green/yellow chunks to allow lightning-fast navigation in large files.
* **Interactive Sidebar:** A color-coded sidebar allows you to quickly click through and inspect file differences straight from the directory scan results.
* **Deep Compare Toggle:** Switch between lightning-fast metadata directory scanning or thorough content-level deep scanning.
* **File Extension Filtering:** Easily filter directory scans by extension (e.g., `*.py, *.c, *.h`) to focus only on the code you care about.
* **Paste-able Path Entries:** You can now manually paste file and folder paths directly into the UI instead of relying solely on the file browser.
* **Binary File Safeguard:** The tool now instantly detects binary files (PDFs, images, executables) and gracefully displays a "Binary files differ" message, preventing the UI from freezing.
* **Threaded Scanning:** Directory scans run on a background thread with a progress bar, keeping the GUI completely responsive.

---

## ✨ Key Features

* **Advanced Visual Diffing:** Side-by-side color-coded comparisons (Red = Deletion, Green = Addition, Yellow = Modification).
* **Modern UI & Navigation:** Sleek dark mode interface (powered by `CustomTkinter`) featuring perfectly synchronized mouse wheel scrolling across all text panes.
* **Smart Formatting:** Automatically formats `.json` files for clean comparisons and aligns `.csv` files row-by-row.
* **Multi-Format HTML Reports:** Generate shareable, self-contained HTML diff reports for individual files, or comprehensive summary reports for entire directory structures.
* **Zero Configuration:** Packaged as a standalone Windows executable. No Python installation, external libraries, or setup required.

---

## 📂 Supported File Types

| Category | Extensions / Formats |
| :--- | :--- |
| **Data Formats** | `.json`, `.csv` |
| **Plain Text** | `.txt`, `.md`, `.log` |
| **Source Code** | `.c`, `.py`, `.js`, `.java`, `.cpp`, `.html`, `.css`, `.sh`, and more |

---

## 🏁 Getting Started

### Prerequisites
* Windows OS (provided as a `.exe` file).
* *No Python runtime or external dependencies are required.*

### Installation & Usage
1. Go to the **Releases** section of this GitHub repository.
2. Download the `FileComparator_V.exe` file.
3. Double-click the downloaded executable to launch the tool.
4. Select **File Mode** or **Directory Mode**.
5. Browse for or paste the paths for your **Source** (Left) and **Target** (Right).
6. *(Optional)* Apply file extension filters or toggle Deep Compare for directory scans.
7. Click **Compare** to view the differences.
8. Click **Export to HTML** to save the formatted results locally for sharing or archiving.

---

## 🛠️ Roadmap (Future Enhancements)

I am continuously working to improve this tool. Upcoming features include:
- [ ] **Increased number of supported file format:** Expand capabilities for different binary format files.

---

## 📄 License

This project is licensed under the **MIT License**.
