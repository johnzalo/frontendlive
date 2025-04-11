# Live HTML/CSS/JS Trainer

A simple, single-file, coding editor for learning and experimenting with HTML, CSS, and JavaScript.


![Image Alt](https://github.com/johnzalo/frontendlive/blob/6cf4a1ca570a157800b5c1e134dad8dd68160798/screen1.png)

## Key Features

*   **Live Preview:** Instantly see the results of your HTML, CSS, and JavaScript code rendered in a preview pane.
    *   Syntax highlighting.
    *   Code folding (collapsible code sections via gutter arrows or `Ctrl+Q`).
*   **Customizable Interface (Ctrl+M):**
    *   **Theme Selection:** Choose from 50 different CodeMirror themes (light and dark) to suit your preference.
    *   **Layout Adjustment:** Use a slider to dynamically change the width split (0-100%) between the code editors and the live preview pane.
*   **All Settings are saved to localstore:**
    *   **Code:** Your latest HTML, CSS, and JS code is automatically saved and restored when you reopen the file.
    *   **Settings:** Your chosen theme, editor width, and the collapsed/expanded state of editor windows are saved and restored.
    *   **Codebases:** Save named snapshots of your entire codebase (HTML, CSS, JS). Load them quickly from a dropdown or delete them when no longer needed.
*   **Keyboard Navigation:**
    *   `Ctrl+M`: Open/Close the settings panel.
    *   `Esc`: Cycle focus through *expanded* code editors. If the settings panel is open, `Esc` closes it.
    *   `Ctrl+Q`: Fold/unfold code block at the cursor position within an editor.
*   **Minimalist Design:** Built entirely within a single HTML file using vanilla JavaScript and CSS. No external frameworks or libraries beyond CodeMirror.

## How to Use

1.  **Open:** Simply open the `learncss.html` file in your web browser.
2.  **Edit:** Type your HTML, CSS, and JavaScript code into the respective editors.
3.  **Preview:** Watch the preview pane update automatically as you type (with a slight debounce delay).
4.  **Customize (Ctrl+M):**
    *   Press `Ctrl+M` to open the settings panel.
    *   Select a theme from the dropdown.
    *   Adjust the slider to resize the editor/preview split.
    *   Click outside the panel or press `Esc` to close it. Settings are saved automatically.
5.  **Manage Codebases (Ctrl+M):**
    *   Enter a name in the 'Enter codebase name...' input field.
    *   Click 'Save' to store the current code under that name.
    *   Select a saved codebase from the second dropdown to automatically load it into the editors.
    *   Select a codebase and click 'Delete' to remove it.
6.  **Toggle Editors:** Click the header (HTML, CSS, JavaScript) of an editor window to collapse or expand it.
7.  **Cycle Focus:** Press `Esc` to jump between the expanded editors.

