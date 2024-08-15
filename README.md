<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/12a6a5bc-3c3f-4418-a6ea-8f64e84b47ab">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/a8036767-c839-4766-87cf-bda21767ed5e">
  <img alt="Speedo Logo" src="https://github.com/user-attachments/assets/12a6a5bc-3c3f-4418-a6ea-8f64e84b47ab">
</picture>


# Welcome to Speedo App!
A Material Design inspired speedometer app for Android!

## Accuracy and Location
- The accuration is depending on your device. So, there is no going to send some bad feedbacks.
- Speed is multiplied by value. so maybe it will become accurate for some reason.

## Features
- When it comes to customization, 12 different backgrounds, 4 meter dial themes, 7 meter labels in **2 digits and 3 digits**, 4 meter pointers, and 8 distance meter fonts. 
- For orientations, 5 mode option will be applied.
- It supports landscape mode.
- You can also get the location icon by clicking the **Settings > Get Location.**
- Has Reset Location system feature by **long-pressing the power button on the app and click it.**
- Profile and stats included. No need to sign in to the internet. Just set it up and you're all set!
- On the Go and Ready to use.

## Monitoring
You will only monitor the **Latitude and Longitude, Altitude, and Distance** coordinates. But you can also monitor the **Accuracy, Time and Bearing**.

## Distance Meter Calculation
In order to show the meter to be accurated, I make some math calculation while assembling the code blocks.

`speed * multiplyByValue`

But it seems to have some problems, the issue #1 shows some consistencies whie testing. so this time before 6.48, I did this:

`speed.format as decimal - places = 0 ` *
`3.865`

## Tips to use
- The speedometer on the app will be inaccurate in compared with the *actual car speedometer* in certain Android Devices. 
- If you have a bicycle to use with the speedometer, Be sure to have a protective tripod to prevent you device from **falling** especially if you are riding in mountains, rough roads, or some dangerous places.
- Use this app if you're wondering that your actual speedometer is damaged or not working anymore.
- You can use both speedometer in you device and the actual car.
