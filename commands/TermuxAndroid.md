## 📱 Termux-Specific Commands

```bash
termux-open https://google.com             # Open link in browser
termux-share file.txt                      # Android share
termux-clipboard-get                       # Paste from clipboard
termux-clipboard-set "Copied text"         # Copy to clipboard
termux-toast "Hi there"                    # Popup message
termux-notification --title "Note" --content "Hello" # Android notification
termux-volume music 5                      # Set music volume
termux-vibrate                             # Vibrate device
termux-camera-photo -c 0 pic.jpg           # Take photo
termux-media-player play music.mp3         # Play audio
termux-setup-storage                       # Grant storage access
termux-file-editor file.txt                # Open file in Termux text editor
termux-download https://example.com/file.zip # Download file
termux-battery-status                      # Show battery info
termux-telephony-deviceinfo                # Get device info
termux-wifi-connectioninfo                 # Show Wi-Fi info
termux-location                            # Get current location (needs permission)
termux-sensor list                         # List available sensors
termux-sensor -s proximity                 # Read proximity sensor
termux-tts-speak "Hello bro"               # Text-to-speech
termux-dialog confirm "Are you sure?"      # Confirmation dialog
termux-dialog text                         # Text input dialog
termux-toast -b bottom "Done!"             # Toast at bottom
termux-media-player pause                  # Pause media
termux-media-player stop                   # Stop media
termux-media-player info                   # Show current track info
termux-volume notification 7               # Set notification volume
termux-wake-lock                           # Prevent device sleep
termux-wake-unlock                         # Allow device sleep
termux-brightness 150                      # Set screen brightness (0–255)
termux-notification-remove 1               # Remove notification with ID 1
termux-reload-settings                     # Reload Termux settings

```
