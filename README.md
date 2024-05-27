# HXD's YouTube GUI Downloader 📺📥

HXD's YouTube GUI Downloader is a user-friendly application to download YouTube videos in various formats using a graphical interface.

## Features

- Simple and intuitive user interface.
- Support for downloading videos with various formats and options.
- Ability to download subtitles along with videos.

## Installation

1. **Download the Executable:**   You can download the executable file (`y.exe`) for Windows from the [Releases](https://github.com/himanshuxd/HXD-yt-dlp-GUI/releases/) page.

2. **Run the Application:** Execute the downloaded `y.exe` file on your Windows system.


## How to Use the Downloader

### Displayed Formats

Once you copy a YouTube URL to your clipboard and refresh the clipboard in the application, the available formats will be displayed in the list box. Formats are categorized into three sections:

1. **Audio Only + M4A**: Lists formats that contain only audio tracks, specifically in M4A format.
2. **Video Only + MP4**: Lists formats that contain only video tracks, specifically in MP4 format.
3. **Other Formats**: Lists any other available formats.

### Choosing Downloads

1. **Refresh Clipboard**: Click the `Refresh Clipboard` button to load the current URL from your clipboard.
2. **View Formats**: The available formats will be displayed in the list box categorized as mentioned above after `yt-dlp` fetches them.
3. **Select Formats**: Click on the desired formats in the list box to select them. You can select multiple formats to get the output you desire whether it be `webm` or `mkv` or `mp4`.

### Available Options

- **Refresh Clipboard**: Refreshes the clipboard to check for a new URL.
- **Refresh Program**: Clears the current selections and output. Refreshes application for new URL download.
- **Execute Command**: Executes a custom command entered in the command entry box.
- **Just Download It**: Downloads the video using the default format.
- **Download with Subtitles Embedded**: Downloads the video with subtitles embedded.
- **Download Selected Formats**: Downloads the video in the selected formats.

## Steps to Download

1. **Launch the Application**: Open the GUI application `y.exe` to launch.
2. **Copy URL**: Copy the desired YouTube video URL to your clipboard.
3. **Refresh Clipboard**: Click the `Refresh Clipboard` button to load the URL.
4. **Select Formats**: In the list box, select the formats you want to download.
5. **Choose Download Option**:
    - **Just Download It**: Click this button to download the video in the default format.
    - **Download with Subtitles Embedded**: Click this button to download the video with embedded subtitles.
    - **Download Selected Formats**: Click this button to download the video in the selected formats.

## Example Workflow

1. **Copy URL**: Copy `https://www.youtube.com/watch?v=dQw4w9WgXcQ` to your clipboard.
2. **Open Application**: Launch the downloader application.
3. **Refresh Clipboard**: Click `Refresh Clipboard` to load the URL.
4. **View Formats**: Observe the formats listed in the list box.
5. **Select Formats**: Click on `140 m4a` under "Audio Only + M4A" and scroll and click on `137 mp4` under "Video Only + MP4".
6. **Download**: Click "Download Selected Formats".

## Notes

- Ensure `yt-dlp` is installed and available in your system's PATH.
- Downloads are saved to `%userprofile%\Downloads\youtube`.

## Dependencies

This application requires the following dependencies to be installed:

- [Python](https://www.python.org/downloads/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) 



## Disclaimer

This application is provided as-is, without any warranty or liability. The author is not liable for any harm caused by the usage of this application. Users are advised to use it at their own risk.

## License

This project is licensed under the [MIT License](https://github.com/himanshuxd/HXD-yt-dlp-GUI/blob/main/LICENSE).
