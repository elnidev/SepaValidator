
# Privacy Policy — SEPA Validator (Extension)

Date: 2025-12-02

## Summary
This extension validates SEPA (pain.001) files directly in your browser. No personal or financial data (IBAN, amounts, names) is sent to any remote server by this extension.

## Processed Data
- The extension only reads and analyzes the XML files you provide (pain.001).
- Extracted information may include IBAN, BIC, names, amounts, and transaction identifiers.
- No automatic collection from websites or the browser is performed.

## Local Processing
- All parsing and validation operations are executed locally in the browser (FileReader + DOMParser).
- No data leaves your device. The extension does not make network calls to send analyzed content.

## Storage
- By default, the extension does not store IBANs or transaction information in chrome.storage or elsewhere.
- If you enable a future storage feature, it will be explicitly indicated in this policy and encrypted if necessary.

## Cookies and Analytics
- No analytics solution (Google Analytics, Sentry, etc.) is integrated and no sensitive usage data is collected.
- The extension may perform HTTP requests only if you voluntarily use a feature that requires it (none are present currently).

## Security
- All network communications (if added in the future) must use HTTPS.
- Avoid using the extension on files from unknown sources if you are concerned about leaks (even though the current operation is fully local).

## Retention and Deletion
- As the extension does not collect or store server-side data, there is no data to delete on the service side.
- If a local storage feature is added, an explicit deletion mechanism will be provided.

## Contact
- For any privacy-related questions: open an issue on the GitHub repository: https://github.com/elnidev/SepaValidator/issues
- Author / Responsible: elnicaise (GitHub profile)

## Policy Updates
- This policy may be updated. The date of the last update is indicated at the top.
