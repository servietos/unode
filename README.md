## Servietos Community App Store for  Umbrel

This repository is created based on template at https://github.com/getumbrel/umbrel-community-app-store.

Contained apps:
chromium        Browser (working)
hello-world     Hello World (working, 1. test from template)
pi-hole         pi-hole DNS server and add blocker (working, V5.18.2/2024.03.2)
invidious       add free youtube access (not working)


## How to use (description from Umbrel's template):

1. Start by clicking the "Use this template" button located above.
2. Assign an ID and name to your app store within the `umbrel-app-store.yml` file. This file specifies two important attributes:
    - `id` - Acts as a unique prefix for every app within your Community App Store. You must start your application's ID with your app store's ID. For instance, in this template, the app store ID is `sparkles`, and there's an app named `hello world`. Consequently, the app's ID should be: `sparkles-hello-world`.
    - `name` - This is the name of the Community App Store displayed in the umbrelOS UI.
3. Change the name of the `sparkles-hello-world` folder to match your app's ID. The app ID is for you to decide. For example, if your app store ID is `whistles`, and your app is named My Video Downloader, you could set its app ID to `whistles-my-video-downloader`, and rename the folder accordingly.
4. Next, enter your app's listing details in the `whistles-my-video-downloader/umbrel-app.yml`. These are displayed in the umbrelOS UI.
5. Include the necessary Docker services in `whistles-my-video-downloader/docker-compose.yml`.
6. That's it! Your Community App Store, featuring your unique app, is now set up and ready to go. To use your Community App Store, you can add its GitHub url the umbrelOS user interface.
