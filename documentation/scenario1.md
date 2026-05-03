\# Scenario 1: No Internet Connectivity



\## Ticket Summary

User reported inability to access the internet from their workstation.



\## Impact

User was unable to browse websites or access online services, impacting productivity.



\## Symptoms

\- Web pages failed to load

\- Ping test to google.com failed with no response



\## Troubleshooting Steps

1\. Verified the issue by attempting to access external websites and performing a ping test.

2\. Checked network configuration using `ipconfig` to confirm IP assignment.

3\. Inspected network adapter status in Network Connections.

4\. Identified that the network adapter was in a disabled state.



\## Root Cause

The network adapter was found to be disabled, preventing the system from obtaining a valid IP address and accessing external networks.



\## Resolution

Re-enabled the network adapter to restore network connectivity.



\## Verification

\- Successfully pinged google.com with replies received

\- Confirmed that web browsing functionality was restored



\## Tools Used

\- Command Prompt (`ping`, `ipconfig`)

\- Network Connections (Windows)



\## Key Takeaway

This issue highlighted the importance of verifying basic network configurations, such as adapter status, before proceeding to more advanced troubleshooting steps.

