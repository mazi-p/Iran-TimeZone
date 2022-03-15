# Iran-TimeZone
Time-Zone file for "/Asia/Tehran" (Iran) without daylight saving configuration.
================================================================================

Due to new rule of the Iranian parlemant, there will be no more Day Light Saving change in the Iranian Time-Zone. By default for Linux and Unix user there is "etc" directory in the "zoneinfo" directory which contains TZs file with no DST configuration. But Iran use not integer offset for their Time-Zone. (GMT +3:30)

So we should wait new update from IANA site, or generate Time-Zone file manually.

I have generated "Tehran-nodst" file manually to use on my Linux machines until new update will be release from Linux distribution.

You can download it and copy it to "zoneinfo" directory of your machine (better to copy it to "zoneinfo/Asia") and create symbolic link "/etc/localtime" to this file.

It is recommended to use update of the zoninfo package as soon as possible which will be released from your distribution.
