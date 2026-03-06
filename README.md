# CoffeeCalculator

A cute little static web app to calculate coffee ratios when your neurons are still asleep 🥱

## Features

- **Multiple Brewing Methods**: Choose between Drip Coffee, French Press, and Turkish Coffee
- **Customizable Strength**: Select light, medium, or strong coffee strength with adorable animal emojis
- **Automatic Calculations**: Get instant water-to-coffee ratio calculations
- **Responsive Design**: Works on mobile and desktop devices
- **Cute UI**: Warm color scheme with smooth animations

## How to Use

1. **Select your brewing method** (Drip, French Press, or Turkish)
2. **Choose your coffee strength** by tapping the animal emojis:
   - 🐹 Light Strength (13.33ml/g) - gentle flavor
   - 🐱 Medium Strength (13.9ml/g) - balanced flavor (default)
   - 🦁 Strong Strength (14.47ml/g) - intense flavor 🔥
3. **Enter your coffee amount** (for Drip) or **water amount** (for French Press/Turkish)
4. **See instant results** showing the perfect ratio and amounts needed

To open the Web App, just go on: (manuasdf.github.io/CoffeeCalculator)[https://manuasdf.github.io/CoffeeCalculator/]

## Technical Details

- **Pure HTML/CSS/JavaScript**: No framework dependencies
- **Modern CSS**: Uses `:has()` selector for parent selection
- **Responsive Grid Layout**: Adapts to different screen sizes
- **Simple Animations**: Subtle transitions and hover effects

## Customization

You can easily customize the app by modifying the CSS variables at the top of the `index.html` file:

```css
:root {
    --primary: #8B4513;      /* Coffee brown */
    --secondary: #F4A460;    /* Light brown */
    --accent: #FFD700;       /* Gold */
    --light: #F5F5DC;        /* Beige background */
    --dark: #2F2F2F;         /* Dark text */
}
```

Maybe themes will be added in the future. 

## Browser Support

Works in all modern browsers that support:
- CSS Grid
- CSS `:has()` selector
- CSS variables
- Flexbox

## License

MIT License - feel free to use, modify, and share!

## Credits

Made with ☕ and love for coffee enthusiasts everywhere!
