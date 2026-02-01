# Haselwood Self Check-In App

Self check-in kiosk application for service appointments - now available as a mobile and desktop app!

## 📱 Features

- **Progressive Web App (PWA)** - Install on mobile or desktop
- Customer information management
- Vehicle information tracking
- Service selection and pricing
- Works offline once installed
- Native app-like experience

## 🚀 Installation Instructions

### Mobile (iOS/Android)

#### **Chrome/Edge (Android)**
1. Open the app URL in Chrome or Edge browser
2. Tap the menu (⋮) and select **"Install app"** or **"Add to Home Screen"**
3. Tap **"Install"** when prompted
4. The app will be added to your home screen

#### **Safari (iOS)**
1. Open the app URL in Safari
2. Tap the Share button (square with arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **"Add"** in the top right corner
5. The app will be added to your home screen

### Desktop (Windows/Mac/Linux)

#### **Chrome/Edge**
1. Open the app URL in Chrome or Edge browser
2. Look for the install icon (⊕) in the address bar or click the menu (⋮)
3. Select **"Install Haselwood Self Check-In"**
4. Click **"Install"** when prompted
5. The app will open in its own window and be added to your applications

#### **Firefox**
Firefox doesn't support PWA installation natively, but you can:
- Bookmark the page for quick access
- Use a browser extension like "PWA for Firefox"

## 🖥️ Running Locally

To test the app locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/Sonali713/Here-we-go.git
   cd Here-we-go
   ```

2. Start a local web server (required for PWA features):
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # OR using Node.js (if you have npx)
   npx serve
   
   # OR using PHP
   php -S localhost:8000
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

4. Follow the installation instructions above to install the app

## 🌐 Deployment

To deploy this app:

1. **GitHub Pages**: Enable GitHub Pages in repository settings
2. **Netlify/Vercel**: Connect your repository for automatic deployment
3. **Any Web Server**: Upload all files to your web server with HTTPS enabled

**Note**: PWAs require HTTPS to work properly (except on localhost for testing)

## 🔧 Technical Details

- **No build step required** - Pure HTML, CSS, and JavaScript
- **Service Worker** - Provides offline functionality
- **Web App Manifest** - Enables installation as an app
- **Responsive Design** - Works on all screen sizes

## 📝 Testing Login

Use these test credentials:
- **Name**: John Doe
- **Phone**: 5559876543

## 🛠️ Work In Progress

- API integration for data push/pull
- Backend data transfer and interface
- Enhanced signature functionality
- Additional disclaimers for service agreements

## 📄 License

See LICENSE file for details 
