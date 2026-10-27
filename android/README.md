# LH44 — Android app

Jetpack Compose port of the Figma export (`PhoneView`).

## Get the APK (cloud build, no Android Studio needed)
1. Create an empty GitHub repo and upload everything in this folder (keep the `.github` folder).
2. Open the repo's **Actions** tab → **Build APK** → wait for the green tick (about 5–8 min the first time).
3. Open the finished run → **Artifacts** → download **lh44-debug-apk** → unzip → `app-debug.apk`.
4. Copy it to your phone and install (allow "install unknown apps" when asked).

If the run goes red, open it and copy the first red error line — that's all that's needed to fix it.

## Or build locally
Open this folder in Android Studio → **Build > Build APK(s)**.

## Replacing the placeholder photos
`app/src/main/res/drawable/` has five grey/colour placeholder PNGs:
`trackimage`, `nightrace`, `redmachine`, `portrait`, `circuitaerial`.
Overwrite each with your own image using the **same file name** (png or jpg; if you use jpg, delete the matching png).
