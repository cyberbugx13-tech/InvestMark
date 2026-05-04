Hello GitHub Security Team,

I would like to report a security issue found in a public GitHub repository.

Issue Description:

A .env file in the repository contains exposed sensitive credentials, including API keys, secret tokens, and a Telegram bot token. These values are publicly accessible and should not be committed to version control.

Security Impact:

If these credentials are still valid, they may allow:

Unauthorized API access
Bot takeover via Telegram Bot Token
Abuse of connected services or automation
Exposure of sensitive backend functionality
Affected Repository:

https://github.com/subbudesigns/InvestMark

Recommendation:
Immediately revoke and rotate all exposed credentials
Remove .env from repository history (not just latest commit)
Ensure .env is added to .gitignore
Enable GitHub secret scanning and push protection

I am reporting this responsibly to help improve security.

Best regards,
Rahul Kumar
