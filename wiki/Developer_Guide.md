# 🛠️ Developer Guide

This guide helps contributors customize and extend AutoTechGPT.

## Repository Structure

```
AutoTechGPT/
├── index.html
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── PRIVACY_POLICY.md
├── SECURITY.md
├── LICENSE
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   ├── feature_request.md
│   │   └── security_report.md
│   └── PULL_REQUEST_TEMPLATE.md
└── wiki/
    ├── Home.md
    ...
```

## Customizing Menu & Prompts

1. **Edit the GPT Definition**:
   - Use **ChatGPT developer** tools: modify the system prompt.
2. **Add New Brand Overlays**:
   - Create conditions in the system prompt for specific make/model keywords.
3. **Extend Training Paths**:
   - Update the **Education & Training** submenu with more lessons or tracks.

## Testing Locally

- You can preview `index.html` by opening it in any browser.
- Use browser dev tools to tweak CSS or structure.

## Submitting Changes

- Follow [CONTRIBUTING.md](../CONTRIBUTING.md).
- Ensure all changes align with style and compliance guidelines.
