TIEM BANH TRANG TRON - PACKAGE
- index.html: game file, offline, single HTML
- icon/tiem_banh_trang_icon_1024.png: app icon artwork

ANDROID APK:
This package is not an APK yet. Wrap index.html in an Android WebView project (for example Android Studio) and set the launcher icon to the PNG. Test on-device before publishing.

iOS versions below iOS 18:
Host index.html over HTTPS, open the URL in Safari, tap Share > Add to Home Screen, ensure Open as Web App is enabled if shown, then tap Add. A local HTML file or a dynamic Blob manifest does not provide a fully reliable installable PWA on every older iOS version. For reliable standalone app-like behavior, host it over HTTPS and use stable icon/manifest URLs; for a true App Store app, build a native wrapper.
