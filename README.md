# IntelliJ IDEA Key Bindings for Visual Studio Code

[![Build Status](https://travis-ci.org/kasecato/vscode-intellij-idea-keybindings.svg?branch=master)](https://travis-ci.org/kasecato/vscode-intellij-idea-keybindings) [![License: MIT](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE.md) [![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/k--kato.intellij-idea-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings) [![Install](https://vsmarketplacebadge.apphb.com/installs-short/k--kato.intellij-idea-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings)

Port of IntelliJ IDEA key bindings for VS Code. Includes keymaps for popular JetBrains products like IntelliJ Ultimate, WebStorm, PyCharm, PHP Storm, etc.

## Usage


### Editing

 macOS | Feature | Supported
------|---------|----------
 ctrl+space | Basic code completion (the name of any class, method or variable) | ✅
 ctrl+shift+space | Smart code completion (filters the list of methods and variables by expected type) | N/A
 cmd+shift+enter | Complete statement | ✅
 cmd+p | Parameter info (within method call arguments) | ✅
 ctrl+j | Quick documentation lookup | ✅
 shift+f1 | External Doc | N/A
 cmd+mouseover | Brief Info | N/A
 cmd+f1 | Show descriptions of error or warning at caret | ✅
 cmd+n | Generate code... (Getters, Setters, Constructors, hashCode/equals, toString) | ✅
 ctrl+o | Override methods | N/A
 ctrl+i | Implement methods | N/A
 cmd+alt+t | Surround with... (if..else, try..catch, for, synchronized, etc.) | N/A
 cmd+/ | Comment/uncomment with line comment | ✅
 cmd+numpad_divide | Comment/uncomment with line comment | ✅
 cmd+alt+/ | Comment/uncomment with block comment | ✅
 cmd+alt+numpad_divide | Comment/uncomment with block comment | ✅
 alt+up | Select successively increasing code blocks | ✅
 alt+down | Decrease current selection to previous state | ✅
 ctrl+shift+q | Context info | N/A
 alt+enter | Show intention actions and quick-fixes | ✅
 cmd+alt+l | Reformat code | ✅
 cmd+alt+l | Reformat selected code | ✅
 ctrl+alt+o | Optimize imports | N/A
 ctrl+alt+i | Auto-indent line(s) | N/A
 tab | Indent selected lines | N/A
 shift+tab | Unindent selected lines | N/A
 cmd+x | Cut current line or selected block to clipboard | ✅
 cmd+delete | Cut current line or selected block to clipboard | ✅
 cmd+c | Copy current line or selected block to clipboard | ✅
 cmd+v | Paste from clipboard | ✅
 cmd+shift+v | Paste from recent buffers... | N/A
 cmd+d | Duplicate current line or selected block | ✅
 cmd+backspace | Delete line at caret | ✅
 ctrl+shift+j | Smart line join | ✅
 cmd+enter | Smart line split | ✅
 shift+enter | Start new line | ✅
 cmd+shift+u | Toggle case for word at caret or selected block | N/A
 cmd+shift+] | Select till code block end | N/A
 cmd+shift+[ | Select till code block start | N/A
 alt+delete | Delete to word end | ✅
 alt+backspace | Delete to word start | ✅
 cmd+= | Expand code block | ✅
 cmd+numpad_add | Expand code block | ✅
 cmd+- | Collapse code block | ✅
 cmd+numpad_subtract | Collapse code block | ✅
 cmd+shift+= | Expand all | ✅
 cmd+shift+numpad_add | Expand all | ✅
 cmd+shift+- | Collapse all | ✅
 cmd+shift+numpad_subtract | Collapse all | ✅
 cmd+w | Close active editor tab | ✅
 ctrl+g | Add selection for Next Occurrence | ✅
 ctrl+shift+g | Unselect Occurrence | ✅
 shift+alt+down | Move Line Down | ✅
 shift+alt+up | Move Line Up | ✅

### Search/Replace

 macOS | Feature | Supported
------|---------|----------
 shift shift | Search everywhere | N/A
 cmd+f | Find | ✅
 cmd+g | Find next | ✅
 cmd+shift+g | Find previous | ✅
 cmd+r | Replace | ✅
 cmd+shift+f | Find in path | ✅
 cmd+shift+r | Replace in path | ✅
 cmd+shift+s | Search structurally (Ultimate Edition only) | N/A
 cmd+shift+m | Replace structurally (Ultimate Edition only) | N/A

### Usage Search

 macOS | Feature | Supported
------|---------|----------
 alt+f7 | Find usages | ✅
 alt+cmd+f7 | Show usages | ✅
 cmd+f7 | Find usages in file | N/A
 cmd+shift+f7 | Highlight usages in file | N/A
 cmd+alt+f7 | Show usages | N/A

### Compile and Run

 macOS | Feature | Supported
------|---------|----------
 cmd+f9 | Make project (compile modifed and dependent) | ✅
 cmd+shift+f9 | Compile selected file, package or module | N/A
 ctrl+alt+r | Select configuration and run | ✅
 ctrl+alt+d | Select configuration and debug | ✅
 ctrl+r | Run | N/A
 ctrl+d | Debug | ✅
 ctrl+shift+r | Run context configuration from editor | N/A
 ctrl+shift+r | Debug context configuration from editor | N/A

### Debugging

 macOS | Feature | Supported
------|---------|----------
 f8 | Step over | ✅
 f7 | Step into | ✅
 shift+f7 | Smart step into | N/A
 shift+f8 | Step out | ✅
 alt+f9 | Run to cursor | ✅
 alt+f8 | Evaluate expression | ✅
 alt+f8 | Evaluate expression (selection) | ✅
 cmd+alt+r | Resume program | ✅
 cmd+f8 | Toggle breakpoint | ✅
 cmd+shift+f8 | View breakpoints | ✅

### Navigation

 macOS | Feature | Supported
------|---------|----------
 cmd+o | Go to class | ✅
 cmd+shift+o | Go to file | ✅
 cmd+alt+o | Go to symbol | ✅
 ctrl+left | Go to previous editor tab | ✅
 shift+cmd+[ | Go to previous editor tab | ✅
 ctrl+right | Go to next editor tab | ✅
 shift+cmd+] | Go to next editor tab | ✅
 f12 | Go back to previous tool window | N/A
 escape | Go to editor (from tool window) | N/A
 shift+escape | Hide active or last active window (Sidebar) | ✅
 shift+escape | Hide active or last active window (Output) | ✅
 shift+escape | Hide active or last active window (Problems) | ✅
 shift+escape | Hide active or last active window (Debug Console) | ✅
 shift+escape | Hide active or last active window (Terminal) | ✅
 shift+escape | Hide active or last active window (Panel) | N/A
 cmd+shift+f4 | Close active run/messages/find/... tab | N/A
 cmd+l | Go to line | ✅
 cmd+e | Recent files popup | ✅
 cmd+alt+left | Navigate back | ✅
 cmd+[ | Navigate back | ✅
 cmd+alt+right | Navigate forward | ✅
 cmd+] | Navigate forward | ✅
 cmd+shift+backspace | Navigate to last edit location | ✅
 alt+f1 | Select current file or symbol in any view | N/A
 cmd+b | Go to declaration | ✅
 cmd+alt+b | Go to implementation(s) | ✅
 alt+space | Open quick definition lookup | ✅
 cmd+y | Open quick definition lookup | ✅
 ctrl+shift+b | Go to type declaration | ✅
 cmd+u | Go to super-method/super-class | N/A
 ctrl+up | Go to previous method | N/A
 ctrl+down | Go to next method | N/A
 cmd+] | Move to code block end | N/A
 cmd+[ | Move to code block start | N/A
 cmd+f12 | File structure popup | ✅
 ctrl+h | Type hierarchy | N/A
 cmd+shift+h | Method hierarchy | N/A
 ctrl+alt+h | Call hierarchy | N/A
 f2 | Next highlighted error | ✅
 shift+f2 | Previous highlighted error | ✅
 f4 | Edit source | ✅
 cmd+down | View source | ✅
 shift+alt+down | Move Statement Down | ✅
 shift+alt+up | Move Statement Up | ✅
 alt+home | Show navigation bar | N/A
 f3 | Toggle bookmark | N/A
 alt+f3 | Toggle bookmark with mnemonic | N/A
 ctrl+0 | Go to numbered bookmark | N/A
 cmd+f3 | Show bookmarks | N/A
 ctrl+alt+shift+down | Next Change | ✅
 ctrl+alt+shift+up | Previous Change | ✅

### Refactoring

 macOS | Feature | Supported
------|---------|----------
 f5 | Copy | N/A
 f6 | Move | N/A
 cmd+delete | Safe Delete | N/A
 shift+f6 | Rename | ✅
 shift+f6 | Rename (File) | ✅
 cmd+f6 | Change Signature | N/A
 cmd+alt+n | Inline | N/A
 cmd+alt+m | Extract Method | ✅
 cmd+alt+v | Extract Variable | ✅
 cmd+alt+f | Extract Field | N/A
 cmd+alt+c | Extract Constant | N/A
 cmd+alt+p | Extract Parameter | N/A

### VCS/Local History

 macOS | Feature | Supported
------|---------|----------
 cmd+k | Commit project to VCS | ✅
 cmd+shift+k | Push commits to VCS | ✅
 cmd+t | Update project from VCS | ✅
 alt+shift+c | View recent changes | N/A
 ctrl+v | ‘VCS’ quick popup | ✅

### Live Templates

 macOS | Feature | Supported
------|---------|----------
 cmd+alt+j | Surround with Live Template | N/A
 cmd+j | Insert Live Template | N/A

### General

 macOS | Feature | Supported
------|---------|----------
 cmd+0 | Activate Messages window (Problems) | ✅
 cmd+numpad0 | Activate Messages window (Problems) | ✅
 cmd+1 | Open corresponding tool window (Explorer) | ✅
 cmd+numpad1 | Open corresponding tool window (Explorer) | ✅
 cmd+1 | Close corresponding tool window (Explorer) | ✅
 cmd+numpad1 | Close corresponding tool window (Explorer) | ✅
 cmd+3 | Open corresponding tool window (Search) | ✅
 cmd+numpad3 | Open corresponding tool window (Search) | ✅
 cmd+3 | Close corresponding tool window (Search) | ✅
 cmd+numpad3 | Close corresponding tool window (Search) | ✅
 cmd+5 | Open corresponding tool window (Debug) | ✅
 cmd+numpad5 | Open corresponding tool window (Debug) | ✅
 cmd+5 | Close corresponding tool window (Debug) | ✅
 cmd+numpad5 | Close corresponding tool window (Debug) | ✅
 cmd+9 | Open corresponding tool window (Git) | ✅
 cmd+numpad9 | Open corresponding tool window (Git) | ✅
 cmd+9 | Close corresponding tool window (Git) | ✅
 cmd+numpad9 | Close corresponding tool window (Git) | ✅
 cmd+s | Save all | ✅
 cmd+alt+y | Synchronize | ✅
 ctrl+cmd+f | Toggle full screen mode | ✅
 cmd+shift+f12 | Toggle maximizing editor | ✅
 alt+shift+f | Add to Favorites | N/A
 alt+shift+i | Inspect current file with current profile | N/A
 ctrl+\` | Quick switch current scheme | ✅
 cmd+, | Open Settings dialog | ✅
 cmd+numpad_separator | Open Settings dialog | ✅
 cmd+; | Open Project Structure dialog | ✅
 shift+cmd+a | Find Action | ✅
 ctrl+tab | Switch between tabs and tool window | ✅

### Custom

 macOS | Feature | Supported
------|---------|----------
 f7 | Next difference | ✅
 shift+f7 | Previous difference | ✅
 alt+cmd+enter | Start new line before current | ✅
 shift+cmd+enter | Start new line | ✅
 alt+f12 | Opens and focuses corresponding tool window (Terminal) | ✅
 alt+f12 | Close corresponding tool window (Terminal) | ✅
 ctrl+cmd+g | Sublime Text style multiple selections | ✅
 shift+cmd+[ | Select previous tab (Terminal) | ✅
 shift+cmd+] | Select next tab (Terminal) | ✅
 alt+tab | Goto next splitter | ✅
 shift+alt+tab | Goto previous splitter | ✅
 enter | Open Highlighted File (Explorer) | ✅
 alt+home | Jump to Navigation Bar | ✅

### Custom

 macOS | Feature | Supported
------|---------|----------
 f7 | Next difference | ✅
 shift+f7 | Previous difference | ✅
 alt+cmd+enter | Start new line before current | ✅
 shift+cmd+enter | Start new line | ✅
 alt+f12 | Opens and focuses corresponding tool window (Terminal) | ✅
 alt+f12 | Close corresponding tool window (Terminal) | ✅
 ctrl+cmd+g | Sublime Text style multiple selections | ✅
 shift+cmd+[ | Select previous tab (Terminal) | ✅
 shift+cmd+] | Select next tab (Terminal) | ✅
 alt+tab | Goto next splitter | ✅
 shift+alt+tab | Goto previous splitter | ✅
 enter | Open Highlighted File (Explorer) | ✅
 alt+home | Jump to Navigation Bar | ✅
 shift+cmd+c | Copy paths | ✅

## Installation

1. Install Visual Studio Code 1.30.2 or higher
1. Launch Code
1. From the extension view `Cmd`-`Shift`-`X` (macOS)
1. Search and Choose the extension `Intellij IDEA Keybindings`
1. Reload Visual Studio Code


## Contributing to the Code

Clone a copy of the repo:

```
git clone https://github.com/kasecato/vscode-intellij-idea-keybindings.git
```


### Building the code

First, install the package dependencies:

```
npm install
```

Now you can compile the code:

1. Launch Code
1. Edit **`src/package-with-comment.json`** (**NOT `package.json`**)
1. Run Build Task `Cmd`-`Shift`-`B` (macOS)
1. Run Command Markdown Generator `node src/tool/gene-keybind-markdown.js`
1. Paste the Command Markdown to `README.md`

After the initial compile, the source files will be watched and recompiled
when changes are saved.


## Contributors

* [@brianegan](https://github.com/brianegan)
* [@whinc](https://github.com/whinc)
* [@HSAR](https://github.com/HSAR)
* [@mastersimon](https://github.com/mastersimon)
* [@thekalinga](https://github.com/thekalinga)
* [@joaomoreno](https://github.com/joaomoreno)
* [@kasperpeulen](https://github.com/kasperpeulen)
* [@waderyan](https://github.com/waderyan)
* [@megha-n-bodke](https://github.com/megha-n-bodke)
* [@gregbacchus](https://github.com/gregbacchus)
* [@acim](https://github.com/acim)
* [@skysteve](https://github.com/skysteve)
* [@spik3s](https://github.com/spik3s)
* [@AlexAkhremenko](https://github.com/AlexAkhremenko)
* [@rtconner](https://github.com/rtconner)
* [@pavilion](https://github.com/pavilion)
* [@xc1427](https://github.com/xc1427)
* [@michielboekhoff](https://github.com/michielboekhoff)
* [@thekalinga](https://github.com/thekalinga)
* [@andrewda](https://github.com/andrewda)
* [@deftomat](https://github.com/deftomat)
* [@rinormaloku](https://github.com/rinormaloku)
* [@covertbert](https://github.com/covertbert)
* [@flashsphere](https://github.com/flashsphere)
* [@kroleg](https://github.com/kroleg)


## License

This extension is [licensed under the MIT License](LICENSE.md).


## References

1. Source code, Resharper 9 Keybindings, https://marketplace.visualstudio.com/items?itemName=ms-vscode.resharper9-keybindings
1. IntelliJ IDEA DEFAULT KEYMAP, https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf
1. Key Bindings for Visual Studio Code, https://code.visualstudio.com/Docs/customization/keybindings
1. Integrate with External Tools via Tasks, https://code.visualstudio.com/docs/editor/tasks#_autodetecting-gulp-grunt-and-jake-tasks
1. gulp-strip-json-comments, https://www.npmjs.com/package/gulp-strip-json-comments
1. Icon, vscode-vs-keybindings, https://github.com/rebornix/vscode-vs-keybindings/blob/master/visualstudio-keyboard.svg
