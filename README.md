# Number Pages by Artboards
Sketch plugin for automatically updating symbol overrides with page numbers

## Instructions
1. Create symbol containing a placeholder text layer with a unique name (by default, plugin will look for layers named `${page_number}`)
2. Run plugin (optionally specify your custom placeholder layer name)

All symbols on the current page containing placeholder layers with the specified name will be overridden with page numbers determined by artboard order in Sketch's Layer List, starting from the top down.
