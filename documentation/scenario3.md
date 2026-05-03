\# Scenario 3: DNS Resolution Failure



\## Ticket Summary

User reported inability to access websites despite having network connectivity.



\## Impact

User could not access web-based services, affecting productivity.



\## Symptoms

\- Unable to access websites by domain name

\- Ping to google.com failed

\- Ping to external IP (8.8.8.8) succeeded



\## Troubleshooting Steps

1\. Verified network connectivity by pinging an external IP address.

2\. Identified that domain name resolution was failing.

3\. Checked DNS configuration using `ipconfig /all`.

4\. Observed incorrect DNS server configuration.



\## Root Cause

DNS server was incorrectly configured, preventing proper domain name resolution.



\## Resolution

Updated DNS settings to valid public DNS servers.



\## Verification

\- Successfully pinged google.com

\- Confirmed web browsing functionality restored



\## Tools Used

\- Command Prompt (`ping`, `ipconfig`)

\- Network Adapter Settings



\## Key Takeaway

This scenario demonstrates how to differentiate between network connectivity issues and DNS resolution failures.

