# Myki Balance Widget (Scriptable)

A handy Scriptable widget to display your Myki balance directly on your iOS home screen! Stay on top of your myki funds in the Melbourne, Australia. This relies on the PTV API but amazingly doesn't require an API key.

![IMG_99B71EED3BEB-1-preview](https://github.com/brad-tan/Myki-Balance-Widget/assets/105221827/7fe3c9d6-2d57-48c1-bd75-1b55148fb5bb)


## Features

* Displays current Myki balance
* Includes passenger type (Full Fare, Concession, etc.)
* Shows card expiry date
* Indicates zones where Myki balance is valid (trams, trains, buses)
* Top-up link for convenience

## Prerequisites

* **Scriptable App:** Download Scriptable from the App Store ([https://apps.apple.com/us/app/scriptable/id1406049200](https://apps.apple.com/us/app/scriptable/id1406049200))
* **Myki Card Number:**  Have your Myki card number handy

## Installation
**Add the Javascript script to the Scriptable app first before proceeding**  
   * Go to your iOS home screen's widget library.
   * Choose Scriptable and select the size.
   * Add the widget to your home screen.
   * Long press the widget, select "Edit Widget".
   * Choose your Myki script and set the "When Interacting" option to "Run Script".
   * **Edit 'cardNumber' parameter:** Replace the placeholder Myki card number in the `cardNumber` variable with your actual card number.

## Usage

* Your Myki balance widget will now display on your home screen.
* Tap the widget to manually refresh your balance.

## Disclaimer

This widget is not affiliated with PTV or Myki. It is intended for personal use only.
