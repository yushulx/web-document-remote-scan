# Web Document Remote Scan
The sample shows how to scan documents from remote document scanners in mobile web browsers.

## SDK Download
- [Dynamic Web TWAIN 17.1](https://www.dynamsoft.com/web-twain/downloads)


## Get a 30-day Free Trial License
Apply for a [trial license](https://www.dynamsoft.com/customer/license/trialLicense).

![DWT trial license](https://www.dynamsoft.com/blog/wp-content/uploads/2021/02/dynamic-web-twain-trial-license.png)

## How to Configure Remote Document Scanners with IP Address
1. Connect document scanners to a PC and install [Dynamic Web TWAIN SDK](https://www.dynamsoft.com/web-twain/overview/). If you don't have a document scanner, you can install the [virtual scanner](https://download.dynamsoft.com/tool/twainds.win32.installer.2.1.3.msi) for development and test.
2. Open `http://127.0.0.1:18625/admin/` in your web browser.
3. Configure the IP address and ports.

    ![Dynamsoft service configuration](https://www.dynamsoft.com/blog/wp-content/uploads/2021/02/dynamsoft-service-configuration.png)


## Deployment
1. Copy `Resources` folder from `Dynamsoft\Dynamic Web TWAIN SDK <version> \Resources` to the project root directory.

2. Update the license key in JavaScript:

    ```js
    Dynamsoft.WebTwainEnv.ProductKey = 'LICENSE-KEY';
    ```

3. Set up an HTTP server quickly using Python:

    ```
    python -m http.server
    ```

4. Open the web document scanning app in mobile browsers:

    <kbd><img src="https://www.dynamsoft.com/blog/wp-content/uploads/2021/01/web-document-remote-scan.jpg" width="50%">

    The image viewer contains images captured from remote document scanners and the mobile camera.

## Blog
[How to Build a Universal Document Scanning App in HTML5](https://www.dynamsoft.com/codepool/mobile-scanner-camera-document-capture.html)
