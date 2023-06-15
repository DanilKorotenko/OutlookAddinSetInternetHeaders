Issue Description
-----------------
It is impossible to set internet headers for outgoing mail in on-sned addin.


Prerequisites
-------------

[Manifest](/manifest.xml)


Steps To Reproduce
------------------
1. Install manifest: [Manifest](/manifest.xml)
2. Create and send test mail message. Send a test message to yourself.
3. Review internet headers in received test message.


Actual Result
-------------
Custom internet headers are absent.


Expected result
---------------
Custom internet headers are present in the received message.


Hardware
--------
MacBook Air M1, 2020


Software
--------
macOS 13.4

Outlook for Mac 16.74 (23061100)
