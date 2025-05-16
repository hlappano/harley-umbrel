## Harley Umbrel Community App Store
This repository is more of a personal apps that I use for my Umbrel OS. Please don't expect constant updates. If you like what I have done, you can fork it or copy it.

This repository came from a template created from Umbrel Community App Store. These additional app stores allow developers to distribute applications without submitting to the [Official Umbrel App Store](https://github.com/getumbrel/umbrel-apps).

## Apps
| App Name                                               | Version | Port  | Notes                   |
| ------------------------------------------------------ | ------- | ----- | ----------------------- |
| [Jellyfin](https://jellyfin.org/)                      | 10.10.7 | 8097  | Changed the port number it doesn't interfere with Umbrel's Apps. |
| [Tiny Media Manager](https://www.tinymediamanager.org) | 5.0.5   | 8098  | Runs application within VNC viewer |
| [Actual Budget](https://actualbudget.org/)             | 25.5.0  | 8099  | None                    |
| [Open TTS](https://github.com/synesthesiam/opentts)    | 2.1     | 8100  | Some voices can be a resource hog with the RAM, so unfortunately, this doesn't work well with 8GB. For additional custom parameters, [App.py Source](https://github.com/synesthesiam/opentts/blob/master/app.py) and review the paremeters.You can modify the docker-compose.yml and add the arguments e.g. command: ["--no-espeak"] |
| [Mimic 3 TTS](https://github.com/MycroftAI/mimic3)     | 0.0.4   | 8101  | Added patch files in volume mount to fix the download voices |
| [Piper Hub](https://github.com/hlappano/Piper-Hub)     | 1.1.1   | 8102  | None                    |

## How to use:
https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4
