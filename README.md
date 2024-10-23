# Location Scoring Logic

There are two ways to earn points at a location:
1. **Scanning the QR code** at the corresponding location.
2. **Proximity-based scoring**: Each location is represented as a circle with a 50-meter radius on the map. When a user enters this radius, they will earn points, and the circle will change color to blue. If the user visits a location by scanning the QR code, the circle will also turn blue on the map.

# Home Screen Logic

The HomeScreen page uses similar logic to detect the user's real-time location and compare it with the stored locations. If the user enters a location's radius, the relevant location information will be displayed. 

> **Note:** Real-time location tracking is used, so it is recommended to test this on a real device. The location refresh logic in simulators can cause repetitive refreshes, leading to inconsistent content display.

# Project List Page

On the ProjectList page, you can refresh the project list by pulling down the screen. This will update the participant count for each project.

# Testing Information

- **Project Name**: `BNE StoryPath`
    1. **Location Name**: `BNE D Terminal`
       - **Position**: `(-27.384068, 153.120577)`
       - **Points**: `10`
       - **QRCode**: https://github.com/NarIyirm/comp2140-qrcode/blob/52a1ddb2d676b78c430fb9c332597343790acd19/BNE%20D%20Terminal%20QRCode.png
    2. **Location Name**: `Roma Street Station`
       - **Position**: `(-27.464731, 153.019171)`
       - **Points**: `10`
       - **QRCode**: https://github.com/NarIyirm/comp2140-qrcode/blob/52a1ddb2d676b78c430fb9c332597343790acd19/Roma%20Street%20Station%20QRCode.png

# Important Note

Please **create a username** before testing the application.