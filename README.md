# streaming-01-getting-started
## Student Name: Lindsey Sullivan
## GitHub Link: https://github.com/LindseySully/streaming-01-getting-started
> Get started with Python for streaming analytics

Set yourself up for productivity and collaboration.
We assume no prior programming experience and that you want to 
get productive as quickly as possible.

## Prerequisites

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured)

Remember:

- **Spacing, Spelling, Capitalization**: With computers, these are critical. Always double-check!

---

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal).
```shell
git --version
python --version
python -m pip install --upgrade pip wheel
```

## Execute Utility Script (Diagnostics)

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.10.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.
1. In VS Code, open a terminal window (View / Terminal).

```shell
python util_about.py
```
---
## Sync to GitHub

### Option A: Use VS Code (Easy!)

1. On the VS Code side panel, click the source control icon (look for a blue bubble with an number in it).
1. Important! Above the Commit button, it will say "Message". 
1. You MUST include a commit message. 
1. In the commit message input box, type "initial results".
1. Click the down arrow on the blue "Commit" button to "Commit and Push" to your GitHub repo. 

Verify: Open a browser to your GitHub repo and verify the files have appeared. 
In addition to the original files, you should have one or more new files and an edited Markdown file. 
If not, return to VS Code and edit/execute files as needed. 
Then commit and push again.

Common Issue: If your computer hangs because you forgot the commit message, 
just enter your message in the top line of the file it shows in the editor.
Then click the checkmark in the upper right to close that file and save your commit message.
"Sync your changes" to push to GitHub. 

## General Recommendations and Troubleshooting

The following are general recommendations and troubleshooting tips.

### Issue: VS Code - No Source Control Icon

Suggestion: If you're in VS Code, and you don't see the Source Control icon with a blue bubble, right-click on the sidebar icons, and make sure "Source Control" is checked.  

### Issue: VS Code wants to install an extension

If VS Code suggests an extension, it's often good to go ahead and try it. 
Do a search on the extension to learn more. VS Code suggestions are usually helpful. 

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).

--
## Module Notes:
1. If the python script does not run it is best to check the default directory by utilizing the os library.
- Suggestion: Use the OS library and os.chdir(path) - this allows to set the default directory and add the absolute path