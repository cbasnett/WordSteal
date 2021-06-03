# WordSteal

This script will create a POC that will steal NTLM hashes from a remote computer. Do not use this for illegal purposes. The author does not take responsibility for any illegal action you perform.

Microsoft Word has the ability to include images from remote locations. This is an undocumented feature but was found
used by malware creators to include images through http for statistics. We can also include remote files to a SMB server
and the victim will authenticate with his logins credentials.
This is very useful during a pentest because allows you to steal credentials without triggering any alerts and most security apps do not detect this.
