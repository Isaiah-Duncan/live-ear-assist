# Live Ear Assist

An assistive test app. A phone camera watches a screen, Gemini reads any question it sees, and the app responds only if the question matches an entry in your own list. The answer arrives as vibration taps (and optional voice).

## Use
1. Open the published link in Safari (iPhone) or Chrome (Android).
2. Tap the gear, paste your Gemini API key in the Key tab, press Test connection.
3. Add your questions in the Questions tab.
4. Press Start and aim the camera at the screen.

## Safety notes
- Never write your API key into `index.html`. Paste it in the app; it stays in the browser on that device only.
- Do not put real patient details into this repository. Questions typed in the app stay on the device.
- Each AI check sends one camera image to Google. Use only with the patient's agreement.
- This is an assistive test, not a medical device.
