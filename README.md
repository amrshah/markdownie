# Markdownie

A lightweight, browser-based markdown viewer with a clean interface inspired by VS Code. Perfect for browsing and reading markdown documentation locally without any installation.

## Features

**Simple Folder Navigation**
Open any folder on your computer and instantly see all markdown files listed in the sidebar. Files are automatically sorted alphabetically for easy browsing.

**Live Preview**
Click any markdown file to see it rendered beautifully in the preview pane. Supports GitHub Flavored Markdown including tables, code blocks, and more.

**Theme Support**
Switch between light and dark themes with a single click. The dark theme uses VS Code's color scheme, while the light theme provides a clean, readable alternative.

**No Installation Required**
This is a single HTML file that runs entirely in your browser. No servers, no build tools, no dependencies to install.

## Getting Started

1. Save the HTML file to your computer
2. Open it in a modern browser (Chrome, Edge, or Opera recommended)
3. Click "Open Folder" and select a folder containing markdown files
4. Click any file in the sidebar to view it

## Browser Compatibility

This viewer uses the File System Access API, which is supported in:
- Chrome 86+
- Edge 86+
- Opera 72+

Unfortunately, Firefox and Safari do not yet support this API.

## Why Use This?

Sometimes you just want to read markdown files without opening a full IDE or installing a dedicated markdown editor. This viewer fills that gap perfectly:

- Great for browsing project documentation
- Useful for reviewing multiple markdown files in a folder
- Handy for reading notes and wikis stored as markdown
- No need to push to GitHub just to see how your markdown renders

## Technical Details

The viewer uses the marked.js library to parse and render markdown. All processing happens client-side in your browser, so your files never leave your computer.

The interface is built with vanilla JavaScript and CSS, keeping things simple and fast. The styling follows VS Code's design language for a familiar, professional look.

## Customization

Feel free to modify the HTML file to suit your needs. The CSS variables at the top of the style section control the color scheme, making it easy to create your own theme.

## Privacy

This tool runs entirely in your browser. No data is sent to any server. Your files stay on your machine.

## Roadmap

**Planned Features**

Edit Support - Modify markdown files directly in the viewer and save changes back to disk.

Source + Preview Mode - Split view showing markdown source on one side and live preview on the other, perfect for writing and editing.

Source Only View - Focus mode for editing raw markdown without distractions.

View Mode Toggle - Quickly switch between preview-only, source-only, and split view modes.

**Ideas Under Consideration**

File Search - Quickly find files by name across your opened folder.

Recent Folders - Remember and quickly reopen recently accessed folders.

Table of Contents - Auto-generated navigation from markdown headings.

Export Options - Convert markdown to HTML or PDF for sharing.

Keyboard Shortcuts - Navigate files and switch views without touching the mouse.

Full-Text Search - Search content across all markdown files in the folder.

File Tree View - Support for nested folders and subdirectories.

Syntax Highlighting - Better code block rendering with language-specific colors.

Custom CSS - Load your own stylesheets for personalized markdown rendering.

Draft Mode - Auto-save work-in-progress to browser storage.

## License

MIT License - Free to use, modify, and distribute as you see fit.