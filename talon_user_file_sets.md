# Talon user file set list

The main Talon user file set for Talon is of course knausj\_talon, but people have created several others. These range from 'base' user file sets that contain their whole Talon setup through to sets which build on top of knausj\_talon functionality.

If intended for public consumption, these Talon user file sets are mostly annouced via the [Slack channel](/). Aside from that there are a few ways you can discover them:

* You can make use of the [talon code search](https://search.talonvoice.com/search/). This aims to search all known github repositories containing Talon related code. If you're looking for integration with a particular application this is a good option.
* You can browse the [github talonvoice topic](https://github.com/topics/talonvoice). Repositories can optionally tag themselves with this to aid discoverability.
* You can take a look at the manually curated list below.

## Voice controlled hands free mouse replacements

The easiest way to control your mouse with Talon is to use an eye tracker. But this is fairly expensive hardware. There are several voice/noise only options in addition to the 'mouse grid' built in to knausj\_talon.

* [gaze-ocr](https://github.com/wolfmanstout/talon-gaze-ocr) for advanced cursor control using eye tracking and text recognition (OCR)
* [Dense Mouse Grid](https://github.com/tararoys/dense-mouse-grid/tree/dense_mouse_grid_2/dense_mouse_grid) Less obtrusive overlay combining a letter and number grid to position the mouse.
* [Alphabet Soup Mouse](https://github.com/tararoys/modified_full_mouse_grid)  This mouse overlays a very dense grid of letters onto the screen for very precise mouse placement. Created by Aegis, TimoTimo, and TaraRoys.
* [crosshairs mouse guide mouse](https://github.com/tararoys/mouse_guide) Created by Aegis.  Allows you to say very specific mouse coordinates and position the mouse precisely on the screen.
* [Racecar Mouse (AKA drawing mouse)](https://gist.github.com/timo/d3a8c871aca93aee4cd8b4fc57b15187) A mouse you can use to draw with Talon. It steers like a racecar around the screen. Created by Timotimo.
* [Hissing Mouse](https://gist.github.com/tararoys/cdabc3bab686abd8d9b585afd7c481da) Created by Tara Roys. A mouse that operates soley by hissing, and uses the idea that if you make a left turn you can get anywhere on the screen by 'circling the block.'  Simplest possible no-words, no-hands, no need to memorize commands mouse.

## Programming and editor integrations

* [Cursorless](https://www.cursorless.org/) Structural code editing in VSCode. This with [`knausj_talon`](https://github.com/knausj85/knausj_talon) is the state of the art for voice coding with Talon currently.
* [Fidgetingbit's knausj fork](https://github.com/fidgetingbits/knausj_talon) Fork of knausj\_talon most famous for its integration with the (N)Vim code editor.

## User Interface

* [Talon Heads Up Display](https://github.com/chaosparrot/talon_hud) This heads up display is awesome because it shows things like when Talon is awake, asleep, what language mode active, prints a pretty history, And a whole bunch of other things that right now you have to memorize.
* [Talon Deck](https://github.com/AndreasArvidsson/talon-deck) Stream deck inspired interactive dashboard for Talon. Turn your phone/tablet into a Talon control UI.

## Application specific

* [Chess board integration](https://github.com/brollin/chess_grid/) Integration with computer based chess. Lets you play chess on Lichess.org for example.
* [Rango](https://github.com/david-tejada/rango) Allows you to easily click active elements in the browser using your voice. An alternative to Vimium with better Talon integration.

## Command builders and macros

Talon user sets that allow you to build voice commands more easily or define commands in a quick ad-hoc way. knausj\_talon has an ephemeral macro system built in, but these user file sets extend that further.

* [Talon UI helper](https://github.com/splondike/talon_ui_helper) Command wizard that lets you build TalonScript commands which work with the screen as an image. For example it lets you easily build a command to click an icon, or show an overlay for clicking items in a list.
* [Screen spots](https://github.com/AndrewDant/screen-spots) Lets you quickly save mouse positions on the screen and then click them with a short voice command. Useful for games with fixed UI element position.

## Other

* [AXKit](https://github.com/phillco/talon-axkit) (macOS only) to enhance Talon with native OS accessibility integrations
* [knausj's clickless mouse](https://github.com/knausj85/clickless_mouse) Use the mouse for positioning, but hover an overlay to click.
* [Subtitles.md](https://gist.github.com/tararoys/accf5506bea2c5c17e5bb31c7beac6e4)  A basic script for writing subtitles to a file for a screencapture.
* [Talon Cheatsheet Generation Script](https://gist.github.com/tararoys/c538b7ae8e1f21db9a794c2c0f5becf4) How to generate a cheatsheet for your own repository
* [wenkokke's cheatsheet and generation script](https://github.com/wenkokke/talon-cheatsheet/) Another cheatsheet generator which can output HTML or PDF.
* [Morse Keypresses](https://gist.github.com/tararoys/7ef72526a825bb4c2253c961695d5e4b) allows you to spell out letters using morse code and the hissing noise.
* [Window Tweak](https://github.com/codecat555/talon-window-tweak) A Talon module for moving and resizing windows using voice commands.
* [Software that pairs well with Talon](/other_integrations#software-that-pairs-well-with-talon) Not a Talon user file set per-se, but other things you might find useful.
