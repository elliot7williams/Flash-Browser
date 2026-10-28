# Flash Browser

A Visual Studio starter project for a C# / WebView2 browser with built-in Ruffle Flash support.

## Project backup

Download [Custom_Flash_Browser_Visual_Studio.zip](./Custom_Flash_Browser_Visual_Studio.zip) and extract it. Open `FlashBrowser.sln` in Visual Studio on Windows with the .NET 8 SDK and WebView2 Runtime.

The archive includes the browser project, bundled Ruffle web runtime, Ruffle source snapshot, branding-defaults patch, rebuild script, and local SWF/embed test fixtures. Ruffle license notices are retained.

## Implemented

- Open local SWF files and route direct HTTP(S) .swf URLs to the player.
- Detect legacy object/embed Flash elements.
- Neutral playback controls with Ruffle splash and context menu disabled.
- Local SWFs are served individually through session tokens.

## Validation status

JavaScript integration checks passed. Windows compilation and WebView2 playback were not verified in the build environment. See the archive's README.md for requirements, limitations, and Windows smoke checks.

## Visibility

This repository is public. The project archive and this README are therefore publicly viewable.
