# telegram-contact-export
Telegram Contact export

### How to use

1. Login to https://web.telegram.org
2. Copy-paste contents of `telegram-scripts.js` into JS console
3. Run `showContacts()` to get the list of contacts with ids
4. Run `saveChat(userId)` where `userId` is the id from step 3

Process can take a while, check console for progress. Occasionall `FLOOD_WAIT` errors are expected. Once done, browser will download the JSON file.
