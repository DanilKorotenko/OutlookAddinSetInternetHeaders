Issue Description
-----------------
It is impossible to set internet headers for outgoing mail in on-send addin.


Prerequisites
-------------
Addin code is hosted on: https://danilkorotenko.github.io/OutlookAddinSetInternetHeaders/index.html

[Manifest](/manifest.xml)


Steps To Reproduce
------------------
1. Install manifest: [Manifest](/manifest.xml)
2. Create and send test mail message. Send a test message to yourself.


Actual Result
-------------
The message didn't sent.

Expected result
---------------
The message has been sent.
Custom internet headers are present in the received message.


Hardware
--------
MacBook Air M1, 2020


Software
--------
macOS 13.4

Outlook for Mac 16.74 (23061100)
Outlook for Mac 16.74.1 (23061800)

Additional info
---------------

This issue is absent in Outlook on the Web (https://outlook.office.com/)

