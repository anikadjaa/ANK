# ANK

json
{
    "manifest_version": 2,
    "name": "Clicker",
    "version": "1.0",
"permissions": ["activeTab", "tabs", "http://*/*", "https://*/*"], 
    "browser_action": { 
        "default_popup": "popup.html", 
        "default_icon": "icon.png" 
}, 
    "background": { 
        "scripts": ["background.js"], 
        "persistent": true 
MU
html 
<!DOCTYPE html> 
<html> 
<body> 
