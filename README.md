# snips-FechaHora 🕑
A date and time app for Snips.ai

## Installation

**Important:** The following instructions assume that [Snips](https://snips.gitbook.io/documentation/snips-basics) is
already configured and running on your device. [SAM](https://snips.gitbook.io/getting-started/installation) should
also already be set up and connected to your device and your account.

1. In the German [app store](https://console.snips.ai/) add the
app `Datum & Uhrzeit` (by domi; [this](https://console.snips.ai/app-editor/bundle_9P346QWA0xE)) to
your *German* assistant.

2. If you already have the same assistant on your platform, update it
(with [Sam](https://snips.gitbook.io/getting-started/installation)) with:
      ```bash
      sam update-assistant
      ```
      
   Otherwise install the assistant on the platform with [Sam](https://snips.gitbook.io/getting-started/installation)
   with the following command to choose it (if you have multiple assistants in your Snips console):
      ```bash
      sam install assistant
      ```
That's it!

## Usage

With this app you can ask Snips for information about the date and the time, including the day of the week,
and some others.

### Example sentences

#### Current date

- *Was für ein Tag ist heute?*
- *Sage den heutigen Tag.*
- *Den wievielten haben wir heute?*
- *Was ist das aktuelle Datum?*
- *Ist schon Wochenende?*
- [...]

#### Current time

- *Kannst du mir die Uhrzeit verraten?*
- *Wie spät ist es?*
- *Sag mir die Zeit*
- *Ich wüsste gerne, wie spät es ist.*
- *Ich muss gleich los, wie spät ist es?
- *Bitte sage mir, wie spät es ist.*
- [...]

#### Week number

- *Welche Wochennummer haben wir heute?*
- *Welche Woche ist am 1. Januar 2019?*
- *Die Wochennummer für den 24. Dezember.*
- *Sage mir die Kalenderwoche vom 2. Juli.*
- *Welche kalenderwoche ist der 18.05.?*
- *Was ist die Kalenderwoche vom 19. März 2016?*
- [...]

#### Date info

- *Sage die aktuelle Minute.*
- *Was sind die aktuellen Stunden?*
- *In welchem Jahr sind wir?*
- *Was für ein Tag der Woche ist heute?*
- [...]

## Contribution

Please report errors (you can see them with `sam service log`) and bugs by
opening a [new issue](https://github.com/MrJohnZoidberg/Snips-DatumUhrzeit/issues/new).
You can also write other ideas for this skill. Thank you for your contribution.
