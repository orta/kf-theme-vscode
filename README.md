# Kary Foundation’s Syntax Themes

[![](https://vsmarketplacebadge.apphb.com/version/karyfoundation.theme-karyfoundation-themes.svg) ![](https://vsmarketplacebadge.apphb.com/installs/karyfoundation.theme-karyfoundation-themes.svg)](https://marketplace.visualstudio.com/items?itemName=karyfoundation.theme-karyfoundation-themes) [![](https://img.shields.io/badge/Powered by-themeX-yellow.svg)](https://github.com/karyfoundation/themeX)

<img width="611" alt="screen shot 2016-11-22 at 10 34 11 pm" src="https://cloud.githubusercontent.com/assets/2157285/20538013/ab9ca2ea-b104-11e6-9dea-23a3379e7511.png">

## What is this?
This page obviously is about a syntax theme, but for this one we have somehow a back story that is way different than just different coloring.

When people say beautiful codes they always mean less complexity or clever code but when we say that we mean it for real. The code must look nice when you read it. In order to manage the code we invented [Kary Foundation’s Coding Style (KFCS)](https://github.com/karyfoundation/comment/wiki) and the fact that we have a very restricted way of [coding style](http://kary.us/2015/02/12/arendelle-coding-styles/). 

Now beauty matters but also it’s the psychology that matters. As developers what you see all day long is code. So it matters that the code be pretty and it matters that your editor is pretty because well it’s your life happening behind it. But how should it look? what colors must be there? 

For what we know we all are playful people. We have an active inner child. Our editors must look like playgrounds. We have developed a rainbow colored theme. With worm colors chosen very carefully for the finest code quality possible. 

From what we noticed [iA Writer](https://ia.net/writer) has the most carefully defined experience. We loved the `gold` and `red`/`orange` colors used by their highlighter and inspired by their design we shaped a coding experience that for us was the most joyful look of the code ever possible. 

## The theme…
#### JavaScript / TypeScript
<img width="747" alt="screen shot 2016-11-22 at 10 24 29 pm" src="https://cloud.githubusercontent.com/assets/2157285/20538012/ab99a496-b104-11e6-8f44-ccc35c1f435b.png">

<img width="786" alt="screen shot 2016-11-22 at 10 24 01 pm" src="https://cloud.githubusercontent.com/assets/2157285/20538011/ab955e7c-b104-11e6-922b-698c99902047.png">

#### Ruby
<img width="647" alt="screen shot 2016-11-22 at 9 55 03 pm" src="https://cloud.githubusercontent.com/assets/2157285/20538010/ab913f5e-b104-11e6-9364-49528adbfb83.png">

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
### 8.0.0
- **Change!** &mdash; Dark colors are improved for good.
- **New!** &mdash; CSS / Less are now fully supported. We had great support but with the new definitions they didn't worked. This new version includes the new defs to provide the bust support.
- **Change** &mdash; TypeScript / JavaScript now have a much better color for the function arguments and types.
- **New!** &mdash; We now have a fully support for Ruby including: Class Variables, Global Variables, Ruby Separators (`do | ... |`), `def` keyword, Right string interpolations.
- **Fix!** &mdash; Type colors had so many issues, they are fixed for good.
- **New!** &mdash; We now have full support fur Pageman (The whole definition is included).

### 7.6.0
- **New!** &mdash; We now have custom support for JSON (true coloring enabled!)
- **New!** &mdash; You think more high level than JSON? We also have the same support for YAML now...

### 7.5.0
- **Fix!** &mdash; Types and type casts in TypeScript and JavaScript are fixed.
- **Fix!** &mdash; Namespace color is fixed.
- **Fix!** &mdash; Coloring of function parameter types are fixed
- **Upcoming!** &mdash; As you know with the new grammar of Visual Studio Code 1.7 we now have functions in everywhere colored as red. This is due to a limitation of the grammar. We have [opend a pull request](https://github.com/Microsoft/TypeScript-TmLanguage/pull/362) to address the problem and provide a solution. We're hoping to have it fixed in the next versions of visual studio code if possible.

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