The entire Vivaldi UI can be configured with custom CSS. In order to do this we need:

1. Go to vivaldi://experiments/ and enable 'Allow CSS modification'
2. Open Vivaldi Settings > Appearance > Custom UI modifications and select folder that contains css styles

we can use this repo as the folder, but if we want to adjust some specific button, input, bar etc., we can go to `vivaldi:inspect/#apps` and click on either first or second Inspect button (it depends). Now we can Inspect our Vivaldi styles like a usual webpage. Don't forget, Vivaldi needs to be restarted after every css change.

In my case I don't do Vivaldi styling only with CSS. I use Vivaldi's ability to import themes as zip files.
If we go to Settings -> Themes, we can see button to export one of Vivaldi's predefined themes. If we do it with one of default themes (for example "Dark") and unzip the file, we will see settings.json and bunch of svg icons. We need to copy all the svg files into this repository, zip everything and import into Vivaldi Themes. we should see a new theme called "My Theme". Now all the needed colors, sizes etc. are actually applied.
