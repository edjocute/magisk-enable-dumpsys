# Magisk Module Template
### README.md

With MagiskSU, the dumpsys command fails in some devices due to insufficient SELinux permissions in enforcing mode. This affects apps which resets battery statsand also prevents aggressive doze in Greenify and Naptime from working correctly.

This module patches SELinux to ensure dumpsys has sufficient privileges to run correctly. 


