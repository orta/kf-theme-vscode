# Kary Foundation’s Syntax Themes

<div style="font-size: 50px; color: red; line-height: 1.4">THIS VERSION NEEDS VSCODE 1.7.0 OR HIGHER. PLEASE DO NOT INSTALL OR UPGRADE IF YOU'RE RUNNING ANY OLDER VERSION.</div>

[![](https://vsmarketplacebadge.apphb.com/version/karyfoundation.theme-karyfoundation-themes.svg) ![](https://vsmarketplacebadge.apphb.com/installs/karyfoundation.theme-karyfoundation-themes.svg)](https://marketplace.visualstudio.com/items?itemName=karyfoundation.theme-karyfoundation-themes) [![](https://img.shields.io/badge/Powered by-themeX-yellow.svg)](https://github.com/karyfoundation/themeX)

<img width="515" alt="screen shot 2016-07-23 at 1 04 23 pm" src="https://cloud.githubusercontent.com/assets/2157285/17077002/83748b40-50d6-11e6-93f9-302440275aa3.png">

## What is this?
This page obviously is about a syntax theme, but for this one we have somehow a back story that is way different than just different coloring.

When people say beautiful codes they always mean less complexity or clever code but when we say that we mean it for real. The code must look nice when you read it. In order to manage the code we invented [Kary Foundation’s Coding Style (KFCS)](https://github.com/karyfoundation/comment/wiki) and the fact that we have a very restricted way of [coding style](http://kary.us/2015/02/12/arendelle-coding-styles/). 

Now beauty matters but also it’s the psychology that matters. As developers what you see all day long is code. So it matters that the code be pretty and it matters that your editor is pretty because well it’s your life happening behind it. But how should it look? what colors must be there? 

For what we know we all are playful people. We have an active inner child. Our editors must look like playgrounds. We have developed a rainbow colored theme. With worm colors chosen very carefully for the finest code quality possible. 

From what we noticed [iA Writer](https://ia.net/writer) has the most carefully defined experience. We loved the `gold` and `red`/`orange` colors used by their highlighter and inspired by their design we shaped a coding experience that for us was the most joyful look of the code ever possible. 

## The theme…
#### JavaScript / TypeScript
<img width="600" alt="screen shot 2016-07-23 at 1 12 03 pm" src="https://cloud.githubusercontent.com/assets/2157285/17077044/7f25599c-50d7-11e6-8511-69f286698743.png">
<img width="600" alt="screen shot 2016-07-23 at 1 12 22 pm" src="https://cloud.githubusercontent.com/assets/2157285/17077045/7fb1bd6a-50d7-11e6-867d-cd90e7d21151.png">

#### Ruby
<img width="641" alt="screen shot 2016-07-24 at 3 44 16 am" src="https://cloud.githubusercontent.com/assets/2157285/17080757/077c4aac-5151-11e6-9182-a7f91985a723.png">

#### Arendelle
<img width="510" alt="screen shot 2016-07-24 at 3 35 36 am" src="https://cloud.githubusercontent.com/assets/2157285/17080732/e87e1a0a-514f-11e6-9227-43aca3767aba.png">

#### CSS / Less
<img width="626" alt="screen shot 2016-07-23 at 1 00 09 pm" src="https://cloud.githubusercontent.com/assets/2157285/17077053/b0c38b0e-50d7-11e6-831a-82a5df23a0de.png">

#### HTML / XML
<img width="523" alt="screen shot 2016-07-23 at 4 23 56 am" src="https://cloud.githubusercontent.com/assets/2157285/17077057/ccbf5fcc-50d7-11e6-855c-9521a450f9c5.png">

#### Pageman
<img width="801" alt="screen shot 2016-07-24 at 3 39 47 am" src="https://cloud.githubusercontent.com/assets/2157285/17080746/7c164e86-5150-11e6-8adf-1dae193d48f6.png">

#### JSON
<img width="596" alt="screen shot 2016-07-23 at 1 03 12 pm" src="https://cloud.githubusercontent.com/assets/2157285/17077058/ddfce520-50d7-11e6-82a9-eab20c5babfb.png">

## How to use it?
We support Atom and Sublime Text as well, For more information on this please [visit here](https://github.com/karyfoundation/karyfoundation.themeX#status)

## Good font to use with this theme?
To use it best, we suggest you use the medium weight of [Hasklig](https://github.com/i-tu/Hasklig) typeface. It's a fork of [Adobe Source Code Pro](https://adobe-fonts.github.io/source-code-pro) with programmer ligatures. Our theme is the best match to this typeface.

## What's new?
### 7.2.0
- **Change!** &mdash; Strings are now blue again. Also string interpolation is added.
- **Change!** &mdash; Function export types are orange.
- **Change!** &mdash; Comparison and Relational operators are orange now.
- **Change!** &mdash; Special Keywords are being taken care of.
- **Upcoming** &mdash; Special Ruby Token will be added soon.

### 7.0.0
- **Change!** &mdash; This version of the theme is designed for the new version of definitions and highlighter of the vscode that is coming in the v1.7.0. The themes are now compatible with the Babel Definitions and the new JavaScript / TypeScript definitions coming with viscose.
- **New!** &mdash; Object keys now have a color! So you can distinguish stuff more easy right now...

#### 5.2.0
- **Change!** &mdash; Strings are green these days...
- **Change!** &mdash; The dark theme's background is lighted a bit to match the dark background of the vscode. This way it has more eye comfort.
- **Issue #1** &mdash; Thanks to dear [Murriouz](https://github.com/Murriouz) a bug was reported about invalid code's rendering and it's not fixed.
- **Upcoming** &mdash; For the next release we'll be having Babel syntax support.

#### 5.0.0
- **Change!** &mdash; The theme is now ported to [themeX](https://github.com/karyfoundation/themeX). As the themeX project itself is just started it may take weeks till we develop adaptors for other editors but once we reach there, using one code base we will compile the theme for all the other editors at ever single update. So soon we'll have support for other main big editors. Thanks for being with us till now.
- **Change!** &mdash; Operators are now blue!

#### 4.0.2
- **Change!** &mdash; No line highlight for dark theme.
- **New!** &mdash; Versions are now synced across all versions.

#### 1.5.2
- **New!** &mdash; Operator Keywords now render just like normal text. (better right?).

#### 1.5.1
- **Fix!** &mdash; As [it turns out](https://github.com/Microsoft/vscode/issues/9629) Mac uses a _Gamma 1.8 RGB_ but the standard for tmThemes are sRGB. Thanks to the great tool ["tmTheme Color Convertor"](https://github.com/jibsen/tmcolorconv) the theme has being fixed and the colors no longer looks dark!

#### 1.4.5
- **New!** &mdash; TypeScript's _Type Cast Expression_ now has custom coloring.

#### 1.4.4
- **New!** &mdash; Custom string color for HTML added.
- **Fix!** &mdash; Markdown Heading color changed to be more hormonic.

#### 1.4.3
- **New!** &mdash; Custom color for TypeScript class storage modifiers (`public`, `private`, ...)


<br />
<a href="http://www.karyfoundation.org/">
    <img src="http://www.karyfoundation.org/foundation/logo/github-full-horse.png" width="250"/>
</a>