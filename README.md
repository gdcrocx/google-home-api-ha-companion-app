# Google Home - Home Assistant Companion app 🚧

Status - `In Development`

### Problem
- Google Home APIs can only be used from an Android environment. [There isn't a REST API endpoint planned for the near future](https://www.googlenestcommunity.com/t5/Smart-Home-Developer-Forum/Will-the-Google-Home-APIs-be-available-as-a-direct-REST-API-without-the/m-p/668079).
- Home Assistant does not have visibility to legacy, non-Matter supported IoT devices that support Google Home, without the use of Tasmota or similar tools and/or further development.
- Google Home Runtime isn't integrated with Home Assistant yet.

### Solution

- Build a Google Home API Android app to act as a bridge between Google Home and Home Assistant until the time Home Runtime is built into Home Assistant.

The *Google Home - Home Assistant Companion App*  will be running in a container environment, acting as a bridge between Google Home and Home Assistant using MQTT, much like Frigate and other bridge-type HACS integrations.

> This might be a temporary solution until the time that at least one of the above-mentioned problem definitions is fixed.

### Disclaimer

By using the Google Home - Home Assistant Companion App ("App"), you acknowledge and agree to the following terms:

No Warranty: This App, nor its derivatives, are provided "as-is" and without warranties of any kind, either express or implied, including but not limited to the implied warranties of merchantability, fitness for a particular purpose, or non-infringement. The developer makes no representation or warranty that the App will meet your requirements, operate without interruptions, or be error-free.

Hardware Compatibility: The App, nor its derivatives, may not be compatible with all hardware devices, and the developer cannot guarantee that it will function properly on every device or with all versions of the Android operating system. The developer is not responsible for any malfunction, damage, or loss of data arising from the use of the App on any hardware or device.

Limitation of Liability: In no event shall the developer, nor its derivatives, be liable for any direct, indirect, incidental, special, consequential, or punitive damages, or any loss of profits, revenue, data, or use, incurred by you or any third party arising from the use, inability to use, or any failure of the App, regardless of whether such damages are based on contract, tort, or any other legal theory.

Indemnification: You agree to indemnify and hold harmless the developer, nor its derivatives, from any claims, damages, liabilities, costs, and expenses (including legal fees) arising out of your use or misuse of the App, or any breach of this disclaimer.

Software or Hardware Failures: The developer, nor its derivatives, shall not be responsible for any software or hardware failures, system crashes, or data loss resulting from the installation or use of this App. It is the user's responsibility to ensure regular backups and take appropriate precautions to prevent data loss.

By installing and using this App, you acknowledge that you have read, understood, and agree to this disclaimer.
