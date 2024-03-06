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
@@@@   4 haf
javascript 
document.getElementById('clicker').addEventListener('click', () => { 
    // Sends a message to your content script 
    chrome.tabs.query({active: true, currentWindow: 
javascript 
chrome.runtime.onMessage.addListener(function(request, sender, sendResponse) { 
    if (request.action === "click") { 
        // Perform the click action on some element 
        document.querySelector('css-selector-of-target-element').click(); 
    } 
}); 
