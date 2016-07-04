# Workshop Unsubscriber for Chrome

Games like Space Engineers and Garrys Mod and many others have large modding communities. Sometimes you might be tempted to download hundreds if not thousands of mods.

But then something goes wrong, you don't know what's causing the problem so all you want to do unsubscribe from everything and start fresh. Unfortunately, the Workshop UI is, let's say, lacking in functionality. It's very tedious to unsubscribe from everything. This tool helps make the process far less tedious.

## How it Works

Once installed, you can visit your list of subscribed workshop items and you'll notice that there is a white square in the upper left corner. Click that square, the extension goes to work, clicking every unsubscribe button on the page, waiting for everything to finish, then reloading the page and seeing if there are any more unsubscribe buttons. If there are more, then the whole process loops over until there are no more items left to unsubscribe.

## Installation

1. Download manifest.json and unsubsciber.js to a directory.
2. Open the extensions setting in Chrome. 
3. Enable developer mode. 
4. Clicked Load Unpacked Extension, point to the directory you put those two files in
5. Visit your list of subscribed workshop items
6. Click the white square in the upper left corner and enjoy

# FAQ

## Why isn't this on the chrome app store?

This is code that manipulates your steam account. Everyone should be skeptical and weary about executing code like this. By ensuring that you download from github is what you run, you can ensure that the code you see here is what you are running.

If you are unsure about executing this code, then ask someone who can understand this code to vet it for you.

## Firefox?

Well, I don't plan on doing it myself any time soon, but this code is simple enough that anyone else is free to submit a pull request or fork this to port it to Firefox.

## Does this violate Steam TOS?

I can not see anything that would prevent using such a tool. However, there may be reasons we are not aware for Valve not letting us "unsubscribe to all". You use this at your own risk.
