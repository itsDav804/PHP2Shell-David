# Security Research Log — 2026-11-09

- Issue or advisory: cve-2026-98432
- Platform / product: Linux
- Vulnerability class: Critical 9.8
- Impact summary:
- Affected versions: Linux kernel versions from 4.4 onward
- Fixed version or mitigation: Unless patched
- Status: open | mitigated | resolved
- References: https://www.google.com/search?q=cve-2026-98432&sca_esv=8b9727547dc98b1b&sxsrf=AKL5yDgNZ4p5H-DPfkCVF21eKGjbyBkIyQ%3A1794195747956&ei=I0HxapjsOb2d4-EPpNzswQI&biw=1536&bih=776&oq=&gs_lp=Egxnd3Mtd2l6LXNlcnAiACoHCAcY6gIYJzIHECMY6gIYJzIQECMY8AUYngYYogcY6gIYJzIQECMYogcYngYY8AUY6gIYJzIHECMY6gIYJzIHECMY6gIYJzIHECMY6gIYJzIHECMY6gIYJzIHECMY6gIYJzIQECMY8AUYngYYogcY6gIYJzIHECMY6gIYJzIXEAAYgAQYigUYkQIY5wYY6gIYtALYAQEyFxAAGIAEGIoFGJECGOcGGOoCGLQC2AEBMhcQABiABBiKBRiRAhjnBhjqAhi0AtgBATIXEAAYgAQYigUYkQIY5wYY6gIYtALYAQEyFxAAGIAEGIoFGJECGOcGGOoCGLQC2AEBMhcQABiABBiKBRiRAhjnBhjqAhi0AtgBAUj8iwFQ-ipY-ipwAngBkAEAmAFToAHZAaoBATO4AQHIAQD4AQGYAgWgAvgBqAIQwgIKEAAYRxjWBBiwA8ICFxAuGNwGGLgGGNoGGNgCGMgDGLAD2AEBmAMF8QWuMeWmQtiEdfEFYsvc-sruNXTxBXryL4_ytYla8QVAHkBG76qllogGAZAGD7oGBggBEAEYGZIHATWgB91GsgcBM7gH6QHCBwMyLTXIBxaACAE&sclient=gws-wiz-serp
- Evidence (sanitized):  Unauthenticated remote attackers can trigger kernel memory corruption, system crashes, or remote code execution (RCE)—notably demonstrated via exploit research against servers running Multipath TCP (MPTCP) listeners.
- Notes / next steps:

Do not include exploit code, credentials, personal data, or sensitive target details.
