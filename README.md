# scannerprotect-docs
Documentation for the ScannerProtect project.

## What is ScannerProtect?
ScannerProtect is a protection layer against data-theft for physical NFC tags.

Some data thefts run around with their phones in NFC scan mode and try to scan your NFC tags to retrieve information from them or even clone them.

Having a ScannerProtect card covering your actual NFC tags will make it near impossible to steal data from your other tags.

## How does it work?
If you sandwich your NFC tags between two ScannerProtect tags a few effects come into play:
- First and foremost: The evildoer will likely not even be able to scan your tags due to overlap. In general, stacking NFC tags makes them harder to read.
- If the attacker DOES successfully scan the card he will be displayed a "tasty" URL like "https://totally-real-credit-institute.com/log-into-my-online-banking-account-in-1-click" which gives him a last chance to turn back.
- If the attacker visists the page an email with the HTTP request (including the attacker's IP address) will be sent to a configurable email address.
