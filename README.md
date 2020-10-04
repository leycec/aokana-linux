![Aokana](https://user-images.githubusercontent.com/217028/94984293-1bf1b700-053a-11eb-8fdf-310eb03a4b33.png)

Ao no Kanata no Four Rhythm (Aokana)… for Linux!
================================================

This repository officially hosts **[Lutris-based Linux
installers][lutris-aokana]** for the [unofficial native Linux port][linux-aokana]
of *[Ao no Kanata no Four Rhythm: Beyond the sky, into the
firmament][nekonyan-aokana]*, officially localized as *Aokana: Four Rhythm
Across the Blue* and commonly abbreviated as merely *Aokana* (あおかな). Read
the [highly-acclaimed][vndb-aokana] [shounen sports
chuunibyou](https://forums.fuwanovel.net/topic/1820-chuuni-what-is-this-genre)
visual novel that spawned a [derivative outpouring of mostly mediocre anime and
manga](https://en.wikipedia.org/wiki/Aokana:_Four_Rhythm_Across_the_Blue#Adaptations)
in the most cultured way possible: as a native 1440p application under a Linux
distro near you.

> ⚠️

> This port is *not* officially endorsed by [NekoNyan][nekonyan],
> *[Aokana][aokana]*'s applause-worthy [Steam publisher][steam-aokana] and
> English localizer. We still love you, [NekoNyan][nekonyan].

## Installation

> ⚠️

> This port currently only supports [NekoNyan][nekonyan]'s **[official Steam
> release][steam-aokana].** We hope to support all digital and physical
> releases of *[Aokana][nekonyan-aokana]* bought directly from other
> storefronts (e.g., [NekoNyan themselves][nekonyan-aokana],
> [JAST][jast-aokana]) at a later date. Both ship *[Aokana][nekonyan-aokana]*
> via non-standard Windows-specific installers and archival formats frustrating
> to support under Lutris.

1. **Please legally purchase [NekoNyan's English localization of
   *Aokana*][steam-aokana],** because [NekoNyan][nekonyan] continually goes
   beyond the call of for-profit duty to support censorship-free localization
   throughout the English visual novel community. We currently recommend
   **[Steam][steam-aokana],** which we [support with multiple Lutris
   installers][lutris-aokana-steam]. Digital storefronts include:
   * **[NekoNyan themselves][nekonyan-aokana].**
   * **[JAST][jast-aokana].**
   * **[Steam][steam-aokana].** (*Currently recommended.*)
1. Download **Linux-compatible videos** in the language of your choice:
   * **[English and/or
     Japanese](https://www.mediafire.com/file/bhm65i1h9tx68yv/file).**
   * **[Simplified
     Chinese](http://www.mediafire.com/file/s3rai72u2je60t1/file).**
   * **[Traditional
     Chinese](http://www.mediafire.com/file/fsisjaibh73wc8v/file).**
1. Choose the installation route that's right for you:

   * **["Steam, please."][steam-aokana]** You have chosen wisely. Note,
     however, that [NekoNyan][nekonyan]'s [vanilla Steam release of
     *Aokana*][steam-aokana] is the **censored All Ages** version. Some people
     like that. Some people don't. (Obligatory shoutouts to
     [/r/visualnovels][r-visualnovels] here.) Again, choose the installation
     subroute that's right for you:

     * **"Censored, please."** Sure thing! It's your visual novel. This route
       installs the [censored All Ages vanilla Steam release of
       *Aokana*][steam-aokana]:

       1. Download our [**experimental** censored Steam Lutris
          installer][local-steam-censored].
       1. Run the following command within a terminal from the directory you
          you downloaded this installer to:

              lutris -i aokana-native-steam-censored.yml

     * **"Uncensored, please."** You have again chosen wisely. This route
       installs the [free-as-in-beer Perfect Edition+ R18 Steam DLC
       patch][steam-aokana-perfect-edition] restoring all CGs, scenes, and
       dialogues from the original Japanese release as well as adding Misaka's
       supplementary scenes from the so-called *Aokana Perfect Edition+*:

       1. Download our [**experimental** uncensored Steam Lutris
          installer][local-steam-uncensored].
       1. Run the following command within a terminal from the directory you
          you downloaded this installer to:

              lutris -i aokana-native-steam-uncensored.yml

   * **[NekoNyan][nekonyan-aokana], [JAST][jast-aokana], or unspecified
     "other sources."** Sure thing, bud! It's your wallet. This route installs
     the [*Aokana Perfect Edition+* R18 release][steam-aokana-perfect-edition]
     identical to the uncensored Steam release discussed above. Again, choose
     the installation subroute that's right for you:

     * **"[NekoNyan][nekonyan-aokana] or [JAST][jast-aokana], please."** But of
       course, cultured Sir or Madam… Your wish is our Linux command:

       1. Download the Windows installer for *[Aokana][nekonyan-aokana]* that
          you recently purchased.
       1. Install the Windows version of *[Aokana][nekonyan-aokana]* to any
          arbitrary directory by running this installer via [WINE][wine]. Note
          that it doesn't matter *where* you install the Windows version of
          *[Aokana][nekonyan-aokana]* to – only that you can find this
          directory again later. For example, if this installer is named
          `"Aokana - Four Rhythms Across the Blue.exe"`, run the following
          command within a terminal from the directory you downloaded this
          installer to:

              wine start /unix "Aokana - Four Rhythms Across the Blue.exe"

       3. Download our [up-to-date standalone Lutris
          installer][local-standalone-new].
       1. Run the following command within a terminal from the directory you
          you downloaded this installer to:

              lutris -i aokana-native-standalone-new.yml

       5. When asked to *Select main Windows executable "Aokana.exe"*, select
          the top-level `Aokana.exe` file in the directory you installed the
          Windows version of *[Aokana][nekonyan-aokana]* to earlier.

     * **"Unspecified other sources, please."** Please legally purchase
       [NekoNyan's English localization of *Aokana*][steam-aokana] when you
       have the financial opportunity, matey. Without monetary support, the
       English visual novel community will get a Bad End: <sup>*that's
       bad*</sup>

       1. Download our [up-to-date standalone Lutris
          installer][local-standalone-old].
       1. Run the following command within a terminal from the directory you
          you downloaded this installer to:

              lutris -i aokana-native-standalone-old.yml

       3. When asked to *Select main Windows executable "Aokana.exe"*, select
          the top-level `Aokana.exe` file in the directory you downloaded the
          Windows version of *[Aokana][nekonyan-aokana]* to earlier.
       1. When asked for the *Destination Folder*, select the **Linux**
          directory to which you are currently installing this **native Linux
          port**:

          1. Click the *Browse* button.
          1. Double-click the **root Linux directory** `/`. Do *not*
             double-click a Windows directory (e.g., `My Computer`, `Trash`),
             because *Aokana* won't be there.
          1. Select your **Linux port game directory** (e.g.,
             `/home/insert_username_here/Games/aokana-native/`).

       1. Click the *Close* button.

You're done. *Praise Misaka!*

## Features

This port is a [fan-authored third-party conversion][linux-aokana] of
[NekoNyan][nekonyan]'s [original Windows-only release][steam-aokana], now
featuring:

* **Native Linux execution.** As a native Linux application, this port requires
  *no* compatibility layer (e.g., [WINE][wine] [Proton][proton]) – reducing
  runtime overhead and the usual laundry list of issues caused by these layers.
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
[leycec]: https://github/leycec
[loam]: https://forums.fuwanovel.net/profile/28837-loam
[local-standalone-old]:   /raw/main/lutris/aokana-native-standalone-old.yml
[local-standalone-new]:   /raw/main/lutris/aokana-native-standalone-new.yml
[local-steam-censored]:   /raw/main/lutris/aokana-native-steam-censored.yml
[local-steam-uncensored]: /raw/main/lutris/aokana-native-steam-uncensored.yml
[lutris]: https://lutris.net
[lutris-aokana]: https://lutris.net/games/aokana-four-rhythms-across-the-blue
[lutris-aokana-steam]: https://lutris.net/games/aokana-four-rhythms-across-the-blue
[linux-aokana]: https://forums.fuwanovel.net/topic/23163-linux-port-now-released-ao-no-kanata-no-four-rythm-linux-port-18-patch-for-nintendo-switch/?do=findComment&comment=522629
[r-visualnovels]: reddit.com/r/visualnovels
[steam]: https://store.steampowered.com
[steam-aokana]: https://store.steampowered.com/app/1044620/Aokana__Four_Rhythms_Across_the_Blue/
[steam-aokana-perfect-edition]: https://nekonyansoft.com/shop/product/23
[vndb-aokana]: https://vndb.org/v12849
[media-vorbis]: https://en.wikipedia.org/wiki/Vorbis
[media-vp8]: https://en.wikipedia.org/wiki/VP8
[media-webm]:  https://www.webmproject.org/about
[proton]: https://github.com/ValveSoftware/Proton
[wine]: https://www.winehq.org
