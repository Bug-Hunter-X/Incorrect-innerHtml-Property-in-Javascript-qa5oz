# Uncommon HTML Error: Incorrect innerHtml Property

This repository demonstrates a common error in HTML/Javascript programming.  The error arises from a simple typo in the `innerHTML` property.  Many developers, especially beginners, commonly misspell it as `innerHtml`, leading to runtime errors. This repo showcases the error and its solution.

## Bug Description
The code attempts to change the content of a div element using Javascript. It mistakenly uses  `innerHtml` instead of the correct `innerHTML` property. 

## Solution
The solution simply corrects the typo, replacing `innerHtml` with `innerHTML` in the Javascript code.

## How to reproduce:
1. Open the file bug.html in a web browser.
2. Observe the console error in the browser's developer tools (usually accessed by pressing F12).