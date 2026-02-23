## Technical Requirements:
- Create a single HTML file with embedded CSS and JavaScript. Place the output in the `build/` folder.
- Implement keyboard navigation: left/right arrow keys to navigate between slides, Home/End to jump to first/last slide
- Display current slide number and total slides in the top right corner (e.g., "3/12")
- Show a chapter navigation menu on the left side of the screen listing all major sections. Add ability to minimize this menu.
- Highlight the current chapter in the navigation menu
- Ensure smooth transitions between slides
- Make the presentation fullscreen-friendly for recording
- Use fixed 16:9 aspect ratio for slides — content must not reflow on different window sizes
- Show a thin progress bar at the bottom of the screen indicating current position in the presentation
- Sync slide state with URL hash (e.g., `#slide-5`) — supports page reload and sharing links to specific slides

## Visual Design Requirements:
- Use Frontend Design Skills!
- Use a font stack with good Cyrillic support (e.g., Inter, Golos Text, or system-ui). Specify `font-feature-settings: "tnum"` for tabular numbers in statistics and pricing.

## Navigation Structure:
- The left sidebar should show chapter names
- Clicking on a chapter should jump to that section
- The current chapter should be visually highlighted
- Slides should be grouped logically under their respective chapters
