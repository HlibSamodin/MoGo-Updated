# MoGo - Website Template

MoGo is a modern, clean, and responsive website template designed to showcase your services, team, and much more. With its sleek design and user-friendly interface, MoGo provides an ideal structure for building professional business websites.

## Features

- **Responsive Design**: Adjusts seamlessly to different screen sizes, ensuring a smooth experience across all devices.
- **Service Section**: Beautifully displays your services with icons, titles, and descriptions.
- **Team Showcase**: Displays your team members with photos, names, and roles.
- **Footer Subscription Form**: Enables users to subscribe to your newsletter.
- **Modern Typography**: Uses Google Fonts (Montserrat, Roboto, Kaushan Script) for an appealing visual experience.

## Technologies Used

- **HTML**: Structure of the website.
- **CSS**: Custom styling with variables for easy customization.
- **Google Fonts**: Montserrat, Roboto, and Kaushan Script for consistent typography.

## CSS Variables

This project utilizes CSS variables for easier customization. Below are the main variables you can modify:

### Text Colors:
- `--navigation-text-color`: Color for the navigation menu links.
- `--hover-text-color`: Color when hovering over navigation links.
- `--titles-color`: Color for titles (e.g., service titles, section titles).
- `--paragraph-color`: Color for paragraph text.
- `--footer-description-color`: Color for footer description text.

### Background Colors:
- `--background-color`: Background color for the body and footer elements.

### Fonts:
- `--first-font`: "Montserrat", sans-serif.
- `--second-font`: "Roboto", sans-serif.
- `--third-font`: "Kaushan Script", cursive.

## Styling Breakdown

### Global Styles
- **Box Sizing**: All elements use `box-sizing: border-box` for better layout control.
- **Font Family**: Default font is set to `Montserrat`, with fallbacks.
- **Flexbox Layout**: Flexbox is used throughout the design for alignment and spacing.

### Header
- **Logo**: Displayed in the header with the class `.header-logo`. Font size is 30px, and it uses the `--navigation-text-color`.
- **Navigation Links**: Styled to be uppercase with a color that changes on hover (`--hover-text-color`). Hover effect includes an underline.

### Service Section
- **Title**: The title of the service section uses `--titles-color` and is styled in uppercase.
- **Service Items**: Displayed as flex items with icons and titles.
- **Cards**: Each service card has a title, a description, and an icon. Text colors and font styles are defined for readability.

### About Section
- **Team Members**: Each team member is displayed with an image, name, and role. The role is italicized for distinction.
- **Description**: The description text is centered, and padding is applied for spacing.

### Footer
- **Copyright Text**: Styled with `--footer-description-color`.
- **Subscription Form**: The email input field and button are styled with consistent typography. The button background uses `--navigation-text-color`.

### Customization
To customize the site:

1. **Change Text Content**: Modify the content inside HTML tags (e.g., `<h1>`, `<p>`, `<a>`).
2. **Modify Colors**: Change the color of various elements by adjusting the CSS variables.
3. **Font Adjustments**: You can modify the `font-family` CSS properties in the styles if you prefer different fonts.

## Installation

1. Clone or download the repository.
2. Open the `index.html` file in your browser.
3. Edit the `style.css` and `index.html` files to customize the website as needed.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Author

MoGo Template by **Norvin**. For more information and updates, check out their portfolio.


