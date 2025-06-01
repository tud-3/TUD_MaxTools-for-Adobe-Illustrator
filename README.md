# TUD MaxTools for Adobe Illustrator

![Illustrator Script](https://img.shields.io/badge/Adobe%20Illustrator-CC%20%7C%20CS4%2B-orange.svg?style=for-the-badge&logo=adobeillustrator&logoColor=white)
![Language](https://img.shields.io/badge/Language-ExtendScript%20(JavaScript)-blue.svg?style=for-the-badge&logo=javascript&logoColor=white)
![Version](https://img.shields.io/badge/Version-2.0-lightgreen.svg?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple.svg?style=for-the-badge)

---

## 🚀 Overview

**TUD MaxTools** is a powerful ExtendScript for Adobe Illustrator designed to significantly enhance your productivity when working with multi-artboard documents. This script automates the process of adding dynamic text elements like page numbers, current dates, timestamps, and file-specific information (full path or just file name) to all artboards in your active document.

Its intuitive user interface allows you to precisely control placement (top/bottom), alignment (left/center/right), and margins, giving you perfect control over the final output. While primarily built for page numbering, its flexible text insertion capabilities make it ideal for adding any consistent information across your artboards, saving you valuable time and ensuring project consistency.

---

## ✨ Features

* **Dynamic Text Insertion:** Automatically inserts:
    * `*page*`: Current artboard number (e.g., "1", "2")
    * `*pages*`: Total number of artboards (e.g., "10")
    * `*date*`: Current date (MM/DD/YYYY)
    * `*time*`: Current time (HH:MM AM/PM)
    * `*fname*`: Full file path and name (e.g., `C:\Users\...\document.ai`)
    * `*file*`: Only the file name (e.g., `document.ai`)
* **Customizable Placement:** Choose between **Top** or **Bottom** placement for your text.
* **Flexible Alignment:** Align text to the **Left**, **Center**, or **Right** of each artboard.
* **Adjustable Margins:** Define the exact distance from the artboard edge in inches.
* **Dedicated Layer:** Creates a new layer named "Page Numbers" for easy organization and toggling visibility of the added text.
* **User-Friendly Interface:** An interactive dialog box provides a clear and simple way to configure settings.
* **Cross-Version Compatibility:** Works with Adobe Illustrator CS4, CS5, and later versions.

---

## ⚙️ Installation

1.  **Download the Script:**
    * Download the `TUD_MaxTools_for_Adobe_Illustrator.jsx` file.
    * **Important:** Ensure your browser doesn't add a `.txt` extension if you copy-paste the code. Save it exactly as `.jsx`.

2.  **Place the Script:**
    * Copy the `.jsx` file into Adobe Illustrator's `Scripts` folder.
    * **Windows:**
        * `C:\Program Files\Adobe\Adobe Illustrator [Your Version]\Presets\[Your Language]\Scripts`
        * (Alternatively, for user-specific scripts): `C:\Users\<Your Username>\AppData\Roaming\Adobe\Adobe Illustrator [Your Version]\Presets\[Your Language]\Scripts`
    * **macOS:**
        * `/Applications/Adobe Illustrator [Your Version]/Presets/[Your Language]/Scripts`
        * (Alternatively, for user-specific scripts): `~/Library/Application Support/Adobe/Adobe Illustrator [Your Version]/[Your Language]/Scripts`

3.  **Restart Illustrator:** Close and reopen Adobe Illustrator to ensure the script appears in the menu.

---

## 🚀 How to Use

1.  **Open Your Document:** Ensure you have an Adobe Illustrator document open with at least one artboard.
2.  **Run the Script:** Go to **File > Scripts** and select `TUD_MaxTools_for_Adobe_Illustrator.jsx` from the list.
3.  **Configure Settings:**
    * **Margins:** Enter the desired margin (in inches) from the artboard edge.
    * **Location:** Choose "Top" or "Bottom" for text placement.
    * **Alignment:** Select "Left," "Center," or "Right" alignment.
    * **Text to Insert:**
        * Type your desired text (e.g., `Project Name - Page *page* of *pages*`).
        * Use the provided buttons (P, Ps, D, T, fFn, Fn) to easily insert keywords (`*page*`, `*pages*`, `*date*`, `*time*`, `*fname*`, `*file*`).
        * Click "C" to clear the text field.
4.  **Execute:** Click the "Ok" button.

The script will automatically generate text frames on a new "Page Numbers" layer, adding the specified information to each artboard.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements, find bugs, or want to add new features, please feel free to open an issue or submit a pull request.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details (you'll need to create this file if you want to include it).

---

## 🧑‍💻 Author

**Thulana Upek Damsiha Dalpathadu**

---
