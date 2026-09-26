# World Clock - Multiple Time Zones

A modern, responsive digital clock application that displays the current time across multiple time zones with real-time updates.

## Features

✨ **Core Features**
- Real-time clock updates every second
- Display time for 20+ major time zones globally
- Show current date and UTC offset for each timezone
- Responsive design that works on desktop and mobile devices

🎨 **User Interface**
- Modern gradient dark mode (default)
- Light mode toggle for day/night usage
- Smooth animations and transitions
- Card-based layout with hover effects
- Interactive timezone selection

🔍 **Search & Filter**
- Search timezones by city name or timezone value
- Preset filters:
  - **All**: Shows all available timezones
  - **Popular**: Shows major global cities (UTC, London, Paris, New York, Tokyo, etc.)
  - **Business**: Shows business-critical timezones (Dubai, Singapore, Toronto, etc.)
- Clear search button for quick reset

⚙️ **Functionality**
- Click any timezone card to set it as "selected"
- Selected timezone highlights with blue accent
- UTC offset calculation for each timezone
- Theme preference saved to browser storage
- No dependencies - pure vanilla JavaScript

## Time Zones Included

### Popular
- UTC/GMT
- London (Europe/London)
- Paris (Europe/Paris)
- New York (America/New_York)
- Los Angeles (America/Los_Angeles)
- Tokyo (Asia/Tokyo)
- Sydney (Australia/Sydney)

### Business
- Dubai (Asia/Dubai)
- Singapore (Asia/Singapore)
- Hong Kong (Asia/Hong_Kong)
- Mumbai (Asia/Kolkata)
- Shanghai (Asia/Shanghai)
- Toronto (America/Toronto)
- São Paulo (America/Sao_Paulo)

### Additional
- Berlin, Moscow, Bangkok, Seoul, Istanbul, Mexico City, Buenos Aires, Auckland, Johannesburg, Jakarta, Manila, and more

## How to Use

1. Open `index.html` in any modern web browser
2. Browse time zones by:
   - Using the search box to find specific cities
   - Using preset filters (All, Popular, Business)
   - Clearing the search and resetting to defaults
3. Click any timezone card to select it
4. Toggle between light and dark modes using the button in the top-right corner

## Technology

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid layout
- **Vanilla JavaScript**: No frameworks or dependencies
- **Intl API**: Native browser timezone handling
- **LocalStorage**: Persists theme preference

## Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Modern mobile browsers: ✅ Full support

## Responsive Design

- Desktop: Multi-column grid layout
- Tablet: Adaptive grid sizing
- Mobile: Single column layout with optimized touch targets

## Performance

- Lightweight single HTML file
- No external dependencies
- Efficient DOM updates every second
- Minimal memory footprint

## Future Enhancements

- Add more timezones
- 12-hour time format option
- Alarm/notification for specific timezones
- Export current times as image
- Analog clock display option
- Add timezone comparison tools
