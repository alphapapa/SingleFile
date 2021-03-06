# SingleFile
SingleFile is a WebExtension compatible with Chrome, Firefox (Desktop and Mobile), and Opera that helps you to save a complete web page into a single HTML file.

## Demo
https://www.youtube.com/watch?v=RdV8DBW5b0g

## Install
 - Firefox Add-ons: https://addons.mozilla.org/en-US/firefox/addon/single-file
 - Chrome Web Store: https://chrome.google.com/extensions/detail/mpiodijhokgodhhofbcjdecpffjipkle
 - Opera: The extension is not on the store yet, you must download the zip file (https://github.com/gildas-lormeau/SingleFile/archive/master.zip) and install it manually

## Getting started
- Wait until the page is fully loaded, you may need to scroll down the entire page to be sure all elements are loaded.
- Click on the SingleFile button in the extension toolbar to save the page.

## Additional notes
 - To save multiple tabs, select them first and click on the SingleFile button.
 - Open the context menu by right-clicking the SingleFile button in the extension toolbar or on the webpage. It allows you to save:
   - the current tab,
   - or the selected content,
   - or the selected frame.
 - You can also process multiple tabs in one click and save:
   - the selected tabs,
   - or the unpinned tabs,
   - or all the tabs.
 - The context menu also allows you to activate the auto-save of:
   - the current tab,
   - or the unpinned tabs,
   - or all the tabs.
 - With auto-save active, pages are automatically saved every time after being loaded (or before being unloaded if not).
 - Right-click on the SingleFile button and select "Options"/"Manage extension" to open the options page.
 - The default save folder is the download folder configured in your browser, cf. about:preferences in Firefox and chrome://settings in Chrome.
 - You can use the shortcut Ctrl+Shift+X to save current or selected tabs in Chrome. Go to chrome://extensions/shortcuts to change it.

## More info
See the extension help in the options page for more detailed information about the options, and technical notes. See https://github.com/gildas-lormeau/SingleFile/wiki/Optimizations-applied-to-web-pages for some info about the optimizations applied to web pages.

## Statistics (Firefox)
See https://addons.mozilla.org/en-US/firefox/addon/single-file/statistics/?last=90

## Known Issues
- All browsers:
  - For security reasons, you cannot save pages hosted on https://chrome.google.com or https://addons.mozilla.org.
  - The last saved path cannot be remembered by default. To circumvent this limitation, disable the option "Save pages in background".
- Chrome/Opera:
  - You must enable the option "Allow access to file URLs" in the extension page to display the infobar when viewing a saved page, or to save a page stored on the filesystem.  

## Troubleshooting unknown issues
Please follow these steps if you find an unknown issue:
- Reset SingleFile options.
- If resetting options did not fix the issue, try to disable all other extensions to see if there is a conflict.
- If there is a conflict then try to determine against which extension(s).
- Please report the issue with a short description describing how to reproduce the issue, Browser version, OS name and version here: https://github.com/gildas-lormeau/SingleFile/issues.

## Contributors
- Chinese translation done by yfdyh000 (https://github.com/yfdyh000), KrasnayaPloshchad (https://github.com/KrasnayaPloshchad)
- Japanese translation done by Shitennouji（四天王寺) (https://github.com/Shitennouji)
- Polish translation done by xesarni (https://github.com/xesarni)
- Russian translation done by rstp14 (https://github.com/rstp14)

## Code derived from third party projects used in SingleFile
- csstree: https://github.com/csstree/csstree
- postcss-media-query-parser: https://github.com/dryoma/postcss-media-query-parser
- UglifyCSS: https://github.com/fmarcia/UglifyCSS
- parse-srcset: https://github.com/albell/parse-srcset

## License
SingleFile is licensed under AGPL and GPL. Code derived from third-party projects is licensed under MIT. Please contact me at gildas.lormeau &lt;at&gt; gmail.com if you are interested in licensing the SingleFile code for a commercial service or product.

Suggestions are welcome :)
