=â Use this project, [contribute](https://github.com/vtex-apps/onesignal) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# OneSignal

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

OneSignal first party integration app. The [solution](https://onesignal.com/) provides web push notifications for customer engagement.

![notification](https://user-images.githubusercontent.com/284515/88438151-68a06f80-cdde-11ea-8624-2626d8464f5d.png)

## Configuration

It is possible to install the app in your store either by using the VTEX App Store or the VTEX IO Toolbelt.

### Using VTEX App Store

1. Access the **Apps** section in your account's admin page and look for the OneSignal box.
2. Click on the **Install** button.
3. You'll see a warning message about needing to enter the necessary configurations. Scroll down and type in your **App ID**.
4. Click on **Save**.

### Using VTEX IO Toolbelt

1. [Install](https://vtex.io/docs/recipes/development/installing-an-app/) the `vtex.onesignal@1.x` app. You can confirm that the app has now been successfully installed by running the `vtex ls` command. 
2. Access the **Apps** section in your account's admin page and look for the OneSignal box. Once you find it, click on the box.
4. You'll see a warning message about needing to enter the necessary configurations. Scroll down and type in your **App ID**.
5. Click on **Save**.

<div class="alert alert-info">
The App ID works as an account identifier and should be provided by the OneSignal solution. 
</div>

<div class="alert alert-warning">
To successfully use this native integration in your store, you will need to <a href="https://vtex.io/docs/recipes/store-management/deactivating-the-vtex-io-native-service-worker/">deactivate the native service worker provided by VTEX IO</a>.
</div>

<!-- DOCS-IGNORE:start -->
## Contributors (

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
<!-- DOCS-IGNORE:end -->


**Upcoming documentation:**

 - [Feat/service worker builder](https://github.com/vtex-apps/onesignal/pull/3)