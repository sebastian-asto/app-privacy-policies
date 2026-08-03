# Battery Runtime Calculator Privacy Policy

**Effective date:** August 3, 2026

**Version:** 1.0

## 1. Developer identity

Battery Runtime Calculator is developed and published by **Sebastian Asto**, a developer located in **Peru**.

## 2. About the application

Battery Runtime Calculator is a technical calculator that estimates battery runtime using values provided by the user. The application can account for battery capacity, the device's average current consumption, system efficiency, usable capacity, and a safety margin.

The results are technical estimates. Actual runtime may vary due to factors such as usage conditions, temperature, battery condition, component tolerances, and changes in the device's power consumption.

## 3. Information Battery Runtime Calculator collects

Battery Runtime Calculator does not collect or transmit personal data, device data, or application usage data off the device. It does not request a name, email address, phone number, physical address, credentials, or device identifiers. It also does not provide accounts or sign-in functionality.

## 4. User-provided data

To perform a calculation, the user may enter or select:

- nominal battery capacity and its unit;
- the device's average current consumption and its unit;
- system efficiency percentage;
- usable capacity percentage; and
- whether to apply a safety margin and its percentage.

These are technical values. Battery Runtime Calculator uses them only to calculate and display an estimated runtime.

## 5. On-device processing

All entered values and results are processed exclusively on the device. Battery Runtime Calculator does not send them to the developer or to third-party servers.

Calculation data is held temporarily in the application's memory during the session. It is not saved persistently and may be lost when the application is closed or restarted, or when the operating system terminates its process.

## 6. Internet access

Battery Runtime Calculator works entirely without an Internet connection. The production Android version does not request Internet permission, and the application code does not make network requests.

The Android development manifests (`debug` and `profile`) include Internet permission solely for Flutter development tools such as debugging and hot reload. This permission is not part of the production version intended for Google Play.

## 7. Device permissions

Battery Runtime Calculator does not request sensitive or runtime permissions to access location, camera, microphone, contacts, files, shared storage, or Bluetooth.

The production Android package may include standard technical components from Flutter and AndroidX, including an internal `signature`-level permission related to protected receivers and a package-visibility declaration for applications capable of processing text. These elements do not give Battery Runtime Calculator access to the sensitive data listed above and are not used to transmit information off the device.

## 8. Local storage

Battery Runtime Calculator does not use local databases, `SharedPreferences`, secure storage, or files to retain entered values, results, or the selected language or theme. These settings exist only in memory while the application is running.

## 9. Third-party services and components

Battery Runtime Calculator uses Flutter for its interface and operation, `flutter_localizations` for localization, and `intl` for locale-aware number formatting. The Android version also bundles standard AndroidX compatibility and lifecycle components as part of the Flutter platform.

The observed use of these components in Battery Runtime Calculator is limited to the interface, localization, number formatting, and application support. No online service or third-party SDK has been configured to collect or transmit data.

Battery Runtime Calculator does not integrate Firebase, AdMob, authentication services, social platforms, or other external services.

## 10. Advertising, analytics, and error reporting

Battery Runtime Calculator does not display advertising and does not use analytics, tracking, profiling, or remote error or crash-reporting services.

## 11. Security

Battery Runtime Calculator reduces exposure of entered technical data by processing it locally, without transmitting it and without retaining it in persistent storage controlled by the application. Protection of the device and physical access to it depends on the operating system's security measures and the settings chosen by the user.

## 12. Children's privacy

Battery Runtime Calculator is a general-purpose technical tool and is not designed to collect personal information from children. Because the application does not collect or transmit personal data from its users, it also does not knowingly collect children's personal data.

## 13. Changes to this policy

This policy will be updated if Battery Runtime Calculator changes how it processes information or adds features such as advertising, analytics, accounts, online services, persistent storage, or new SDKs. The updated version will state its new effective date.

## 14. Contact

For questions about this policy or privacy in Battery Runtime Calculator, please contact:

**Sebastian Asto**  
**Email:** marseapps@gmail.com  
**Country:** Peru
