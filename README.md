## Custom Argento Themes Boilerplate

 *  Copy `app` folder to your store root folder
 *  Log in to Magento backend and navigate to `Content > Themes`. You should see new themes in the list.
  > Clear cache if theme is not appeared in the list.
 *  Run the following commands in terminal to deploy static content files:
    ```bash
    bin/magento setup:static-content:deploy
    ```
 *  Navigate to `Stores > Configuration > Design` and select your new theme in `Design Theme` option dropdown.
 *  Press `Save Config` button.
 *  That’s all, now you can modify anything you’d like to, without modifiyng core Argento files.
  > **NOTE**: After enabling **CUSTOM* theme the **SwissupEditor** will not work for it.
  > It works only for native **Argento** designs.
  > Please, use custom CSS, JS, templates editing for changing custom theme look.