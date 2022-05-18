# Chordic Keyboard Layout (For the 42-Key Corne/crkbd)
### _A chord-heavy layout built for instantaneousness_

![chordic-layout-full](./images/01-chordic-layout-full.png)

_**Summary**: This layout heavily relies on **chording** for symbols and actions. All letters, symbols, arrow keys, media keys, and modifiers are **instantaneous** without the need for layers, hold activation, or double taps, making this layout fast and friendly for **software keyboard shortcuts** and **password entry**. Chord positions are intuitive and created with **mnemonics** in mind. Layers are only reserved for number keys and function keys._

-------------------
|**Content**      |
|-----------------|

1. [Introduction](#introduction)
   - [Why Only a 42-Key, 40% Keyboard?](#why-only-a-42-key-40-keyboard)
   - [What is a Chord?](#what-is-a-chord)
   - [Considerations](#considerations)
2. [Base Layout](#base-layout)
   - [Arrow Keys](#arrow-keys)
   - [QWERTY](#qwerty-default)
   - [Dvorak, Colemak, & Workman](#dvorak-colemak--workman-optional)
   - [Modifier Keys](#modifier-keys)
   - [Thumb Clusters](#thumb-clusters)
   - [Media Keys](#media-keys)
3. [Layers](#layers)
   - [Number Layer](#number-layer)
   - [Function Key Layer](#function-key-layer)
4. [Symbol Chords](#symbol-chords)
   - [Common Symbols](#common-symbols)
   - [Basic Math Symbols](#basic-math-symbols)
   - [Parentheses](#parentheses)
   - [Shapes](#shapes)
   - [Intonation](#intonation)
   - [Association](#association)
5. [Action Chords](#action-chords)
   - [Common Actions](#common-actions)
   - [Navigation Chords](#navigation-chords)
   - [Additional Media Chords](#additional-media-chords)
   - [Mouse Chords](#mouse-chords)
   - [Misc Chords](#misc-chords)
6. [Conclusion](#conclusion)
7. [Resources](#resources)

------
## Introduction
### Why Only a 42-Key, 40% Keyboard?
On standard keyboards, many keys require reaching, like the number keys, symbols, etc. **A smaller keyboard reduces finger movement and can greatly increase ergonomics**. The tradeoff to having less keys is generally more complicated usability – the Chordic layout tries to find the sweet spot.
### What is a Chord?
Chords, also known as combos, are **multiple keys pressed together that result in a new action**. Chording is used in stenography and feels similar to playing chords on a piano.
### Considerations
* **The learning curve** – there will be chord memorization, but they are designed to be memorable. If you’re just interested in the absolute basics to get started, just read about the [Base Layout](#base-layout), [Layers](#layers), [Common Symbols](#common-symbols), and [Common Actions](#common-actions).
* **The “L” key is moved** – it takes getting used to. Read why it's been moved in the [Arrow Keys section](#arrow-keys).
* **Accidental letters** – if a chord’s keys aren’t pressed together, the result may be individual characters rather than the intended chord.
* **Accidental chords** – if a word is being typed quickly, a chord could potentially be triggered. Chords have been chosen to avoid this problem, as mentioned in the [QWERTY section](#qwerty-default).
* **Lighter keyboard switches** - recommended for chording multiple keys at a time, I use 50g.
* **An external trackball is necessary for mouse directional keys** – read more in the [Mouse Chords section](#mouse-chords).
* **Keyboard layouts are highly personal** – I don’t expect this to work for everyone. Experiment! 

------
## Base Layout
### Arrow Keys
![chordic-arrow-keys](./images/02-arrow-keys.png)
**Arrows are used often and placed on the base layer**. This layout also makes the **arrow keys easy to be used with modifiers**. While I’ve seen the single-row Vim-style (or DDR-style) positioning of arrows (←↓↑→), the **inverted-T arrow key configuration is more intuitive**. The downside is that the “L” key is moved one space to its right. Read more about why it's been moved in the [QWERTY section](#qwerty-default)


### QWERTY (Default)
![chordic-qwerty](./images/03-QWERTY.png)
I use QWERTY because it’s what I’m used to, but there are **three reasons the Chordic layout works well with QWERTY + arrow keys**:
1. **The chords chosen within this Chordic layout avoid common letter pairings specific to the QWERTY layout**. A chord made up of letters that are common within words (like "A-S"), may be accidentally activated when typing a word quickly (words like "f-A-S-t"), which is why Chordic does not use the chord "A+S" or many other commonly paired letters. 
2. **Home row chords benefit from QWERTY’s less common keys on its home row**. Chords positioned on or near the home row are more convenient – but the more common letters on the home row, the higher the potential for words misfiring as chords.
3. **The Up key on the right-hand home row benefits chording**. A chord that utilizes an arrow key and a letter key is far less likely to accidently fire when typing since these two types of keys are not generally typed quickly in succession. 

### Dvorak, Colemak, & Workman (Optional)
![chordic-dvorak-colemak-workman](./images/04-dvorak-colemak-workman.png)
**All chords in the Chordic layout are key-position based rather than letter-based. Feel free to try to swap in non-QWERTY layouts**. Within the popular alternative layouts, I’ve moved one letter each to prioritize the grouped arrow keys. The Chordic layout is built around avoiding accidental chords within QWERTY only – **non-QWERTY layouts are untested** and may include chords that fall on common letters, potentially causing more chords accidently firing rather than the intended words being typed. 

### Modifier Keys
![chordic-modifier-keys](./images/05-modifier-keys.png)
The modifier column is **ordered by most commonly used keys, from bottom to top** (most to least accessible). The default layout is Mac, but it's easy to swap to the PC layout, as mentioned in the [Misc Chords section](#misc-chords). **Modifiers are instantaneous**. Other layouts require a key to be held to change it into a modifier, but this adds a delay and can mess with regular typing. **Also, this layout parallels how software keyboard shortcuts are written** – modifiers on the left, other key(s) on the right. 

### Thumb Clusters
![chordic-thumb-clusters](./images/06-thumb-clusters.png)
The thumbs are strong and less prone to fatigue, so **common actions are moved away from the pinkies**. On Mac, Caps Lock on some external keyboards has a delay; either hold the chord to activate or install [Karabiner](https://karabiner-elements.pqrs.org/) to remove the delay. In this position, **Shift comfortably capitalizes any letter on either side of the keyboard**. Backspace, Space, and Delete – **all basic text keys are assigned to the right thumb**. They are ordered chronologically in the direction they manipulate text. The lack of Tab/Enter keys is explained in the [Control Key Chords section](#control-key-chords).

### Media Keys
![chordic-media-keys](./images/07-media-keys.png)
**This layout prioritizes control over audio**. The chords for Next, Previous, and Mute buttons are within the [Additional Media Chords section](#additional-media-chords).

------
## Layers
### Number Layer
![chordic-numbers-layer](./images/08-numbers-layer.png)
The number layer is activated by holding or double-tapping "D+F." Double-tapping enters into the layer without the need for holding, and Escape returns to the base layer. On the right side, the numbers are **ordered chronologically, top-down**, with 0 on the spacebar. For keyboard shortcuts that include a number, **this layer is also activated with "W+D" so modifiers are more comfortably within reach**.

### Function Key Layer
![chordic-function-key-layer](./images/09-function-key-layer.png)
Access F1-12 by holding (or double-tapping) "Q+W," which is also placed so function keys can be easily paired with modifiers. Similar to the numbers, function keys are **ordered chronologically, top-down**.

And that’s it for layers!

------
## Symbol Chords
_All symbols are chorded with the right-hand, freeing the left-hand to be used with modifiers. All symbols can be chorded from within the Number Layer_.
### Common Symbols
![chordic-common-symbols](./images/10-common-symbols.png)
**Period** and **Comma** chords share the general placement of their QWERTY counterparts but without leaving the home row. **Colon** and **Semicolon** are the same Period/Comma chords, but with “J” also pressed. **Apostrophe** and **Quote** are each the shape of their symbol.

### Basic Math Symbols
![chordic-basic-math-symbols](./images/11-basic-math-symbols.png)
**Equals** and **Minus** are commonly used as increase/decrease shortcuts, so stacking them feels natural. Quickly typing words like “b-U-Y” may activate the Equals chord. **Underscore** chord is placed below Minus since its character appears as a lowered Minus. Underscore may be activated when words like “da-M-N” are typed quickly. **Plus** chord is the Minus chord with an added key.

### Parentheses
_All parentheses chords are paired next to each other. The most common regular parentheses are placed on the home row_.
![chordic-parentheses](./images/12-parentheses.png)

### Shapes
_These chords reference the symbol's individual shape_.
![chordic-shapes](./images/13-shapes.png)

### Intonation
_These chords reference the vocal rise and fall related to the symbols_.
![chordic-intonation](./images/14-intonation.png)

Words with an **Exclamation Point** drop in emphasis on the final syllable – this downward intonation is replicated by the shape of this chord. Inversely, words with a **Question Mark** have an inflection that starts low, ends high. The **Dollar Sign** symbol replicates a cash register’s sound. “Cha” starts lower while higher emphasis/tone is on “Ching!” 

### Association
_These chords create an association with how a symbol is used or the position of a previously established chord_.
![chordic-association](./images/15-association.png)

When addressing someone, you can use the **At Sign** or point at the person – this chord makes your right-hand point at the person you’re addressing. An **Asterisk** is used for footnotes at the bottom of a page – this chord uses the bottom row, where a footnote would be. The **Ampersand** uses the same chord as Plus (both symbols can mean "and"), only with one less letter. Words like “an-K-H” typed quickly may activate this chord. The **Hashtag** symbol looks like an Equals sign with two vertical lines – so, the Hashtag chord is made up of the Equals chord and the letter “I,” a vertical line. 

------
## Action Chords
### Common Actions
![chordic-common-actions](./images/16-common-actions.png)
**Tab** is conveniently placed, especially for application switching, but quickly typing “J-K” may activate Tab. **Enter**’s chord is similar to its position on  QWERTY but without the need to leave the home row. 

### Navigation Chords
![chordic-navigation-chords](./images/17-navigation-chords.png)
While **Home** and **End** are usually stacked vertically on full-sized keyboards, these chords are horizontal to eachother since they trigger the cursor to jump left and right. End chord could be triggered with words like “P-O-I-nt” typed quickly. **Page Up** and **Page Down** chords neighbor the Scroll Up and Down chords in the [“Mouse Chords” section](#mouse-chords). Activating **Insert**’s “overtype” mode is similar to combining the actions of Space and Delete.

### Additional Media Chords
![chordic-additional-media-chords](./images/18-additional-media-chords.png)

### Mouse Chords
![chordic-mouse-chords-photo](./images/19-mouse-chords-photo.jpg)

_This section requires an external trackball, as the directional mouse keys take too much time to operate and are too imprecise. I’m using the [Ploopy Nano Trackball](https://ploopy.co/nano-trackball/)_. 
![chordic-mouse-button-and-scroll](./images/20-mouse-button-and-scroll.png)
**Mouse Buttons** are placed on the bottom row near the trackball, emulating the feel of a mouse. **Scroll Up** and **Scroll Down** chords are one key position away from Page Up and Down, making for an easy switch between fast or slow page navigation. **Scroll Left** and **Scroll Right** physically rotate your hand to face the direction you want to be scrolling. The Scroll Left chord could trigger with words like “e-L-M.”

### Misc Chords
![chordic-misc-chords](./images/21-misc-chords.png)
**Reset** is visually represented by the line dipping and rising. Which side you use for reseting depends on which side of the keyboard is the parent. **Swap To Mac** is "M+A+C", **Swap To Windows** is ["P+C+M+R"](https://en.wikipedia.org/wiki/PC_Master_Race), the only chords within the Chordic layout specific to key placements on QWERTY. The chord "P+C" isn’t used because quickly typing the letters “P-C” could accidentally activate this chord. Default layout is Mac – refer to [Modifier Keys section](#modifier-keys) for more info on what's being swapped.

------
## Conclusion

And that’s Chordic! A chording-heavy layout that focuses on instantaneousness. While there is a decent amount of chord memorization for symbols, my goal is that the learning process is as simple as it can be.

Remember, layouts are highly personal – what works for me may not for you. I encourage experimentation and tweaking!

If you have a Corne keyboard (aka the crkbd) and want to give this a go, [here are the keymap files](./keymaps) for download to be used with QMK, or [the compiled .hex file](./crkbd_rev1_chordic.hex) ready to be flashed onto your Corne keyboard with QMK Toolbox. The above links have the left side of the keyboard acting as the parent to the right side.

Feel free to reach out if you have any comments, questions, and/or concerns; all feedback is welcome and highly encouraged! Even if I get a message showing a single person made it this far, it'd be extremely satisfying to know I hadn't written all this for just an empty void 😁👍

Also, feel free to [buy me a beverage](https://www.buymeacoffee.com/gfolgert), it would be greatly appreciated. Any donations will likely go right back into keyboard-related things (I'd like to make this into a video if there's interest). Thanks for reading!

------
## Resources
* [**r/ErgoMechKeyboards**](https://www.reddit.com/r/ErgoMechKeyboards/) - subreddit for ergonomic and weird keyboards.
* [**Boardsource.xyz**](https://boardsource.xyz/) – the [Corne keyboard](https://boardsource.xyz/store/5ecc0f81eee64242946c988f) (I have this one) & the [Corne low-profile keyboard](https://boardsource.xyz/store/5f2efc462902de7151495057).
* [**Ben Vallack's "Exploring Usability" YouTube playlist**](https://www.youtube.com/watch?v=WA_GUYS8UJg&list=PLCZYyvXAdQpvysng5wxGkrnIoFtvPibXM) – wonderful videos about split keyboards.
* [**Designing a 36-key custom keyboard layout – Peter Jang**](https://peterxjang.com/blog/designing-a-36-key-custom-keyboard-layout.html) – a solid 36-key layout with similar goals to mine, but with less chording.
* [**Markstos layout**](https://github.com/markstos/qmk_firmware/blob/markstos/keyboards/crkbd/keymaps/markstos/README.md) – a 42-key layout.
* [**QMK Configurator**](https://config.qmk.fm/#/planck/rev6/LAYOUT_ortho_4x12) – an online tool for easily creating firmware files for QMK keyboards.
* [**QMK Toolbox**](https://github.com/qmk/qmk_toolbox) – software that flashes firmware onto your keyboard.
* [**QMK Configurator – Test**](https://config.qmk.fm/#/test) – double check all characters are working properly.
* [**Macro Generator for QMK**](https://codepen.io/mvaneijgen/full/LYEVQXp) – type in the chord you want, this spits out the code needed - saves loads of time.
* [**QMK Documentation**](https://docs.qmk.fm/#/) – great resource for learning about the capabilities of QMK.
