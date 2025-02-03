# CSS `calc()` Misuse Bug

This repository demonstrates a common yet subtle bug related to the incorrect usage of the `calc()` function in CSS. The issue arises when attempting to calculate a width relative to a parent element that doesn't have an explicitly defined width.

**Bug:** The `calc()` function is used to calculate a width based on the parent's width, but the parent doesn't have a specified width. This often leads to the element not rendering correctly or having an unexpected width.

**Solution:** To fix the issue, ensure that the parent element has its width defined, either explicitly or implicitly (through its content).