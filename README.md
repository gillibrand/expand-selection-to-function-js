Expand Selection to Function (JavaScript)
=========================================

A command to expand the current selection to the enclosing JavaScript function. This works with named and anonymous functions.

Each time this command runs it will expand farther out. For anonymous functions, the local variable or property name that refer to the function can also be selected. For example, expanding from the `alert` line below will first select the anonymous function (as represented with the «angle quotes»):

    var foobar = «function() {
        alert('Example!')
    }»;

Running it again will then select the variable and trailing semicolon:

    «var foobar = function() {
        alert('Example!')
    };»

After expanding the selection, you can restore the last selection, which will contract the selection to what it was before. You can expand several times then restore several times to return to your original selection.

Usage
-----

Both commands are available in the `Selection` menu and bound to the following keyboard shortcuts on Windows and Linux:

    Expand Selection to Function (JavaScript)   Alt+↑
    Restore Last Selection                      Alt+↓

Or similarly, on OS X:
    
    Expand Selection to Function (JavaScript)   ⌥↑
    Restore Last Selection                      ⌥↓
