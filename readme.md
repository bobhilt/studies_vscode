# Visual Studio Code Demo - PyHawaii 11/7/18
## Introduction:  
 
### Visual Studio to Visual Studio Code

### Visual Studio is Microsoft’s full-blown commercial IDE, evolving since VS 97, VS 6.0, then VS.Net in 2002, followed by Microsoft’s year naming convention to today's VS 2019. Highly developed, feature rich environment which provides a tremendous amount of help/scaffolding to build and manage projects, and coordinate teams.  If you are planning to do a lot of .Net coding, Visual Studio is your best choice.  VS is not our focus for this demo.

### Visual Studio Code (VSCode), 2015 is a cross-platform (Linux, Mac OS, Windows) code editor that can be extended with plugins to support your needs.  It is now the #1-ranked code editor [stackoverflow.com]. While it can be used as a straightforward editor, it can be extended to the point of being a pretty rich editor.  VS Code effort was led by Erich Gamma (Gang Of Four and Eclipse)

*Features:*
* Cross-platform
* Extensibility—its main feature?  1000s of packages available.
* Open source! (MIT License), source code on Github.
* Git integration
* Interactive Playground — learn and try things in a sandbox.
* Themes[cmd-k,cmd-t]
    * Dark (easier on the eyes and battery life)
        * Winter is Coming
        * Cobalt 2
        * Atom Dark
        * Monokai
    * Light
* Intellisense (context-aware auto-completion)
* Brace matching
* Snippets
* Formatting (autopep8, black, yapf)
* Code folding  ⌥⌘[ to fold or press ⌥⌘] to unfold the ranges at the current cursor position. 
* Refactoring (Extract Variable, Extract Method, and Sort Imports.)
* Support for many languages, probably including whichever you use: C, C++, Go, Powershell, R, Ruby, VB, etc, and, of course, Python. Feature support varies across languages.
* Note: defaults to opt in--collects usage data and sends it to Microsoft, (may be shared with law enforcement).  This telemetry reporting can be disabled. Useful for improving the user experience, but might not be your cup of tea.

Basics:

Navigation: The folder in which you begin vscode determines your workspace.  For security reasons, one cannot navigate to parent (including sibling-level) folders. The starting folder workspace determines your effective root.

Command Pallet (where the magic happens): Cmd-shift-P  (ctrl-shift-p or F1 on Windows)

Extensions:
Python

Settings:
Scope:
User —> All sessions unless overridden by…
Workspace: Project-specific
    python.unitTest.unittestEnabled (Other test frameworks should be disabled).

## Demo:

From your terminal, navigate to your code directory

```
mkdir pyhi_vscode
cd pyhi_vscode
code .
```
[Explore the environment a bit...]

### To get this demo and follow along:

```
Command: `Git: Clone Repository git@github.com:bobhilt/studies_vscode.git`
```

Resources: 
* Getting Started with python: https://code.visualstudio.com/docs/python/python-tutorial
* Settings: https://code.visualstudio.com/docs/getstarted/settings
* https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting
* Unit Testing: https://code.visualstudio.com/docs/python/unit-testing
* Using Git: https://code.visualstudio.com/Docs/editor/versioncontrol
* Learn and use your keyboard! https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf
    
    Shortcuts
    * Windows: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf
    *  Mac: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf
    * Linux: https://go.microsoft.com/fwlink/?linkid=832144

* Customizing keybindings/creating custom shortcuts: https://code.visualstudio.com/docs/getstarted/keybindings


Problems to resolve: 
* Upgrading pip version, SSL certificate catch-22 from vscode (works from terminal)