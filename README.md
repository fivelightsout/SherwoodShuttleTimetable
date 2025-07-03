<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Project Summary</h1>

  <h2>Introduction</h2>
  <p>The “豫豐花園接駁巴士時間” web app is a lightweight, mobile-friendly shuttle timetable tracker designed to give users instant access to the next two departures for each direction on the NR762 and NR762A routes. Built as a single self-contained HTML page, it embeds the full schedule data, automatically displays the current time, highlights the next bus, and adapts its layout to any screen size.</p>

  <h2>Summary of Features</h2>
  <ul>
    <li><strong>Embedded Schedule:</strong> All route data is contained in the page, removing external fetches.</li>
    <li><strong>Real-Time Updates:</strong> JavaScript timers refresh the displayed time and bus predictions every minute.</li>
    <li><strong>Next-Two Departures:</strong> Displays “Last,” “Next,” and “Next Next” times for each direction.</li>
    <li><strong>Responsive Layout:</strong> Flex-based two-by-two card rows that collapse gracefully on narrow viewports.</li>
    <li><strong>Dark Mode Support:</strong> Automatic color scheme switch via <code>prefers-color-scheme</code> for high contrast.</li>
    <li><strong>Emoji Favicon:</strong> A 🚍 emoji embedded as an SVG data URL for a friendly tab icon.</li>
  </ul>

  <h2>Technical Stack & Considerations</h2>
  <ul>
    <li><strong>Vanilla HTML/CSS/JS:</strong> Zero frameworks; everything lives in one file for easy portability.</li>
    <li><strong>Maintainability:</strong> Updating the timetable is as simple as replacing the embedded arrays.</li>
    <li><strong>Performance:</strong> No network requests after initial load, ensuring instant rendering.</li>
    <li><strong>Accessibility:</strong> Uses semantic markup, high-contrast colors, and responsive text sizes.</li>
  </ul>
</body>
</html>
