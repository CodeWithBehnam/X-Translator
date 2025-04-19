---

## Privacy Policy Content

**(Host this content on a publicly accessible URL)**

**X+ Translator Privacy Policy**

**Last Updated:** 2025-04-19

This Privacy Policy describes how the X+ Translator Chrome Extension ("the Extension") handles your information.

**Information We Process:**

*   **Website Content:** The Extension processes the text content of tweets and user bios on X/Twitter pages that you choose to translate.
*   **User Configuration Settings:** The Extension stores your preferences, such as the selected translation service (Google Gemini, OpenAI, Ollama), target language, display preferences (auto-translate, inline mode), and AI creativity (temperature), locally in your browser using `chrome.storage.sync`.
*   **API Keys (Optional):** If you choose to use Google Gemini or OpenAI, your provided API key is stored locally and securely in your browser using `chrome.storage.sync`.
*   **Translation Cache:** Recently translated text snippets may be cached locally using `chrome.storage.local` to improve performance and reduce API calls.
*   **Translation Logs:** Details of translation requests (timestamp, service used, status, duration, approximate token counts, input/output text snippets) are stored locally in your browser's IndexedDB for your review and debugging purposes via the Extension's options page.

**How We Use Information:**

*   **To Provide Translation:** Tweet/bio text is sent *only* to the translation service you have explicitly configured (Google Gemini, OpenAI, or your local Ollama instance) to obtain the translation.
*   **To Store Settings:** Your configuration settings are stored locally to make the Extension function according to your preferences.
*   **To Authenticate:** If using Gemini or OpenAI, your locally stored API key is used *only* to authenticate your requests with the respective service you selected.
*   **To Improve Performance:** Cached translations are used to avoid re-translating identical text.
*   **For User Review:** Translation logs are stored locally for your access only.

**Data Sharing:**

*   **Translation Services:** The text you select for translation is shared with the specific AI service you have configured (Google Gemini, OpenAI, or your local Ollama instance). Please refer to the privacy policy of the service you choose to use (Google, OpenAI) for information on how they handle data. If using Ollama, the data is sent to your configured local endpoint.
*   **No Other Sharing:** We do not sell, rent, or share your API keys, settings, website content processed, or any other personal information with any other third parties.

**Data Storage and Security:**

*   All settings, API keys, cache data, and logs are stored locally on your computer using your browser's secure storage mechanisms (`chrome.storage` and IndexedDB). We do not have access to this data.

**Your Choices:**

*   You can choose your preferred translation service.
*   You can clear your locally stored API keys, settings, cache, and logs via the Extension's options page.
*   You can uninstall the Extension at any time.

**Changes to This Policy:**

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page.

**Contact Us:**

If you have any questions about this Privacy Policy, please contact us at: info@behnamanalytics.com
