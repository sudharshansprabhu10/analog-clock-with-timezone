# Elegant Analog Clock with Timezone Support

A beautiful, responsive analog clock implementation with timezone support and an elegant pendulum animation. Built with HTML, CSS, and JavaScript, using Moment.js for timezone handling.


## Features

- ⏰ Real-time analog clock with hour, minute, and second hands
- 🌍 Support for multiple timezones across all major regions
- 🕰️ Elegant pendulum that swings at the start of each hour
- 📱 Fully responsive design that works on all devices
- 🎯 Precise time display with both analog and digital formats
- 🎨 Clean, modern UI with smooth animations

## Dependencies

- Moment.js (2.29.4)
- Moment Timezone with Data (0.5.43)

## Quick Start

1. Clone this repository or download the HTML file
2. Include the required dependencies:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.29.4/moment.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment-timezone/0.5.43/moment-timezone-with-data.min.js"></script>
```
3. Open the HTML file in a web browser

## Supported Timezones

The clock supports multiple timezones across different regions:

### Americas
- New York (EST/EDT)
- Chicago (CST/CDT)
- Los Angeles (PST/PDT)
- Toronto
- Vancouver
- Mexico City
- São Paulo
- And more...

### Europe
- London (GMT/BST)
- Paris (CET/CEST)
- Berlin
- Madrid
- Rome
- Amsterdam
- And more...

### Asia
- Dubai
- Tokyo
- Shanghai
- Hong Kong
- Singapore
- Mumbai/New Delhi (IST)
- And more...

### Oceania
- Sydney
- Melbourne
- Auckland
- Perth
- Fiji

### Africa
- Cairo
- Johannesburg
- Lagos
- Nairobi
- Casablanca

## Customization

### Clock Size
Modify the clock size by adjusting the `.clock` dimensions in CSS:
```css
.clock {
    width: 300px;  /* Adjust this value */
    height: 300px; /* Adjust this value */
}
```

### Colors
Customize the clock appearance by modifying these CSS variables:
```css
/* Hand Colors */
.hour { background: #333; }
.minute { background: #666; }
.second { background: #ff6b6b; }

/* Clock Face */
.clock { background: white; }
```

### Pendulum Animation
Adjust the pendulum swing timing and angle:
```css
@keyframes swing {
    0% { transform: rotate(0deg); }
    25% { transform: rotate(20deg); }  /* Adjust angle */
    75% { transform: rotate(-20deg); } /* Adjust angle */
    100% { transform: rotate(0deg); }
}

.swing {
    animation: swing 2s ease-in-out; /* Adjust duration */
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing

Feel free to submit issues and enhancement requests!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Moment.js team for the excellent timezone support
- Inspired by classic grandfather clocks for the pendulum feature

## Author

Sudharshan S Prabhu

## Version History

- 1.0.0 (2024-10-11)
  - Initial release
  - Basic clock functionality
  - Timezone support
  - Pendulum animation
