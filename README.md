# File Integrity Monitor

This script provides a way to monitor a folder for changes. It maintains a baseline of file hashes, and then periodically compares these hashes with the current hashes of the files.

If a file has been added or removed, or if a file has been modified (i.e., its hash has changed), the script will notify the user.

To use this script, you need to provide the path to the folder you want to monitor.

This script is useful for detecting unauthorized modifications to important files, such as configuration files or software binaries.

## How to Use

To use this script, follow these steps:

1. Clone this repository.
2. Open PowerShell and navigate to the directory containing the script.
3. Run the script using the command `.\FileIntegrityMonitor.ps1`.
4. When prompted, enter 'A' to collect a new baseline, or 'B' to begin monitoring files with the saved baseline.

The script will continuously monitor the files in the specified folder. To stop the script, press `Ctrl+C` in the PowerShell window.

## Potential Improvements

1. Support for additional file hashing algorithms.
2. Better error handling and logging capabilities.
3. Ability to specify which file extensions or types of files to monitor.
4. Option to ignore certain files or directories, such as those with temporary files.
5. Ability to execute custom actions when specific events are detected, such as sending an email notification.

By implementing these improvements, this script could provide a more robust and customizable solution for monitoring file integrity.

## Conclusion

This script offers a straightforward way to monitor a folder for changes, with potential applications in system administration, security, and other fields. While there is still room for improvement, this script serves as a valuable starting point for those looking to implement a file integrity monitoring solution.
