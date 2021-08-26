# poqrtal

A silly "browser" that can only navigate by scanning QR codes.

This is useful for iOS users who prefer to use their phone without Safari enabled, but need to be able to open contact tracing or other specific links presented as QR codes.

## Installation on iOS

1. Enable Safari
2. Navigate to https://knuton.github.io/poqrtal/
3. Add the page to your homescreen ([instructions](https://www.lifewire.com/home-screen-icons-in-safari-for-iphone-and-amp-ipod-touch-4103654))
4. Disable Safari in Screen Time

This tool uses the fact that standalone progressive web apps, once installed, can be used even when Safari is disabled.

## Usage

UI is kept to a minimum as I just took some minutes before work to throw this together. When the app loads it should prompt for permission to use your camera. It tries to select the back-facing camera and starts scanning for QR codes. If any HTTP(S) address is detected, it will immediately load it. The app does not currently report any errors.

## Acknowledgements and License

This app is possible by using the well-documented [nimiq/qr-scanner](https://github.com/nimiq/qr-scanner) (MIT).

Licensed under MIT.
