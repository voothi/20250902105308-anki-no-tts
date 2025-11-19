# No TTS Player for Anki

A simple Anki add-on to globally disable all Text-to-Speech (TTS) playback.

[![Version](https://img.shields.io/badge/version-v1.44.8-blue)](https://github.com/voothi/20250902105308-anki-no-tts)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

> **Attribution and License Notice**
>
> This add-on is based on the official "No TTS" example from the [Anki Add-ons repository](https://github.com/ankitects/anki-addons/tree/main/code/no_tts).
>
> The original code is **Copyright © Ankitects Pty Ltd and contributors** and is licensed under the **GNU AGPL, version 3 or later**. In accordance with its terms, this derivative work is also licensed under the same license.

This minimalist add-on allows users to temporarily or permanently silence all TTS fields (`{{tts...}}`) in their Anki cards without needing to edit their card templates.

## Table of Contents

- [No TTS Player for Anki](#no-tts-player-for-anki)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Related Projects](#related-projects)
  - [Kardenwort Ecosystem](#kardenwort-ecosystem)
  - [License](#license)

---

## Features

-   **Zero Configuration**: Just install and it works.
-   **Global Mute**: Disables all TTS triggers across all decks and note types.
-   **Easily Toggled**: Enable or disable the effect by simply toggling the add-on in Anki's add-on manager.
-   **No Template Editing**: Silences audio without requiring any changes to your card templates.

[Back to Top](#table-of-contents)

## Installation

1.  Clone or download this repository.
2.  Copy the `NoTTS` folder into your Anki `addons21` directory.
3.  Restart Anki.

[Back to Top](#table-of-contents)

## Usage

Once installed, the add-on is active and will prevent any TTS audio from playing.

-   **To disable TTS**: Make sure the add-on is installed and enabled.
-   **To re-enable TTS**: Disable or uninstall this add-on from Anki's add-on manager (`Tools -> Add-ons`) and restart Anki.

[Back to Top](#table-of-contents)

## Related Projects

-   [**gTTS Player with Piper Fallback for Anki**](https://github.com/voothi/20250421115831-anki-gtts-player): For users who want to enhance TTS with offline capabilities instead of disabling it, this add-on provides a resilient solution with a local fallback engine.

[Back to Top](#table-of-contents)

## Kardenwort Ecosystem

This project is part of the **[Kardenwort](https://github.com/kardenwort)** environment, designed to create a focused and efficient learning ecosystem.

[Return to Top](#table-of-contents)

## License

This add-on is licensed under the [GNU AGPL, version 3 or later](https://www.gnu.org/licenses/agpl.html).

[Back to Top](#table-of-contents)