# Asteroid Field

<img width="681" height="670" alt="Screenshot 2026-10-25 at 11 11 37 AM" src="https://github.com/user-attachments/assets/393f89d1-6968-43ec-b616-d4f1010861d2" />


Asteroid field is my take on the 1979 game "Asteroids." It was built using SFML for the graphics, user input, music and SFX outputs and DearImGui for the UI.

All game art was created by csbees, and all SFXs were created by csbees
Music were created by [AlkaKrab](https://alkakrab.itch.io/), and are royalty-free.

## Known Issues

- The UI does not scale, or adjust properly when the game window is resized
- When the game window is resized, to a ratio that is not 1:1, and the game art looks stretched or squashed
- Big asteroids do not leave the screen completely before deleting
- The MacOS build does not have a Developer ID
- The Windows build's window is to small, magnifying previous issues 
  
## FAQ

_**Will I fix these things?**_

no.

_**How do I run the MacOS build?**_

run `xattr -r -d com.apple.quarantine "pathto/Asteroids.app"` in the terminal, removing its' protections.
Open "Asteroids.app" in the terminal, and run `cd Contents/MacOS; ./Asteroids`

Should you do this? Probably not, at least I wouldn't. Removing all the save guards of a random file you got from the internet, and then running it? Sounds thing a stupid thing to do. Mind you, the builds _are_ safe, but you can never be too careful.

**_What's the License on this Project?_**

You're free to play, modify and use for educational purposes. Just be sure to credit me. You are **_not_** free to sell this code, any of the builds, or assets, regardless of whether it's been modified or not.

