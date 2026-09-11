#NX-Status

#Features

Glassmorphism UI: Elegant, semi-transparent design with modern blur effects and clean FontAwesome icons.

Performance Optimized: Extremely low resource usage (0.00ms idle) thanks to optimized loops and events.

Full ESX Integration: Displays health, armor, hunger, thirst, and stamina in real time.

Smart Visibility: Automatically hides the HUD when unconscious or dead.

Easy Customization: The style can be fully adapted to your server layout via CSS.

#📦 Dependencies
es_extended (ESX Legacy)

esx_status (For hunger and thirst tracking events)

#Installation

Download the script and place the nxd_status folder into your resources directory.

Add this entry to your server.cfg:

Code-Snippet
ensure nx_status
Make sure es_extended and esx_status are loaded before this script in your server configuration.

#Customization

You can flexibly edit the appearance, spacing, and colors in html/style.css. The position (default is bottom right) can be adjusted via #hud-container:

CSS
#hud-container {
    position: absolute;
    bottom: 30px;
    right: 30px;
    /* ... */
}
#💡 Support & Credits
Developed by Next-Solutions.

# Discord
https://discord.gg/mB45RPuFdE
