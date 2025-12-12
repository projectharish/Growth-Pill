# App Icon Setup Instructions

## To add your anime character as the app icon:

1. **Save your anime character image** as `app_icon.png` in this folder
2. **Image requirements:**
   - Size: 1024x1024 pixels (recommended)
   - Format: PNG with transparent or black background
   - Your anime character should be clearly visible

3. **Your anime character description:**
   - Young man with medium-dark skin tone
   - Dark spiky hair
   - Dark beard and mustache
   - Looking over his left shoulder in profile
   - Wearing a dark t-shirt
   - Black background
   - Anime art style

4. **After adding the image, run these commands:**
   ```bash
   flutter pub get
   flutter pub run flutter_launcher_icons:main
   ```

This will generate all the necessary icon sizes for Android and iOS.

## Current Status:
- ✅ Assets directory created
- ✅ Icon configuration ready in pubspec.yaml
- ⏳ Waiting for your app_icon.png file


