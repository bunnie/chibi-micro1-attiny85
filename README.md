Chibitronics microcontroller for sticker set 1

Default code for chibitronics ATTiny85 microcontroller sticker
as used in the first release of stickers.

Implements a two-point touch function, and these behaviors:
* Light on touch
* Fade on touch
* "Dice" (between 1-6 blinks upon touch)
* "Memorize" (remember and playback a tapping pattern, minimum two taps)

Notes on fusing for production:
* Brownout detecter set to 1.8V (note default none)
* Initial clock set to 8MHz by fuses (note default is 1MHz)
