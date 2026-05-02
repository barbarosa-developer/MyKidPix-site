
  ---
  layout: page
  title: MyKidPix
  ---

  MyKidPix is an Android app that automatically finds photos of your children
  in your WhatsApp media folder and backs them up to your Google Photos account.

  ## How It Works

  1. **On-device face recognition** — MyKidPix uses TensorFlow Lite to detect
     and recognise your children's faces directly on your device. No photos are
     sent to external servers for analysis.
  2. **Automatic backup** — When a photo containing a recognised child is found,
     it is uploaded to a dedicated album in your Google Photos account.
  3. **Per-child albums** — Each registered child gets their own album
     (e.g. "MyKidPix – Emma"), keeping your photos organised automatically.

  ## Google Photos Integration

  MyKidPix requests the `photoslibrary.appendonly` scope to upload photos to
  your Google Photos account. This scope allows the app to:

  - Create albums on your behalf
  - Upload photos to those albums

  The app does **not** read, browse, or access any existing photos in your
  Google Photos library.

  ## Privacy

  All face recognition runs entirely on your device. MyKidPix never transmits
  your children's face data or biometric information to any server.

  See the full [Privacy Policy](privacy_policy) for details.

  ## Contact

  For support: [support-mykidpix@googlegroups.com](mailto:support-mykidpix@googlegroups.com)
  Developer: Barbarosa-Developer

  ---
