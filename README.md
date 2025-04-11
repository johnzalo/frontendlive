# Live HTML/CSS/JS Trainer

A simple, single-file, vanilla JavaScript web application designed for learning and experimenting with HTML, CSS, and JavaScript in real-time. This tool provides a clean, minimalist environment focused on coding and immediate visual feedback.


![Image Alt](https://github.com/johnzalo/frontendlive/blob/6cf4a1ca570a157800b5c1e134dad8dd68160798/screen1.png)

## Key Features

*   **Live Preview:** Instantly see the results of your HTML, CSS, and JavaScript code rendered in a preview pane.
*   **CodeMirror Editors:** Separate, feature-rich editors for HTML, CSS, and JavaScript with:
    *   Syntax highlighting.
    *   Code folding (collapsible code sections via gutter arrows or `Ctrl+Q`).
    *   Hidden scrollbars (still scrollable).
*   **Collapsible Editor Windows:** Expand or collapse the HTML, CSS, or JS editor windows to focus on specific parts of your code.
*   **Customizable Interface (Ctrl+M):**
    *   **Theme Selection:** Choose from 50 different CodeMirror themes (light and dark) to suit your preference.
    *   **Layout Adjustment:** Use a slider to dynamically change the width split (0-100%) between the code editors and the live preview pane.
*   **Persistence with LocalStorage:**
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

## Technology

*   **HTML5**
*   **CSS3**
*   **Vanilla JavaScript (ES6+)**
*   **CodeMirror:** Core library for the code editors.
*   **LocalStorage:** For saving code, settings, and codebases.

Enjoy learning and coding! 
