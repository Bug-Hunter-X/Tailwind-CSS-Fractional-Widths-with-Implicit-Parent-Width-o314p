# Tailwind CSS Fractional Widths Issue

This repository demonstrates a common issue encountered when using Tailwind CSS fractional width classes (`w-1/2`, `w-1/3`, etc.) without explicitly setting the width of the parent container.

The problem arises when the parent element's width is implicitly determined by its content. This can lead to unexpected layout behavior, where the fractional widths don't divide the space equally or as intended.

**Steps to Reproduce:**

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the two divs don't take up exactly half the width each.

**Solution:**

Refer to `solution.html` for a possible fix, which involves explicitly setting the width of the parent container.