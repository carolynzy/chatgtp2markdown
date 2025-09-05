# chatgtp2markdown

Overview

ChatGPT → Markdown Exporter is a Chrome extension that allows users to export ChatGPT conversations into Markdown format. We respect your privacy and are committed to protecting it. This extension is designed to process all data locally within your browser.

**Data Collection**

* No personal data is collected.

* No conversation content is transmitted, stored, or shared.

* The extension does not use analytics, ads, tracking, or third-party services.

**Data Access & Usage**

* The extension only runs on chatgpt.com and chat.openai.com.

* It reads the visible conversation content on those pages solely for the purpose of converting it into a Markdown file.

* The processed data is saved directly to your device using the Chrome Downloads API.

**Local Storage**

* User preferences (such as highlight style, filename pattern, or whether to include YAML front matter) are stored locally using chrome.storage.local.

* These settings never leave your device and are not synced to the cloud.

**Images**

* If conversations contain images, the exported Markdown may include links to those image URLs.

* When you open the Markdown file in an editor or viewer, that program may fetch the images from their original servers.

* This behavior is part of your viewer software, not the extension itself. You can configure the extension to convert images into links or omit them entirely.

**Permissions**

* The extension requests the following Chrome permissions:

* scripting: to inject the exporter script into ChatGPT pages.

* downloads: to save Markdown files locally.

* storage: to remember your export settings.

* These permissions are used exclusively for the features described above.

**Remote Code**

This extension does not use remote code. All functionality is bundled within the extension package and runs locally in your browser.

**Contact**

If you have questions or concerns about this extension or its privacy practices, please contact the developer using the support email provided in the Chrome Web Store listing.
