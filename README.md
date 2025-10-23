# LitFarms Product Listing

![LitFarms Product Listing Interface](litfarms.gif)

A dynamic, real-time product listing web application for LitFarms THCA products. This application provides a modern, responsive interface for viewing and monitoring product availability with advanced filtering and notification capabilities.


---

## 2.0 Changes and Enhancements

This section details the significant updates introduced in the latest version.

### Design and UX Updates
- **New Theme and Design:** Includes a refreshed aesthetic for a better user experience.
- **Light/Dark Mode Switch:** Added to allow users to customize the interface theme.
- **COA Button Fix:** Corrected an issue where product COA (Certificate of Analysis) buttons were sometimes not displaying correctly.

### Filtering and Data Logic
- **Programmatic Tiers:** Tiers are now **programmatically determined** from the product data. This means any new tier created by LitFarms will automatically appear in the filters without requiring a code update.
- **Improved Algorithms:** The search, weight, image selection, and sort-by algorithms have been refined for **greater precision** and reliability.
- **Programmatic Weight Filtering:** Weight filtering is now dynamic, automatically listing all available weights rather than being fixed (replaces the hardcoded 28g, 3.5g, 7g filters).

### Notification System
- **New In-Browser Notifications:** A real-time, visible notification system has been added directly to the application interface. (Existing Ntfy mobile app notifications and email notifications remain unchanged).

---

## Features

### Product Display
- Real-time product updates
- Responsive grid layout
- Beautiful product cards with dynamic images
- Detailed pricing by tier and weight
- Stock status indicators with "In Stock" and "Out of Stock" badges
- Add to Cart functionality for in-stock items

### Advanced Filtering
- Search products by name
- Filter by tier (Essential, Preferred, Supreme)
- Filter by strain type (Sativa, Indica, Hybrid)
- Filter by weight (28g, 3.5g, 7g)
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
  - Multi-select weight filtering (28g, 3.5g, 7g)
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
  - Mobile app notifications via Ntfy
  - Email notifications
- Granular notification settings:
  - Select specific products to monitor
  - Filter by product tiers
  - Filter by product weights
  - Choose notification types (new/stock/removed)

---

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
3. Select desired weights (Dynamically loaded weights, or All)
4. Choose notification types:
   - New products
   - Stock changes
   - Removed products
5. Optionally select specific products to track:
   - Use the search box to find products
   - Check/uncheck products to monitor
   - Use "Deselect All" to clear selections
---
## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies
- Responsive design for all screen sizes
- Local storage for settings persistence
- Real-time product monitoring
- Virtual cart system
- Smart caching system for improved performance
---
## Browser Compatibility

The application is compatible with all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers
---
## Privacy

- No user data is collected
- All settings are stored locally in your browser
- Notifications are sent through encrypted channels
- Email addresses are only used for notifications
---
## Contributing

Feel free to submit issues and enhancement requests!
