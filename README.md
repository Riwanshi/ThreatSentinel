# ThreatSentinel
AI-powered social media threat monitor that collects public posts and metadata, detects cyber threats (phishing, disinformation, impersonation, doxxing) using NLP and behavior analytics, prioritizes incidents by risk score, and alerts stakeholders with evidence and remediation guidance. Cloud-native, modular, and privacy-aware.


Main Features
User Management
User Registration
Login/Logout
Role-Based Access Control
Admin
Analyst
User


Social Media Data Collection
Connect Social Media APIs
Fetch Posts/Comments
Scheduled Data Collection
Real-Time Monitoring

Examples:

Twitter/X API
Reddit API
Facebook Graph API (if available)


NLP Text Processing
Preprocessing
Remove URLs
Remove Emojis
Remove Stop Words
Tokenization
Stemming
Lemmatization

Example:

Input:

"I will destroy you!!! 😡"

Processed:

destroy


Threat Detection Module
Detect:

Cyberbullying

Examples:

You are stupid
Nobody likes you
Hate Speech

Examples:

Religious hatred
Racial abuse
Threats

Examples:

I will kill you
Bomb threat messages


AI Classification

Output Categories:

Threat Score	Category
0-40%	Safe
41-70%	Warning
71-100%	Dangerous


Alert System

When Dangerous content is found:

Email Alert
Dashboard Notification
SMS Alert (Optional)
Push Notification


Dashboard
Display:

Total Posts Analyzed
Total Threats
Dangerous Posts
Recent Alerts
User Activity Logs
Graphs and Charts


Reports
Generate:

Daily Reports
Weekly Reports
Monthly Reports

Export:

PDF
Excel


Activity Logs
Store:

Login History
Threat Detection History
Alerts Generated
