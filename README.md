# BPM Automator Script for Apple Music

This AppleScript allows you to quickly set the BPM (Beats Per Minute) metadata for selected tracks in the Apple Music app and updates the track name to include the BPM value. If the track name already contains a BPM value at the start (e.g., "120 - Song Title"), it will be replaced with the new BPM.

## Features
- Prompts for a BPM value and applies it to all selected tracks in Apple Music.
- Updates the track name to include the BPM at the start (e.g., "128 - Song Title").
- If the track name already starts with a BPM, it replaces it with the new value.
- Notifies you when the BPM is set for each track.

## How to Use

### 1. Download the Automator Workflow
1. Go to the latest release from [Github Releases](https://github.com/cjameslok/BPM-Automation/releases)
2. Scroll down to Assets and download `BPM_Automation.workflow.zip`

### 2. Install the Workflow
1. Double-click the `BPM_Automation.workflow` file on your Mac.
2. Quick Action Installer will open and prompt you to install the workflow as a Quick Action.
3. System Settings should open automatically to **Services**, in that case go to set 3.4

### 3. Assign a Keyboard Shortcut
1. Open **System Settings** (or **System Preferences**) on your Mac.
2. Go to **Keyboard > Keyboard Shortcuts**.
3. Select **Services** (or **Quick Actions**).
4. Find your new workflow in the list. Expand **General** and it should be called `BPM_Automation`
5. Click on it and assign a custom keyboard shortcut (e.g., `⌥⌘B`).

### 4. Usage
1. In Apple Music, select one or more tracks.
2. Use your assigned keyboard shortcut (or run the Quick Action from the Services menu).
3. Enter the desired BPM when prompted.
4. The script will update the BPM metadata and rename the tracks accordingly.

## Troubleshooting
- Make sure you have granted Automator and Apple Music the necessary permissions in **System Settings > Security & Privacy > Privacy > Automation**.
- The script only works if tracks are selected in Apple Music.
- Only positive integer BPM values are accepted.

## License
See the repository for license details.

---

For questions or issues, please open an issue in the repository.
