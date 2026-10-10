# Goal
Add a dark theme so the site is comfortable to read at night and respects each visitor's system setting.

# What will change
Add light and dark CSS color themes using custom properties, default to the visitor's system preference, and provide an accessible header toggle that saves a manual choice in localStorage. Adjust header controls only as needed to keep the header usable at 375px and 1280px.

# Why it improves the site
Visitors can use a comfortable color scheme that follows their device by default, with a simple way to override it. Readable contrast and visible keyboard focus will be maintained in both themes.

# How I will verify it
Build the Jekyll site, check the system-default and saved-toggle behavior, check light and dark contrast for text, links, navigation, and focus indicators, and inspect the header at 375px and 1280px.
