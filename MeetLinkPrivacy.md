# Privacy Policy for MeetLink

Effective Date: September 18, 2026  
Publisher: Freist Li

This Privacy Policy explains how MeetLink accesses, uses, stores, and discloses information when you use the application.

MeetLink is a local Windows desktop application. It does not include advertising, analytics, an account service, or a publisher-operated server that collects your Profiles, device information, recordings, camera images, or meeting links. The publisher does not sell this information.

## Information Collection and Use

MeetLink accesses information from Windows that is necessary to show and control your meeting devices. This may include:

- Audio endpoint identifiers, names, connection status, default roles, volume, and mute state.
- Bluetooth adapter status and the names, addresses, and connection status of paired Classic Bluetooth audio devices.
- Camera identifiers and labels used to populate Profile choices and select a local preview device.
- Profile names, selected devices, optional HTTPS meeting links, and application preferences that you choose to save.

This information is processed locally on your device. MeetLink does not transmit it to the publisher.

## Microphone, Camera, and Audio Tests

MeetLink accesses your microphone only when you explicitly start a microphone test. The test records up to five seconds of audio for local playback. The recording remains in application memory and is discarded when you stop the tests, hide the window, or exit the application. MeetLink does not save or upload the recording.

MeetLink accesses your camera only when you explicitly start a camera preview. Video is displayed locally and is not recorded, saved, or uploaded by MeetLink.

The speaker test plays a locally generated test sound through the current output device. Windows permissions, device drivers, and enterprise policies may restrict access to these features.

## Bluetooth and Windows Device Control

MeetLink uses Windows audio and Bluetooth interfaces to enumerate devices, request a connection to a paired Classic Bluetooth headset, optionally request that Bluetooth be enabled, and change selected audio defaults, volume, or mute state. These actions affect Windows and may affect other applications that use the same devices.

MeetLink does not pair or unpair Bluetooth devices. Pairing and related consent are handled by Windows.

## Local Data Storage

Profiles and preferences are stored in a local `profiles.json` file in MeetLink's Windows user-data directory. Stored information may include Profile names, device identifiers, Bluetooth addresses and names, camera labels, optional meeting URLs, language and startup preferences, and the active Profile identifier.

MeetLink does not encrypt this file. Do not put passwords, access tokens, or other secrets in Profile names or meeting links. Other users or administrators with access to your Windows account or files may be able to read it. Operating-system backups and enterprise management tools may copy local data independently of MeetLink.

MeetLink does not use browser cookies or provide cloud synchronization for Profile data.

## Network Access and Third-Party Services

MeetLink does not use a publisher-operated backend and does not contain advertising or analytics services.

If you choose **Join meeting**, MeetLink passes the saved HTTPS meeting link to your default browser or registered application after the device switch succeeds. The destination service may receive the link and information normally provided during a network connection, such as your IP address, and will process that information under its own privacy policy. MeetLink does not operate or control that service.

Microsoft Store, Windows, your default browser, meeting providers, and Electron/Chromium components may process diagnostic or service data independently under their own policies and your system configuration. For more information about Microsoft products and services, see the [Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement).

## Log Data and Support

MeetLink does not automatically send telemetry, crash reports, or application logs to the publisher. Errors and device diagnostics may be displayed locally. Windows, device drivers, enterprise management software, or runtime components may create or transmit event logs, crash dumps, or diagnostics according to their own settings and policies.

If you voluntarily contact support, the publisher and the service you use to send the message will process the information you provide to respond to your request. Do not include meeting links, recordings, device identifiers, passwords, or other sensitive information in a public support request.

## Service Providers

MeetLink may be distributed through Microsoft Store and relies on Windows platform services for installation, permissions, device access, and optional operating-system diagnostics. Those services are provided independently by Microsoft and are governed by Microsoft's terms and privacy statements.

Any browser, registered application, or meeting service that you choose to open through MeetLink is a separate third-party service. Review that service's privacy policy before using it.

## Security

The publisher uses reasonable measures within the application to limit access to the functions MeetLink needs. However, no method of electronic storage or transmission is completely secure. Security also depends on your Windows account, device configuration, installed software, backups, and the third-party services you choose to use.

## Links to Other Sites

MeetLink may open meeting links or Windows settings pages at your request. External sites and applications are not operated by the publisher. The publisher has no control over and assumes no responsibility for their content, privacy policies, or practices.

## Children's Privacy

MeetLink is not directed to children under the age of 13, and the publisher does not knowingly collect personal information from children through the application. If a child contacts the publisher for support and provides personal information, a parent or guardian may contact the publisher to request its deletion, subject to applicable legal obligations.

## Data Retention and Deletion

Local Profile data remains on your device until you delete it. Delete a Profile in MeetLink to remove that Profile's saved settings. To remove all MeetLink settings, exit the application from the system tray and delete its user-data directory. Store installations may use a package-specific or redirected directory under your Windows profile.

Microphone test recordings are retained only in memory for the local test and are discarded as described above. Camera previews are not recorded by MeetLink.

Uninstalling MeetLink may not remove every backup, cache, event log, or crash dump retained by Windows or enterprise systems. Review those systems separately. Information sent to a meeting provider or support service is retained according to that provider's policy.

## Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. Changes will be posted on this page with a revised effective date and will take effect when posted.

## Contact Us

For questions or suggestions about this Privacy Policy, contact [freistli@outlook.com](mailto:freistli@outlook.com).
