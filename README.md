# Sign Up Form

A modern sign-up form built with HTML, CSS, and custom fonts. This project features a professional two-column layout with a background image and a clean, user-friendly registration interface.

## Features

- **Form Validation**: HTML5 built-in validation with visual feedback
- **Custom Typography**: 
  - Norse font for branding
  - Josefin Sans for form text
- **Interactive Elements**:
  - Focus states with blue borders and shadows
  - Invalid input highlighting in red
  - Smooth styling transitions
- **Professional Styling**: 
  - Clean, modern UI with proper spacing
  - Color-coded elements (#596D48 accent color)
  - Box shadows for depth

## Project Structure

```
Sign Up Form/
├── index.html          # Main HTML file with form structure
├── style.css           # Stylesheet with layout and component styling
├── font/               # Custom fonts
│   ├── Norse.otf
│   ├── Norsebold.otf
│   └── freefont_license.txt
├── img/                # Image assets
│   ├── background.jpg  # Form background image
│   └── odin-lined.png  # Logo image
└── README.md           # Project documentation
```

## Form Fields

The sign-up form includes the following fields with validation:

- **First Name** - Required, 2-26 characters
- **Last Name** - Required, 2-26 characters
- **Email** - Required, email format validation
- **Phone Number** - Required, minimum 10 characters
- **Password** - Minimum 8 characters
- **Confirm Password** - Minimum 8 characters

## Technologies Used

- **HTML5** - Semantic markup with form validation
- **CSS3** - Flexbox layout, custom styling, responsive design
- **Google Fonts** - Josefin Sans font family
- **Custom Fonts** - Norse font for branding

## How to Use

1. Open `https://shakurah.github.io/Sign-up-Form/` in a web browser
2. Fill in the form fields with your information
3. The form provides real-time validation feedback:
   - Focus on an input to see the blue border
   - Invalid inputs show a red border

## Credits

- Background photo by [Halle West](https://unsplash.com/@hallowest) on [Unsplash](https://unsplash.com)
- Logo design: ODIN (fictional branding)
- Fonts: Google Fonts (Josefin Sans), Custom Norse fonts

## Notes

- This is a frontend form template. Backend functionality for processing submissions is not implemented.

## Browser Compatibility

Works on all modern browsers that support:
- HTML5 form validation
- CSS Flexbox
- Custom fonts (@font-face)
