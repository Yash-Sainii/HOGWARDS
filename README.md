# HOGWARDS - Immersive Wizarding World Experience

An interactive, fully-featured immersive website dedicated to the Harry Potter universe. Experience a magical journey through Hogwarts School of Witchcraft and Wizardry with rich animations, detailed character profiles, and engaging interactive elements.

**Live Demo:** [https://hogwards-seven.vercel.app/](https://hogwards-seven.vercel.app/)

## Features

- **Immersive Landing Page** - Animated castle entrance with particle effects
- **Hogwarts Houses** - Four houses with detailed information and color-coded styling
- **Spell Library** - Interactive spell cards with 9 major spells from the series
- **Character Gallery** - 10 character profiles with real images and detailed biographies
- **Sorting Ceremony** - Interactive Sorting Hat experience
- **Great Hall** - Animated floating candles visualization
- **Patronus Charm** - Interactive spell casting experience
- **Timeline Section** - Complete saga timeline across all 8 movies
- **Audio System** - Magical sound effects with toggle control
- **Custom Wand Cursor** - Magic trail effects and particle bursts on interaction
- **Responsive Design** - Fully functional on desktop, tablet, and mobile devices
- **Easter Egg** - Hidden secrets for users to discover

## Tech Stack

- HTML5
- CSS3 (with advanced animations and effects)
- Vanilla JavaScript (ES6+)
- Web Audio API (for sound effects)

## Installation

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/ishika-guptaa25/HOGWARDS.git
cd HOGWARDS
```

2. Open the HTML file directly in your browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` (or your designated port)

### Project Structure

```
HOGWARDS/
├── index.html          # Main application file
├── images/             # Character images (PNG files)
├── .DS_Store          # macOS system file
└── README.md          # Project documentation
```

## Usage

### Navigation

- Use the navigation bar at the bottom of the page to jump between sections
- Click portraits to view detailed character information
- Hover over elements to see interactive effects
- Type "alohomora" to unlock hidden features

### Audio Control

Click the speaker icon in the bottom-right corner to toggle sound effects on/off.

### Sorting Hat

Enter your name and click "Begin Sorting Ceremony" to be sorted into a Hogwarts house.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Single HTML file with embedded base64 images
- No external dependencies or frameworks
- Optimized animations using CSS keyframes and requestAnimationFrame
- Lazy loading for floating candles
- Responsive grid layouts with auto-fit

## Deployment

The project is deployed on Vercel and automatically updates on push to the main branch.

To deploy your own version:

1. Push your changes to GitHub
2. Connect your repository to Vercel
3. Configure build settings (Static Site)
4. Deploy


## Customization

### Adding New Characters

Edit the `characterData` object in the JavaScript section to add new character profiles:

```javascript
characterData.newcharacter = {
    emoji: 'character emoji',
    name: 'Full Name',
    role: 'Character Role',
    description: 'Character biography...'
};
```

### Modifying Styles

CSS variables are defined in the `:root` selector:
- `--gold`: Primary accent color
- `--silver`: Text color
- `--dark-bg`: Background color
- `--wizard-blue`: Secondary color

## Future Enhancements

- Advanced search functionality
- User progress tracking
- Multiplayer sorting ceremony
- Mobile app version
- Extended character database


## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgments

- Harry Potter series by J.K. Rowling
- Inspiration from interactive web experiences
- Web animation and design best practices

## Support

For issues, questions, or suggestions, please open an issue in the GitHub repository.

---

### *"Magic is something that lives within us all..."*

