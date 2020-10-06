![Aokana](https://user-images.githubusercontent.com/217028/94984293-1bf1b700-053a-11eb-8fdf-310eb03a4b33.png)

Ao no Kanata no Four Rhythm (Aokana)… for Linux!
================================================

This repository officially hosts **[Lutris-based Linux
installers][lutris-aokana]** for the [unofficial native Linux
port][linux-aokana] of *[Ao no Kanata no Four Rhythm: Beyond the sky, into the
firmament][nekonyan-aokana]*, officially localized as *Aokana: Four Rhythm
Across the Blue* and commonly abbreviated as merely *Aokana* (あおかな). Read
the [highly-acclaimed][vndb-aokana] [shounen sports chuunibyou][chuuni] visual
novel that [spawned a derivative outpouring of anime and manga
spinoffs](https://en.wikipedia.org/wiki/Aokana:_Four_Rhythm_Across_the_Blue#Adaptations)
in the most cultured way possible: as a native 1440p application under a Linux
distro near you.

> ⚠️

> This port is **not officially endorsed** by [NekoNyan][nekonyan],
> *[Aokana][nekonyan-aokana]*'s applause-worthy [Steam publisher][steam-aokana]
> and English localizer. We still love you, [NekoNyan][nekonyan].

## Installation

> ☢

> These installers are experimental, largely untested, and possibly even (but
> hopefully *not*) broken. Please help us get a better idea of the state of
> these installers by **[submitting a new issue documenting your installation
> experience][local-issue-new].** Installers verified as working will be
> published to [the Lutris page for *Aokana*][lutris-aokana]. Until verified,
> these installers are *only* available from this repository.

1. **Please legally purchase [NekoNyan's English localization of
   *Aokana*][steam-aokana],** because [NekoNyan][nekonyan] continually goes
   beyond the call of corporate duty to support censorship-free localization
   throughout the English visual novel community. Online storefronts include:
   * **[NekoNyan themselves][nekonyan-aokana].**
   * **[JAST][jast-aokana].**
   * **[Steam][steam-aokana].**
1. Download **Linux-compatible videos** in the language of your choice:
   * **[English and/or
     Japanese](https://www.mediafire.com/file/bhm65i1h9tx68yv/file).**
   * **[Simplified
     Chinese](http://www.mediafire.com/file/s3rai72u2je60t1/file).**
   * **[Traditional
     Chinese](http://www.mediafire.com/file/fsisjaibh73wc8v/file).**
1. Choose the installation route that's right for you:
   * **"[NekoNyan][nekonyan-aokana] or [JAST][jast-aokana], please."** But of
     course, cultured senpai! This route installs the [*Aokana Perfect
     Edition+* R18 release][steam-aokana-perfect-edition] directly purchased
     from [NekoNyan][nekonyan-aokana] or [JAST][jast-aokana] (identical to the
     uncensored Steam release detailed below):
     1. Download our [**experimental** NekoNyan-or-JAST Lutris
        installer][local-nekonyan-or-jast].
     1. Run the following command in a terminal from the directory you
        downloaded this installer to:

            lutris -i aokana-native-nekonyan-or-jast.yml

     3. When asked for a *Destination Folder*, select the **Linux game
        directory** that Lutris has already created for
        *[Aokana][nekonyan-aokana]* (e.g.,
        `/home/insert_username_here/Games/aokana-native/`):
        1. Click the *Browse* button.
        1. Double-click the **root Linux directory** `/`. Do *not*
           double-click a Windows directory (e.g., `My Computer`, `Trash`),
           because Lutris expects native Linux games to be installed to
           standard Linux directories.
        1. Select the **Linux game directory** that Lutris has already created
           for *[Aokana][nekonyan-aokana]* (e.g.,
           `/home/insert_username_here/Games/aokana-native/`).
     1. Click the *Close* button.
   * **["Steam, please."][steam-aokana]** Your wish is our Linux command. Note,
     however, that [NekoNyan][nekonyan]'s [vanilla Steam release of
     *Aokana*][steam-aokana] is the **censored All Ages** version. Some people
     like that. Some people don't. <sup>Obligatory shoutouts to
     [/r/visualnovels][r-visualnovels] here.</sup> Again, choose the
     installation subroute that's right for you:
     * **"Censored, please."** Sure thing! It's your visual novel. This
       subroute installs the [censored All Ages vanilla Steam release of
       *Aokana*][steam-aokana]:
       1. Download our [**experimental** censored Steam Lutris
          installer][local-steam-censored].
       1. Run the following command in a terminal from the directory you
          downloaded this installer to:

              lutris -i aokana-native-steam-censored.yml

     * **"Uncensored, please."** You have chosen wisely. This subroute
       installs the [free-as-in-beer Perfect Edition+ R18 Steam DLC
       patch][steam-aokana-perfect-edition] restoring all CGs, scenes, and
       dialogues from the original Japanese release as well as adding Misaka's
       supplementary scenes from the so-called *Aokana Perfect Edition+*:
       1. Download our [**experimental** uncensored Steam Lutris
          installer][local-steam-uncensored].
       1. Run the following command in a terminal from the directory you
          downloaded this installer to:

              lutris -i aokana-native-steam-uncensored.yml

   * **"Unspecified other sources, please."** Please legally purchase
     [NekoNyan's English localization of *Aokana*][steam-aokana] when you have
     the financial means – if you haven't already, of course. Without ongoing
     monetary support, the visual novel community will get a Bad End (which is
     bad):
     1. Download our [**experimental** portable Lutris
        installer][local-portable].
     1. Run the following command in a terminal from the directory you
        downloaded this installer to:

            lutris -i aokana-native-portable.yml

     3. When asked to *Select main Windows executable "Aokana.exe"*, select
        the top-level `Aokana.exe` file in the directory containing your
        portable Windows copy of *[Aokana][nekonyan-aokana]*.
     3. When asked for a *Destination Folder*, select the **Linux game
        directory** that Lutris has already created for
        *[Aokana][nekonyan-aokana]* (e.g.,
        `/home/insert_username_here/Games/aokana-native/`):
        1. Click the *Browse* button.
        1. Double-click the **root Linux directory** `/`. Do *not*
           double-click a Windows directory (e.g., `My Computer`, `Trash`),
           because *Aokana* won't be there.
        1. Select the **Linux game directory** that Lutris has already created
           for *[Aokana][nekonyan-aokana]* (e.g.,
           `/home/insert_username_here/Games/aokana-native/`).
     1. Click the *Close* button.

You're done. Praise Misaka!

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

## See Also

If you enjoy this, you might also enjoy:

* [*Fate/stay night [Réalta Nua] Ultimate Edition*… for
  Linux!][leycec-fatestaynight], a [Lutris installer][lutris] automating
  patching and execution of the *[Réalta Nua]* variant of the seminal [shounen
  chuunibyou][chuuni] visual novel *[Fate/stay night][typemoon-fatestaynight]*.

[chuuni]: https://forums.fuwanovel.net/topic/1820-chuuni-what-is-this-genre
[nekonyan]: https://nekonyansoft.com
[nekonyan-aokana]: https://nekonyansoft.com/shop/product/22
[jast-aokana]: https://jastusa.com/aokana-four-rhythms-across-the-blue
[leycec]: https://github/leycec
[leycec-fatestaynight]: https://github.com/leycec/fsnrnue
[loam]: https://forums.fuwanovel.net/profile/28837-loam
[local-issue-new]: /issues/new/choose
[local-nekonyan-or-jast]: /raw/main/lutris/aokana-native-nekonyan-or-jast.yml
[local-portable]:         /raw/main/lutris/aokana-native-portable.yml
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
[typemoon-fatestaynight]: https://typemoon.fandom.com/wiki/Fate/stay_night
[wine]: https://www.winehq.org
