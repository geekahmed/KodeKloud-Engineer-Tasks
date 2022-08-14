# Create a Linux User with non-interactive shell	
## Problem
The System admin team of **xFusionCorp** Industries has installed a backup agent tool on all app servers. As per the tool's requirements they need to create a user with a **non-interactive shell**.

Therefore, create a user named ammar with a non-interactive shell on the App Server 1

## Solution
- ssh to the app server 1
- use the command: `sudo adduser ammar -s /sbin/nologin`
