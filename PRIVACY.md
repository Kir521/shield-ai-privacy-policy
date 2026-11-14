# Privacy Policy — Shield AI Security & Privacy

**Last Updated: 14 November 2026**

## 1. Introduction

Shield AI Security & Privacy is a defensive cybersecurity application designed to help users understand website security signals, inspect potential exposed secrets, and review privacy-related risks.

We aim to minimize the collection and sharing of personal and sensitive information.

## 2. Information Processed

Depending on the features used, the application may process:

- Website URLs submitted for security checks.
- Public HTTP response headers and connection information returned by scanned websites.
- Cybersecurity questions and conversation history submitted to the AI assistant.
- Website security results provided as context to the AI assistant.
- Files selected for privacy inspection.

The application does not request passwords, one-time passwords, recovery codes, or authentication secrets.

## 3. Website Security Checks

Website Security Check performs defensive checks against user-provided public website URLs.

The requested website receives network requests from the scanning service. The application may process the returned HTTP status, HTTPS connection information, and security headers.

These checks are preliminary assessments and do not constitute a complete security audit.

## 4. AI Assistant and Third-Party Services

The application may use Google Gemini as an AI fallback when the relevant integration is configured.

Questions, relevant conversation history, and website security context may be transmitted to Google Gemini to generate responses.

Such processing is subject to the applicable third-party provider's privacy and data-handling policies.

## 5. File Privacy Inspection

File privacy inspection is designed to help users identify potential sensitive information in selected files.

File contents and private pasted text are not intended to be sent as AI prompts.

Users should avoid selecting files containing information they do not have permission to inspect.

## 6. Data Storage and Retention

Website scan history may be stored in browser local storage and, when available, Anna account storage. The application maintains a limited scan history.

File inspection reads selected text files in the browser. The current implementation has a 5 MB file-size limit. File inspection results and scan records may be stored locally in browser storage.

When Gemini fallback is used, the question, up to the last 10 conversation messages, and available website scan context may be sent to Google Gemini.

Retention and processing by Anna AI OS and Google Gemini are governed by their respective policies and settings.

We do not guarantee zero data retention or zero cloud processing.

## 7. Security

We recommend keeping API keys and credentials in secure environment variables and never committing them to public source-code repositories.

Users should only scan websites they own or are authorized to assess.

## 8. Children's Privacy

This application is a cybersecurity tool and is not specifically designed to collect personal information from children.

## 9. Changes to This Policy

This policy may be updated when application functionality or data-processing practices change.

## 10. Contact and Support

For support and privacy-related questions, use the support channel provided with the application's official listing.

---

Shield AI Security & Privacy  
Audit before risk becomes an incident.
