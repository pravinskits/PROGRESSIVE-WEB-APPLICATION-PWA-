# PROGRESSIVE-WEB-APPLICATION-PWA

Company : CODTECH IT SOLUTIONS

Name : Pravin S

Intern Id : CT04DG2370

Domain : WEB DEVELOPMENT

Duration : 4 Weeks

Mentor : Neela Santosh

Description:

This project is a Progressive Web App (PWA) named ShopNow, built using HTML, JavaScript (Vanilla JS), Service Workers, Cache API, and Web Push technologies. The primary goal is to deliver an e-commerce experience that works offline and supports push notifications.

The index.html file creates a simple webpage layout that includes a title (ShopNow - PWA), a <div> to display the product list dynamically, and a reference to a manifest file and an external JavaScript file (app.js). The app.js file contains a hardcoded array of products (T-shirt, Sneakers, and Backpack), each with an ID, name, and price. These products are displayed dynamically on the page using JavaScript DOM manipulation. The script also registers a Service Worker (service-worker.js) to enable offline capabilities.

The manifest.json file is essential for making the app installable on devices. It defines app metadata like the name, start URL, theme color, background color, and icons in various sizes, which allows the PWA to behave like a native app when added to a device’s home screen.

The service-worker.js file manages caching. During installation, it pre-caches essential assets (HTML, JS, and manifest files) using the Cache API. On each fetch event, it intercepts network requests and serves cached content if available, thus enabling offline support.

The push-server.js file, intended to run on a backend Node.js server, handles Web Push Notifications. It uses the web-push library to send a push notification to subscribed clients. This script generates VAPID keys, sets them for authentication, and defines an endpoint /subscribe to receive subscription objects from clients. When triggered, it sends a promotional notification about a big sale.

Overall, the application combines modern web capabilities to ensure a fast, reliable, installable, and engaging user experience even without internet access

Output:

