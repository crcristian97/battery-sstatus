# Battery Status App

This simple JavaScript app displays the current status of your device's battery. It provides information on battery level, charging status, and visual feedback through color-coded battery levels. This app uses the `navigator.getBattery()` API to retrieve and display battery data.

## Features

- 📊 **Battery Level Indicator**: Displays the current battery percentage.
- 🔋 **Charging Status**: Indicates whether the device is charging or not.
- 🟢 **Color Indicators**: The battery liquid is color-coded based on the battery level:
  - **Green**: Battery is above 80%
  - **Yellow**: Battery is between 48% and 80%
  - **Orange**: Battery is between 20% and 48%
  - **Red**: Battery is below 20%
- 💡 **Battery Full Status**: Shows a notification when the battery is fully charged.
- ⚠️ **Low Charge Warning**: Alerts the user when the battery is low and not charging.

## How It Works

The app uses the **Battery Status API** to track and update the battery level in real time. It applies CSS classes to the battery liquid to visually represent the battery's current charge with different colors.
