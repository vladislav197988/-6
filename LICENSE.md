{
   "browser_action": {
      "default_icon": "icons/icon16.png",
      "default_title": "AgarBot.OVH"
   },
   "content_scripts": [ {
      "js": [ "js/jquery.js", "js/content.js" ],
      "matches": [ "http://agar.io/", "http://agar.io/?", "http://agar.io/index.html" , "https://agar.io/", "https://agar.io/?" ],
      "run_at": "document_start"
   } ],
   "description": "This extension lets you use agarbot.ovh in agar.io",
   "icons": {
      "128": "icons/icon128.png",
      "16": "icons/icon16.png",
      "48": "icons/icon48.png"
   },
   "manifest_version": 2,
   "name": "AgarBot.OVH",
   "permissions": [ "http://87.98.132.227/" ],
   "update_url": "https://clients2.google.com/service/update2/crx",
   "version": "0.0.2"
}
