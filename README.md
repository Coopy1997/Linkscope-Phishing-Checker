# LinkScope

LinkScope is a professional website safety checker built for everyday users. Paste a website link to receive a clear trust score, plain-language explanation, and practical safety advice.

## Live Website

[Open LinkScope](https://linkscope-phishing-checker.vercel.app)

## Features

- Trust score from 0 to 100
- Clear safe, caution, or high-risk verdict
- Plain-language explanations
- Live website inspection
- Machine-learning URL analysis
- Brand impersonation detection
- HTTPS and certificate checks
- Redirect and domain record analysis
- Suspicious form and login detection
- Responsive desktop and mobile interface
- No account required

## How It Works

LinkScope combines several layers of analysis:

1. A trained URL model reviews 60 security signals.
2. The website is checked for redirects, certificates, forms, password fields, and suspicious behavior.
3. DNS records, domain age, email protection, and brand similarity are reviewed.
4. The findings are combined into a single trust score and easy-to-read report.

The model was trained using more than 35,000 legitimate and malicious URL examples from generated samples, popular-domain datasets, and public cybersecurity feeds.

## Trust Score

| Score | Result | Recommendation |
|---|---|---|
| 75–100 | Looks safe | Continue carefully |
| 45–74 | Be careful | Verify the website first |
| 0–44 | High risk | Do not use the website |

## Technology

- React
- TypeScript
- Tailwind CSS
- FastAPI
- Python
- Portable logistic URL model
- Vercel

## Privacy and Security

- No account or sign-in required
- Forms on scanned websites are never submitted
- Private and local network addresses are blocked
- Scans use strict timeouts and redirect limits

## Important Notice

LinkScope provides automated security guidance, not a guarantee that a website is safe. Results may include false positives or false negatives. Always verify unexpected links before entering passwords, payment details, or personal information.
