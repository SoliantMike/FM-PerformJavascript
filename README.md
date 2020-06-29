# FM-PerformJavascript

This sample file has a few examples of the Javascript functionality in FileMaker 19+. The scripting and UI is kept minimal in order to demonstrate the low amount of code required to get good functionality when working with Javascript in a FileMaker Web Viewer. 

There is a new script step "Perform JavaScript in Web Viewer" where you can call a function in the HTML/Javascript page that is currently loaded in a web viewer, and optionally pass in parameters.

Conversely, there is a Javascript function that you can use from within the loaded HTML/Javascript to call a FileMaker script and pass it parameters as well.

There is no dependency on FMP URLs, which is how you would have done some of this before.

This makes it very easy to interact between the two scripting environments. It also is supported across the FileMaker Platform, which includes WebDirect. 

There are two examples shown:
 <ol>
 <li> A simple HTML Editor that uses Tiny MCE. (https://github.com/tinymce/tinymce)
 <li> Signature Capture that will save a PNG to a container field. (https://github.com/szimek/signature_pad)
 </ol>
