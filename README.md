# Mega Menu Block

This plugin registers an **experimental** Mega Menu block.

You can [test the block in your browser](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/ndiego/mega-menu-block/main/_playground/blueprint.json) using Playground. Try adding the Menu Menu block to a Navigation block and configure a menu template in the Settings Sidebar.

## Requirements

- WordPress 6.5+
- PHP 7.0+

## Limitations

This block is experimental, so there are a few limitations, and you will likely run into some oddities on the front end. It's recommended that you use this plugin as a starting point and adapt it to your theme.

- You must be using a block theme. (e.g., Twenty Twenty-Four)
- There is no support for vertically positioned Navigation blocks.
- The width of each mega menu is restricted to either full width or `content` and `wide` width as defined in theme.json.
- Menu template parts are created in the Site Editor. There is no UI in the Navigation block itself.

## Accessibility and RGAA 4 Compliance

This plugin aims to be compliant with the RGAA 4 accessibility guidelines. The following measures have been taken to ensure accessibility:

- **Semantic HTML**: The plugin uses semantic HTML elements such as `<nav>` for navigation and `<button>` for interactive elements to improve screen reader support.
- **ARIA Attributes**: All interactive elements, like buttons, have appropriate ARIA attributes such as `aria-expanded`, `aria-haspopup`, `aria-controls`, and `aria-label` to convey their state and purpose to screen readers.
- **Keyboard Navigation**: The plugin provides keyboard navigation support by handling focus and key events, ensuring users can navigate the menu using the keyboard alone.
- **Responsive Design**: The mega menu is responsive and adapts to different screen sizes, providing a consistent experience for all users.
- **Color Contrast**: The plugin ensures sufficient color contrast for text and interactive elements to ensure readability for users with visual impairments.
- **Clear Labels**: All menu items and interactive elements have clear and concise labels to improve usability and accessibility.
- **No Reliance on Color Alone**: The mega menu does not rely solely on color to convey information, as this can be problematic for users with color blindness.

### Using the Plugin with Screen Readers

To use the Mega Menu Block plugin with screen readers, follow these instructions:

1. **Navigation**: Use the Tab key to navigate through the interactive elements of the mega menu.
2. **Toggle Menu**: Use the Enter or Space key to toggle the mega menu open or closed.
3. **Menu Items**: Use the Arrow keys to navigate through the menu items.
4. **Close Menu**: Use the Escape key to close the mega menu.

### ARIA Roles and Attributes

The following ARIA roles and attributes are used in the plugin to enhance accessibility:

- `aria-expanded`: Indicates whether the menu is currently expanded or collapsed.
- `aria-haspopup`: Indicates that the button controls a menu.
- `aria-controls`: Associates the button with the menu it controls.
- `aria-label`: Provides a label for the button to improve screen reader support.
- `role="menu"`: Indicates that the element is a menu.
- `role="menuitem"`: Indicates that the element is a menu item.
