WEBAR PROTOTYPE — HAWKN TECH CONCEPT

Files expected in this folder:
- index.html
- Web_AR-Character-Combined.glb (page model, with both animation clips)
- Web_AR-Character_Idle.glb (default tracked character and idle animation)
- Web_AR-Character_Gangnam_Style.glb (alternate dance animation asset)
- Web-AR Image Target.png
- targets.mind (compiled from the poster image)
- Gangnam Style Audio.mp3 (local soundtrack)

NEXT REQUIRED ASSET STEP
1. Open the MindAR Image Targets Compiler:
   https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2. Add "Web-AR Image Target.png" and start compilation.
3. Check the feature point preview, then download the compiled file.
4. Save/rename that download as targets.mind in this folder.

The page starts with a Start the experience button. On tap, it requests camera access and scans for the compiled poster. When found, Maya's idle clip and the local soundtrack play. Tap Maya to switch to the Gangnam dance; tap again to return to idle. Use the single Mute/Unmute control on her ID card for sound. Tap the numbered poster markers to read about Hawk'N services, and use the card link to open the official website.

For camera access, serve this page over HTTPS (or localhost for a same-computer preview). The final QR should be generated only after the HTTPS page URL is stable.

