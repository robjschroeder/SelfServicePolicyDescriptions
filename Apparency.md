<!-- Keywords: Apparency, macOS, app inspector, security, Gatekeeper, notarization, app components, entitlements, code signature -->

# WHAT HAPPENS WHEN YOU OPEN THAT APP?
macOS checks every app against a slew of security features: Gatekeeper, notarization, hardening, entitlements and more. But it doesn't show you the result of these checks, preferring to keep these behind the scenes — either the app opens or it doesn't, perhaps with an “app downloaded from the internet” dialog first.

Even “code signatures” — around since Mac OS X 10.5 (Leopard!) — are visible only via arcane Terminal incantations.

# WHAT'S INSIDE THAT APP?
Today's macOS apps are often made up of many pieces. Some of these are organizational artifacts, of interest only to the developers.

But some pieces of an app can extend macOS itself — Share Extensions, Today Widgets, Safari Extensions, Quick Look generators, Spotlight importers, and so on. macOS lets you see and manage some of these, but not all of them, and not all in one place.

# ENTER APPARENCY — THE APP THAT OPENS APPS.
Control-click on an app in the Finder, choose Open With Apparency, and see all the details in one place:

## APP CONTENTS
- See identifiers and versions
- Browse “components” inside
- See document types and URLs
  
![App Contents](https://mothersruin.com/software/Apparency/images_dark/feature-contents.png)


## SECURITY FEATURES
- What did Gatekeeper say?
- Was it notarized?
- Is App Sandbox enabled?
- Inspect the code signature
- Browse entitlements

![Security Contents](https://mothersruin.com/software/Apparency/images_dark/feature-security.png)

## AND MORE
- Browse the Info.plist
- Find the executable
- See macOS version info
- Inspect linked frameworks

![And More](https://mothersruin.com/software/Apparency/images_dark/feature-other.png)

## OR GET A QUICK LOOK
You can also get a Quick Look at some of the same information: Quick Look preview
![Quick Look](https://mothersruin.com/software/Apparency/images_dark/feature-ql.png)
