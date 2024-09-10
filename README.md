# Significant points of publication Android application to Play market

You should start by registering a developer account [documentation](https://support.google.com/googleplay/android-developer/answer/6112435). It is important to register an **organizational** developer account, not a personal developer account.

The process of creating a new application is described in Google Help [documentation](https://support.google.com/googleplay/android-developer/answer/9859152).
Essentially, you need to click through several forms, answering questions about the purpose of the application and compliance with numerous legal requirements.
To design the application page, you will need to prepare screenshots from the device and other graphic resources.

Important notes that must be taken into account. Without them, you will be denied publication. Remember that before publication the application will be reviewed by attentive and picky people in Google.

1. When designing an application page, it is important to upload screenshots taken specifically from your application. You will not pass the review if the application interface does not contain the screens that you provided in the screenshots.
2. If you request **Local notifications** feature in questionare, for the **Foreground service permissions** section, you need to record a video from the screen and say the following text out loud: "We use foreground service permissions for a background service to receive notifications from our video server when there is no Internet. This is a replacement for push notifications for a local network."
3. In the **Advertising ID** section, indicate that you use advertising ID for **analytics**.
4. For the **Data safety** and **Privacy policy** sections, you will need to place the text of the privacy policy **on your site** and provide a link to this page.
5. Filling out the **Content ratings** section is possible only after uploading the application assembly to the release draft.
6. If your application does not have a demo server, Google may require a test account to check the application. Pass them this data to connect: URL http://136.243.144.109:8000/asip-api, login root, password root.
7. If you registered a personal account instead of an organizational account, before publishing the application, you will have to perform closed testing. At least 20 devices must take part in it for at least 14 days in a row. Testing on simulators will not work, real devices are needed. Google suggests looking for them almost on the street, looking for volunteers among friends, acquaintances and on forums. You need to create a list of tester device accounts in the console. After publishing the application in the closed testing channel, send the testers a link to the application so that they install it. Details [documentation](https://support.google.com/googleplay/android-developer/answer/14151465). The most absurd requirement. 

_Ask questions about any unclear aspects of the publication, and we will immediately supplement this instruction with answers_