 ClaudeAssistant

ClaudeAssistant is a Python utility designed to help Unity developers quickly generate an enhanced tree structure of their project directory along with extracting and summarizing critical project settings and information. This script is particularly useful for managing large Unity projects where keeping track of all files, settings, and assets can become cumbersome.

## Features

- **Project Tree Generation:** Creates a comprehensive tree-like structure of your Unity project, excluding unnecessary directories.
- **Build Settings:** Summarizes the build settings of your project.
- **Package Versions:** Provides detailed information on the versions of packages used in your project.
- **Project & Quality Settings:** Extracts and displays key settings from your Unity project files.
- **Scene Hierarchies:** Lists and provides a summary of the hierarchy of all Unity scenes in your project.
- **Unity Version:** Identifies and displays the Unity version used in the project.
- **Git Information:** Shows the current Git branch and the latest commit details.
- **Asset Counts:** Categorizes and counts the assets in your project, such as scenes, prefabs, materials, textures, and scripts.

## Usage

To use ClaudeAssistant, simply run the script in your Unity project directory. The script will generate a detailed summary and save it to a timestamped text file in the same directory.

```bash
python ClaudeAssistant.py --root-dir /path/to/your/unity/project
