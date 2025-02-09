# Uncommon HTML Bug: Incorrect innerHTML usage with HTML Entities

This repository demonstrates an uncommon bug related to the usage of `innerHTML` in HTML when dealing with HTML entities.  The bug arises when attempting to set the `innerHTML` property of an element with a string containing HTML entities that are not properly escaped.  This can lead to unexpected rendering and potential security vulnerabilities.

## Bug Description
The bug is demonstrated in `bug.html`. The script incorrectly uses `innerHTML` to insert a string containing an unescaped `<p>` tag. The browser interprets this, leading to incorrect parsing and rendering.

## Solution
The solution, provided in `bugSolution.html`, demonstrates how to correctly handle HTML entities when using `innerHTML` to avoid this parsing issue.