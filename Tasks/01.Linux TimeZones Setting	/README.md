# Linux TimeZones Setting	
## Problem
During the daily standup, it was pointed out that the timezone across `Nautilus Application Servers` in `Stratos Datacenter` doesn't match with that of the local datacenter's timezone, which is `Asia/Kabul`.

## Solution
For each application server do the following:
- Check the time zone using the command `timedatectl`
- Changing the time zone using the command `sudo timedatectl set-timezone Asia/Kabul`