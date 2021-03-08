## Description

This repository contains the Android Xamarin Native and Xamarin Forms source code for a sample browser app that uses the MAM SDKs for endpoint management.  It does not contain the [MAM SDK](https://docs.citrix.com/en-us/mdx-toolkit/mam-sdk-overview.html) libraries themselves, which are downloaded separately.

## Download

The MAM SDK libraries can be downloaded from [MAM SDKs and Toolkit](https://www.citrix.com/downloads/citrix-endpoint-management/product-software/mdx-toolkit.html).

## Notes

This sample browser app is designed to make it easy for you to test the Micro VPN functionality of the MAM SDK. Note that by default it only allows HTTPS connections, and if you'd like to connect to an HTTP web page then you will need to modify `android:usesCleartextTraffic="false"` in the AndroidManifest.xml file.

## Documentation

For detailed documentation on how to use this sample app, and compile it, see the [MAM SDK for Android Xamarin Overview](https://developer.cloud.com/citrixworkspace/mobile-application-integration/xamarin-android/docs/overview).  Documentation is also included in the MAM SDK download package.

## Questions

For questions and support:

-  [StackOverflow [citrix] [mdm] tags](https://stackoverflow.com/questions/tagged/mdm+citrix)
-  [Citrix Discussion Forum](https://discussions.citrix.com/forum/1797-mobile-app-management-mam/)

## License

[MIT License](./LICENSE)
