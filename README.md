## Custom Argento Themes Boilerplate

  > **WARNING!** Make sure you have no such folders already or your previous
  > customizations can be rewritten !!!

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

  > **NOTE**: Theme editor will not work for custom theme.
  > Please enable it explicitly using our [manual](https://docs.swissuplabs.com/m2/argento/customization/custom-theme/#enable-theme-editor-for-custom-theme)
