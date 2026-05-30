# NFC Wallet
This app is meant to be a simple tool for managing loose NFC tags.

Though currently in progress, the app will support:
- Scanning existing NFC tags and adding them to your wallet
- Selecting an NFC tag from your wallet to "impersonate".
- (?) Manually registering a new NFC tag based on protocol and data.

It will probably not support full impersonation, i.e. appearing exactly as the scanned NFC tag.
This limitation is caused due to lack of support from the Android NFC API in controlling certain
fields.
As a result, the functionality of the scanned NFC tags might be limited - it depends on the
scanner's implementation.