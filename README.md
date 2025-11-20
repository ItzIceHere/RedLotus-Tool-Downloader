# 🔥 RedLotus Downloader - Official Download Hub

This tool serves as the central hub for all official tools approved by RedLotus.

## 📺 Presentation Clip

You can watch a brief demonstration of the tool here: [https://youtu.be/RZC7H5V1plo](https://youtu.be/RZC7H5V1plo)

---

### ⚙️ Interface & Features

The tool consists of **3 main tabs**:

1.  **Hub Tab**: Manually select the tool categories to download (Spok, Nirsoft, Zimmerman, Other).
2.  **Presets Tab** (Central): Download predefined file groups with a unified progress bar.
    * **Download All**: Downloads all tools from all categories.
    * **Quick SS**: Downloads a quick selection of essential tools.
    * **Full SS**: Downloads the full suite of tools.
3.  **Status Tab**: View the detailed progress of downloads initiated from the Hub Tab.

---

### 🔗 Quick Links (Footer)

Three quick buttons are available at the bottom of the window:

* **Open Folder**: Opens the save folder for all downloaded files (`C:\SS1`).
* **Discord**: Opens the invitation to the official RedLotus Discord server.
* **Guides**: Opens the official RedLotus online guide.

> 📝 **Guide Utility**: Provides easy access to strings, commands, and PowerShell scripts, and increases **transparency** on how specific tools and scripts work (improving SSer/Player communication).

---

### 🚀 Technical Optimizations

Several optimizations have been implemented to ensure better speed and efficiency:

* **Multithreading (Parallel Downloads)**: Allows downloading up to **4 files simultaneously** instead of one at a time, drastically reducing overall download times.
* **Connection Reuse (Keep-Alive)**: Keeps the connection to the server open, avoiding the overhead of constantly reconnecting for each individual file.
* **Increased Buffer (64KB)**: Uses a larger download buffer (64KB instead of the standard 8KB) to reduce CPU usage and disk I/O operations.

---

### 🛡️ Future Proof

The tool is built strategically:
Download links are **not hard-coded** within the executable (EXE) itself, but are saved in an **online tool list**.

This design allows us to **change, add, or remove** any tool from the download lists for every button in just a few seconds, ensuring that the current EXE file will continue to function seamlessly with all future updates.