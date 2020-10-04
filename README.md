![Aokana](https://user-images.githubusercontent.com/217028/94984293-1bf1b700-053a-11eb-8fdf-310eb03a4b33.png)

Ao no Kanata no Four Rhythm (Aokana)… for Linux!
================================================

This repository officially hosts the [Lutris-based **Linux**
installer][lutris-aokana] for the [unofficial native Linux port][linux-aokana]
of *[Ao no Kanata no Four Rhythm: Beyond the sky, into the firmament][nekonyan-aokana]*,
officially localized as *Aokana: Four Rhythm Across the Blue* and commonly
abbreviated as merely *Aokana* (あおかな). Read the
[highly-acclaimed][vndb-aokana] [shounen sports
chuunibyou](https://forums.fuwanovel.net/topic/1820-chuuni-what-is-this-genre)
visual novel that spawned a [derivative outpouring of mostly mediocre anime and
manga](https://en.wikipedia.org/wiki/Aokana:_Four_Rhythm_Across_the_Blue#Adaptations)
in the most cultured way possible: as a native 1440p application under a Linux
distro near you, of course!

> ⚠️

> This port has *not* been officially endorsed by [NekoNyan][nekonyan],
> *Aokana*'s applause-deserving Steam publisher and English localizer. We still
> love you, [NekoNyan][nekonyan].

## Installation

1. **Please purchase [NekoNyan][nekonyan]'s [English localization of
   *Aokana*][nekonyan-aokana],** because [NekoNyan][nekonyan] consistently goes above
   the call of for-profit duty to support censorship-free localization
   throughout the English-speaking visual community. <sup>*that's us*</sup>
   Online storefronts include:
   * (*Recommended*) **[NekoNyan themselves][nekonyan-aokana].**
   * **[JAST][jast-aokana].**
   * **[Steam][steam-aokana].**
1. *Finish this tomorrow, please.* `</sigh>`

## Features

This port is a [fan-authored third-party conversion][linux-aokana] of
[NekoNyan][nekonyan]'s [original Windows-only release][steam-aokana], now
featuring:

* **Native Linux execution.** As a native Linux application, this port requires
  *no* compatibility layer (e.g.,
  [Wine](https://www.winehq.org),
  [Proton](https://github.com/ValveSoftware/Proton)) – reducing both runtime
  overhead and the usual laundry list of issues resulting from these layers.
* **Linux-compatible videos.** As a native Linux application, this
  port leverages cross-platform open-source royalty-free media standards like
  [Vorbis][media-vorbis], [VP8][media-vp8], and [WebM][media-webm] rather than
  the non-cross-platform non-open-source royalty-encumbered media shipped with
  the [original Windows-only release][steam-aokana].
* **Fast save restart.** This port additionally supports a new low-level
  `--continue` command-line option substantially reducing startup times. When
  passed, this option bypasses all startup logos, the opening video (OP), the
  main menu, and the load menu by immediately loading straight into the most
  recent save. *Nice.*

## Differences

This port also features a number of *mostly* negligible differences from the
[original Windows-only release][steam-aokana], listed here for both
completeness and to avoid confusion:

* **Sprite Viewer file features unsupported.** This port does *not* currently
  support Sprite Viewer features attempting to open a file dialog, as the
  [original Windows-only release][steam-aokana] did so by opening a
  non-portable Windows-specific file dialog. This includes the following Sprite
  Viewer features:
  * Background importation.
  * Image file saving.
* **Letterboxing on window resizes.** When manually resizing the game window to
  an unsupported aspect ratio, this port currently letterboxes (i.e., surrounds
  game content with both horizontal and vertical black bars) rather than
  auto-correcting itself as in the [original Windows-only
  release][steam-aokana].
* **Unpaused audio on window minimization.** When minimizing the game window,
  this port currently fails to pause the currently playing audio if any rather
  than automatically pausing that audio as in the [original Windows-only
  release][steam-aokana].
* **Save thumbnail degradation.** As in the Switch port, this port downscales
  save thumbnails with Unity's lower-quality stock bilinear filtering mode
  rather than the higher-quality bicubic filtering mode implemented by the
  [original Windows-only release][steam-aokana].

## Authors

Authoritative credit for this native Linux port goes entirely to [Unity maestro
and Fuwanovel forums contributor **loam**][loam]. *You are amazing and you
surely know it.*

[nekonyan]: https://nekonyansoft.com
[nekonyan-aokana]: https://nekonyansoft.com/shop/product/22
[jast-aokana]: https://jastusa.com/aokana-four-rhythms-across-the-blue
[loam]: https://forums.fuwanovel.net/profile/28837-loam
[lutris]: https://lutris.net
[lutris-aokana]: https://lutris.net/games/fatestay-night
[linux-aokana]: https://forums.fuwanovel.net/topic/23163-linux-port-now-released-ao-no-kanata-no-four-rythm-linux-port-18-patch-for-nintendo-switch/?do=findComment&comment=522629
[steam-aokana]: https://store.steampowered.com/app/1044620/Aokana__Four_Rhythms_Across_the_Blue/
[vndb-aokana]: https://vndb.org/v12849
[media-vorbis]: https://en.wikipedia.org/wiki/Vorbis
[media-vp8]: https://en.wikipedia.org/wiki/VP8
[media-webm]:  https://www.webmproject.org/about
