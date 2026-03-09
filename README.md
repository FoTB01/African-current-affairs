# African Current Affairs App

A simple web application that provides news and updates on African current affairs topics.

## Features

- **Pre-defined Topics**: Quick access to popular African news categories
  - Nigeria Politics
  - South Africa Economy
  - Kenya News
  - African Union
  - Ghana Business
  - Ethiopia News
  - African Tech
  - African Sports

- **Custom Search**: Search any African topic of interest

- **Real-time News**: Can be connected to news APIs for live updates

## Setup

### Option 1: Simple HTML (No setup required)
1. Open `index.html` in any web browser
2. The app works immediately with built-in mock data

### Option 2: With Live News API (Recommended)
1. Get a free API key from [NewsAPI.org](https://newsapi.org)
2. Open `index.html` in a text editor
3. Replace `YOUR_API_KEY` on line 159 with your actual API key:
   ```javascript
   const API_KEY = 'your-actual-api-key-here';
   ```
4. Save and open in browser

## Usage

1. **Click a topic button** to see news on that subject
2. **Type in the search box** and click Search for custom queries
3. **Press Enter** in the search box to search quickly

## Customization

### Adding More Topics
Edit the `topic-buttons` div in the HTML to add new buttons:
```html
<button class="topic-btn" onclick="searchTopic('Your Topic')">Your Topic</button>
```

### Styling
The app uses CSS variables for easy theming. Modify the colors in the `<style>` section to match your brand.

### API Integration
The app is designed to work with NewsAPI but can be adapted for:
- Google News API
- MediaStack
- New York Times API
- Custom RSS feeds

## Files

- `index.html` - Main application file (contains HTML, CSS, and JavaScript)
- `README.md` - This file

## Browser Support

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Free to use and modify.
