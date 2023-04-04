## Updating the config
- Update the [customConfig.json](https://github.com/AmorphicData/white-labelled/edit/main/configuration/customConfig.json) file with required changes
- Verify changes are in effect by visting [this link](https://raw.githubusercontent.com/AmorphicData/white-labelled/main/configuration/customConfig.json)
- Reset the application state [here](https://sandbox.amorphicdata.cloud/reset)

> ** do not rename the file

## Background Images
- Visit [Unsplash](https://unsplash.com/) and search for a background images
- Landscape images are preferred
- Use discreation while selecting images
- Select the image of choice, right click on the image and select `Copy Image address` ( use this URL for `backgroundCover` images )

## Custom Configuration Options

> ** Do not remove any fields from the JSON, instead provide empty string (`""`) to make the application ignore the key and default to its native configuration

| Key | Description |
| --- | --- |
| `LOGO_PATH` | The logo to use for un-authenticated pages and when sidenav is expanded. |
| `LOGO_MARK_PATH` | The logo to use when sidenav is collapsed. |
| `PROJECT_NAME` | The project name to display, it overrides the default config project name. |
| `backgroundCover` | The background image to use for the corresponding page |
| `heading` | The heading to display on the corresponding page |
| `subHeading` | The subheading to display on the corresponding page |
| `aliases` | The alias names for service, use json format with key as service name and value as replacement name |