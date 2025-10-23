# LitFarms Product Listing

![LitFarms Product Listing Interface](litfarms.gif)

A dynamic, real-time product listing web application for LitFarms THCA products. This application provides a modern, responsive interface for viewing and monitoring product availability with advanced filtering and notification capabilities.

## Features

### Product Display
- New theme and updated design (With light/dark mode switch)
- Real-time product updates
- Responsive grid layout
- Beautiful product cards with dynamic images
- Detailed pricing by tier and weight
- Stock status indicators with "In Stock" and "Out of Stock" badges
- Add to Cart functionality for in-stock items
- Fixed product COA buttons not displaying correctly sometimes

### Advanced Filtering
- Search products by name
- Filter by tier (Essential, Preferred, Supreme)
- Tiers now are programmatically determined (So if a new tier is created by LIT, they should show up without needing to update the code)
- Filter by strain type (Sativa, Indica, Hybrid)
- **Programmatic weight filtering** (All available weights are dynamically loaded)
- Search, weight, image, and sort-by algorithms are a little more precise
- Sort by:
  - Name (A-Z, Z-A)
  - Date (Newest, Oldest)
  - Price (Low to High, High to Low)
- Toggle between in-stock items and all items
- Persistent filter settings across sessions

### Notification System
- Real-time product monitoring
- Customizable update frequency
- Smart notification filtering:
  - Multi-select tier filtering (Essential, Preferred, Supreme)
  - **Multi-select weight filtering** (All available weights are dynamically loaded)
  - Specific product tracking
- Notification types:
  - New products
  - Stock changes (including price updates)
  - Product removals
  - New variant additions
- Detailed notifications including:
  - Price changes
  - Stock status changes
  - New variant introductions
  - Product removals
- Multiple notification methods:
  - New in-browser notification system (Ntfy notifications not changed)
  - Mobile app notifications via Ntfy
  - Email notifications
- Granular notification settings:
  - Select specific products to monitor
  - Filter by product tiers
  - Filter by product weights
  - Choose notification types (new/stock/removed)

## Setup

### Basic Usage
1. Visit the website at [litfarms.github.io](https://litfarms.github.io)
2. Use the filters at the top to find specific products
3. Click on any product card to view more details
4. Use the "Add to Cart" button on in-stock items to add them to your cart

### Setting Up Notifications

#### Mobile App Notifications
1. Download the Ntfy app:
   - [iOS App Store](https://apps.apple.com/us/app/ntfy/id1625396347)
   - [Google Play Store](https://play.google.com/store/apps/details?id=io.heckel.ntfy)
2. Click the settings gear icon in the bottom right
3. Enable "App Notifications"
4. Generate a unique topic name or enter your own
5. In the Ntfy app:
   - Tap "Add subscription"
   - Enter your topic name exactly as shown in the settings
   - Save the subscription

#### Email Notifications
1. Click the settings gear icon
2. Enable "Email Notifications"
3. Enter your email address
4. Save the settings

### Customizing Notifications
1. Open settings (gear icon)
2. Select desired tiers (Essential, Preferred, Supreme, or All)
3. Select desired weights (All available weights are dynamically loaded)
4. Choose notification types:
   - New products
   - Stock changes
   - Removed products
5. Optionally select specific products to track:
   - Use the search box to find products
   - Check/uncheck products to monitor
   - Use "Deselect All" to clear selections

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies
- Responsive design for all screen sizes
- Local storage for settings persistence
- Real-time product monitoring
- Virtual cart system
- Smart caching system for improved performance

## Browser Compatibility

The application is compatible with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## Privacy

- No user data is collected
- All settings are stored locally in your browser
- Notifications are sent through encrypted channels
- Email addresses are only used for notifications

## Contributing

Feel free to submit issues and enhancement requests!
