# Getting started browser extension

Useful browser extension that changes the background color of a page [=

Browser extension getting started from Google: https://developer.chrome.com/docs/extensions/mv3/getstarted/

## Branch [manifest-v2](https://github.com/viniciuskneves/getting-started-browser-extension/tree/manifest-v2)

This branch modifies the current implementation so it works on manifest version 2. You can check the diff [here](https://github.com/viniciuskneves/getting-started-browser-extension/compare/manifest-v2).

- `manifest_version` changes from 3 to 2;
- Under `background`, rename `service_worker` to `scripts` as an array and set `persistent` to `false;
- Add permission `declarativeContent` and remove `scripting`;
- Rename `action` to `page_action`;
- Enable extension only on `developer.chrome.com`.
