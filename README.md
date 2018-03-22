# telegram-contact-export
Telegram Contact export

### How to use

1. Login to https://web.telegram.org
2. Copy-paste contents of `telegram-scripts.js` into JS console
3. Run `showContactsPhoneNumber()` to get the list of contacts with Phone number
4. Run `saveChat(userId)` where `userId` is the id from step 3

Process can take a while, check console for progress. Occasionall `FLOOD_WAIT` errors are expected. Once done, browser will download the JSON file.

### Motivation

Proposed solution requires no dependencies and works with any browser/OS.

[telegram-history-dump](https://github.com/tvdstaaij/telegram-history-dump) has a dependency on [telegram-cli](https://github.com/vysheng/tg) which failed to work for me.
