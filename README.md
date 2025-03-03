# Big Clock
## A full-screen digital clock for an exam/quiz with simple customizations

This code was generated from the following prompts in ChatGPT in early 2025.
- Write a simple web app in simple HTML/CSS/JS that can do the following?
    - Display the current time, hour and minute, prominently
    - Can be shown fullscreen in dark background
    - Text and background colors should be customizable
    - Other information such as day of week, date, and some custom text can be shown in smaller text as well
    - The current time in seconds should be shown only when it's approaching a custom end time (within 30 minutes or any customizable range)
    - The UI should be simple and discreet, possibly visible only when needed or hovered
- The text on screen should be easy to see all the time. And the current time should be even bigger.
How can I adjust any customization I mentioned earlier?
- The customization should be adjustable from the web app itself. Other issues:
    - date format should use month names
    - the custom text should be on the other line
- The UI should hidden when not in use.
    - The background selector should have contrasting border so the user knows where to click
    - The colors and text should change as the inputs were selected or entered. No need to have the Apply button
- The default custom text should be empty
    - Color selector labels do not vertically align with the selectors.
    - The time should be always visible; it does not hide with the UI. Why are there two sets of texts showing time?
- The color selectors and text input should horizontally aligned as well. Maybe their labels can be right-aligned.
    - Still there is no current time in seconds that should be shown only when it's approaching a custom end time (within 30 minutes or any customizable range)
- They are not exactly aligned
    - How to adjust the custom time?
- the heights of the input fields should be the same.
    - when the seconds are shown, they should be on the same line with hours and minutes but should not move/push them to the left
    - The leading zeros in the hours should be the same color as the background
    - the text color selector doesn't shown the current default color

For some reasons, ChatGPT failed to do some stylings so I will add some minor adjustments. Below are some todos.
- The heights of all input fields should be the same.
- When the seconds are shown, they should not move/push the hours and minutes to the left
- The seconds should be top-aligned with the hours and minutes?