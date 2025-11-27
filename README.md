The entire Vivaldi UI can be configured with custom CSS. In order to do this we need:

1. Go to vivaldi://experiments/ and enable 'Allow CSS modification'
2. Open Vivaldi Settings > Appearance > Custom UI modifications and select folder that contains css styles

You can use this repo as the folder, but if you want to adjust some specific button, input, bar etc., you can go to `vivaldi:inspect/#apps` and click on either first or second "Inspect" button (it depends). Now we can Inspect our Vivaldi browser styles like a usual webpage. Don't forget, Vivaldi needs to be restarted to apply css change.

In my case I don't do Vivaldi styling only with CSS. I also use Vivaldi's ability to import themes as zip files.
If you go to Settings -> Themes, we can see button to export one of Vivaldi's predefined themes. If you do it with one of default themes (for example "Dark") and unzip the file, you will see settings.json and a bunch of svg icons. We need to copy all the svg files into this repository, zip everything and import into Vivaldi Themes. You should see a new theme called "My Theme". Now all the needed colors, scales etc. are actually applied.
<img width="1920" height="1080" alt="image_2025-11-20_20-36-40" src="https://github.com/user-attachments/assets/fe6bda1b-55f2-4903-9313-74c61f31ed1f" />
<img width="1920" height="1080" alt="image_2025-11-20_20-38-29" src="https://github.com/user-attachments/assets/15b04c54-2a53-4e1d-8934-45e79e701db1" />
