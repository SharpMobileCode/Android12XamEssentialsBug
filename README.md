# Description
On an Android 12 device or emulator, the `Permissions.RequestAsync<Permissions.LocationWhenInUse>()` call returns `PermissionStatus.Denied` when user selects "Approximate" location.

# Steps To Reproduce
1. Clone or download this repo.
2. Run the Android application on an Android 12 device or emulator.
3. Tap the "Request Location Permission" button.
4. Select "Approximate".
5. Select "While using the app" or "Only this time".

# Expected Result
Returns `PermissionStatus.Granted`.

# Actual Result
Returns `PermissionStatus.Denied`

