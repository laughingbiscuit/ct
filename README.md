CT - Curl Templates
---

Typically a CLI will prompt a user for some values, then run one or many commands. These are typically API requests.

CLI library code is often bloated, out of date with the actual APIs they call, difficult to extend and limited compared with using the APIs directly.

CT is a small cli (12 lines) that prompts user for input, substitutes these values in a template and then runs the script. 

Users can add their own templates to the `requests` directory. For dynamic values, such as getting an OAuth token then scripts from the `auth` folder can be called.

