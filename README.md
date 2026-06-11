# Linkscope-Phishing-Checker
LinkScope is a professional phishing detection and link trust platform for checking suspicious URLs before users open them.

The app lets a user paste a URL, run a scan, and receive a trust score, risk score, verdict, technical evidence, and readable explanation. The checker combines URL intelligence with safe live website inspection.

Product Features
Clean one-page web experience
React, Vite, TypeScript, Tailwind CSS frontend
FastAPI backend with Pydantic schemas
URL feature extraction from the submitted link
Live HTTP/HTTPS reachability checks with bounded response reads
Private-network blocking and redirect-by-redirect target validation
Redirect, final URL, status code, and content-type inspection
TLS certificate validation and expiry signal
HTML form, password field, external form action, script, and link inspection
Brand impersonation, credential-field, iframe, meta refresh, and risky download signals
DNS intelligence for A/AAAA, MX, NS, CAA, SPF, and DMARC records
RDAP domain-age lookup when registration data is available
Typo-squatting similarity checks against major brand domains
In-memory scan caching and basic API rate limiting
Weighted scoring engine with category scores and ranked evidence
Common security header checks
ML model loader using Joblib when a trained model exists
Clearly labelled fallback heuristic when no model file is available
Executive-style trust report interface
Responsive polished product-style design
Tech Stack
Frontend: React, Vite, TypeScript, Tailwind CSS, Lucide icons
Backend: Python, FastAPI, Scikit-learn, Pandas, NumPy, Joblib, Pydantic, Uvicorn
Machine learning: URL feature extractor with Logistic Regression and Random Forest training script
