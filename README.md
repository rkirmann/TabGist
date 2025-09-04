Title: Privacy Policy — TabGist
Effective date: 2025-09-04
1) Who we are
TabGist is a Chrome extension that summarizes and analyzes web pages and PDFs using Google Gemini. Contact: [your email].
2) What data we process
Page content: When you click “Ask AI,” the extension reads visible text from the current tab (and any tabs/files you explicitly add) to build a prompt for the AI.
Prompts and context: The prompt you type and the extracted text are sent to Google’s Generative Language API to generate an answer.
Settings: Your API key and preferences (e.g., dark mode, context chips) are stored locally in your browser via chrome.storage.
We do not collect analytics, personally identifiable information, or browsing history. The extension does not run in the background to scrape data; it only accesses content when you open the side panel and initiate a request.
3) Where data is sent
Google services: The prompt and context are sent to Google’s Generative Language API at generativelanguage.googleapis.com to generate a response.
PDFs: For online PDFs, the extension may fetch the PDF file contents to your browser to extract text locally. The PDF content is not transmitted to any third‑party other than Google if included as context in your prompt.
4) How data is stored
Locally: Your API key and preferences are saved in chrome.storage on your device. You can clear them anytime from the extension’s settings or by removing the extension.
No server: We do not operate our own servers to store user data. We do not sell or share data.
5) Permissions explained
activeTab/tabs/scripting: Used only to read the current page (and optional additional tabs) that you select, to provide AI context.
storage: Used to save your local settings and API key.
sidePanel: Provides the in‑browser user interface.
Host permissions: <all_urls> to read content you choose; generativelanguage.googleapis.com for AI responses.
6) Your choices and controls
Don’t share a key: The extension supports your own AI key; it isn’t sent anywhere except to Google when making a request.
Clear data: Use the “Save key”/settings UI to remove or replace your key, or uninstall the extension to remove all local data.
Limit access: Only open the side panel and click “Ask AI” on pages you want summarized; don’t add tabs/files you don’t want processed.
7) Children’s privacy
This extension is not intended for children under 13, and we do not knowingly collect personal data from children.
8) Changes
We may update this policy as features evolve. Material changes will be reflected by a new “Effective date” above.
9) Contact
Questions or requests: reimokirmann@gmail.com
