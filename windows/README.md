# Windsurf Application Installation (Windows)

This guide explains how to download, unzip, and install Windsurf applications on your Windows system.

## Prerequisites

-   A `.zip` file containing the Windsurf application.
-   Windows 10 or later.

## Download the Application

1.  Go to the project's **GitHub Releases page**: [https://github.com/chrisgroks/windsurf-zips/releases](https://github.com/chrisgroks/windsurf-zips/releases)
2.  Find the latest release (or the version you wish to install).
3.  Download the appropriate `.zip` file for Windows (e.g., `Windsurf-Windows-x64-1.9.2.zip`). Save it to your `Downloads` folder or another convenient location.

## Installation Steps

1.  **Locate the ZIP file:** Open File Explorer and navigate to where you saved the downloaded `.zip` file.

2.  **Unzip the file:**
    *   Right-click on the `.zip` file.
    *   Select "Extract All...".
    *   Choose a destination folder for the extracted files. For example, you can extract it to a temporary folder on your Desktop or directly to your desired installation location (see next step).
    *   Click "Extract". This will create a new folder containing the application files (e.g., a folder named `Windsurf`).

3.  **Move the Application Folder (Recommended):**
    *   Once extracted, you will have a folder containing the Windsurf application (e.g., `Windsurf.exe` and other supporting files/folders).
    *   It's recommended to move this entire folder to a permanent location. Good options include:
        *   **User-specific installation (no admin rights needed):** `C:\Users\<YourUserName>\AppData\Local\Programs\Windsurf` (You may need to create the `Windsurf` subfolder. Replace `<YourUserName>` with your actual Windows username).
        *   **System-wide installation (admin rights may be needed):** `C:\Program Files\Windsurf` (You may need to create the `Windsurf` subfolder).
        *   **Portable use:** You can also run the application directly from the extracted folder in any location (e.g., `Documents`, a dedicated `Applications` folder you create, or even a USB drive).

4.  **Create a Shortcut (Optional):**
    *   Navigate into the folder where you placed the Windsurf application.
    *   Find the main application executable (e.g., `Windsurf.exe`).
    *   Right-click on `Windsurf.exe` and select "Send to" > "Desktop (create shortcut)".
    *   You can also pin it to your Start Menu or Taskbar by right-clicking the `.exe` and choosing "Pin to Start" or "Pin to taskbar".

5.  **Launch the Application:**
    *   Double-click the `Windsurf.exe` file or use the shortcut you created.

## Updates

We update Windsurf frequently to bring you the latest features and improvements. 

When a new version is available, a popup notification will appear in the top right corner of the application prompting you to update.

## Troubleshooting

*   **Windows SmartScreen:** Windows SmartScreen might prevent an unrecognized app from running. If you see a message like "Windows protected your PC":
    1.  Click "More info".
    2.  Click "Run anyway".
*   **Antivirus Software:** Some antivirus programs might flag new or unrecognized applications. If this happens, you may need to temporarily disable your antivirus or add an exception for `Windsurf.exe`.
*   **Missing Dependencies (e.g., .NET, VC++ Redistributable):** If the application fails to start and gives an error about missing `.dll` files, you might need to install a specific version of the .NET Framework or Microsoft Visual C++ Redistributable. The application's documentation (if available beyond this README) should specify these requirements.

That's it! Your Windsurf application should now be ready to use on Windows.
