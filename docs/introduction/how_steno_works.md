# How steno works

If you're here, reading this, then you've probably heard something great about stenography. Maybe you've heard about the court reporting profession, about how professional stenographers can write down every word that's said for hours at a time. Maybe you've met a captioner who essentially watches TV for a living. Maybe you've heard from someone who replaced most or all of their computer input with a steno machine, and they've told you about the ergonomics boost, the speed boost. Maybe you've seen inhuman records on competitive typing sites.

How is it possible? How can someone just "learn" something and then be twice or three times as fast as they previously were, keyboarding? Why does the average keyboardist coast somewhere in the 50-150 words per minute range, while stenographers regularly break that barrier? Why isn't stenography ubiquitous?

Today I want to illustrate, at a high level, how stenography works, and how that equals speed and ergonomics.

## Layout

The first, most obvious difference between a regular computer keyboard and the steno machine is the key layout. On the standard computer keyboard, letters and numbers are uniformly squares and layed out in a staggered layout. Counting all the special keys like the arrow keys, shift, enter, etc., you are looking at around 90 or more keys.

In contrast, the steno machine has 24 functional keys. The bar at the top counts as one modifier key, kind of like having a shift key along the entirety of your keyboard. Steno has fewer keys, but does a lot more with them by using multiple keys at once; if you hit two keys at once, the action is different then hitting each of those keys in succession.

## Homerow

On Qwerty, the standard American keyboard layout, the home row is made up of keys `asdf jkl;`. In touch-typing classes, students are taught to return to the home row in order to maintain the placement of their hands. This is why on most keyboards, the `f` and `j` keys have little nubs.

One common optimization for the traditional keyboard is rearranging the letters. Dvorak, Colemak, and other custom layouts aim to move the most common letters in English to the home row. The thought is that if your hands default to where they most likely need to be, there's less finger and hand movement, thus improved ergonomics and potentially speed.

On the steno machine, with its reduced number of keys, the home row is where over 95% of writing happens. The most movement that a finger will need to move in any direction is one key width, and only for certain fingers. In steno, the most fingers are responsible for only two keys, with exception to the right hand pinky which must deal with four keys, and the index fingers which have to deal with three. There is also the bar at the top which is used infrequently but can be used with any available finger.

The home row is actually the cracks between the keys.

## Striking keys on a keyboard

**In typing,** there are three types of keys: symbols, modifiers, and commands.  Symbol keys output a symbol when you strike them. Press the `a` key, an `a` appears on the screen. Modifiers, like the "shift" key, change the behavior of the symbol keys. When holding shift, `a` becomes `A`.

Finally, command keys exist which aid with navigation of the computer. You can use delete, backspace, and the arrow keys to aid in editing a document, or page up, page down, home, and end to navigate documents.

Hitting a single key in typing is called a *keystroke*.

For the most part, typing is a very "serial" operation; meaning the keys you hit have output in the same order that you hit them. If you type `t e h` the output is, obviously, `teh`, even if you were trying to write `the`.

In order to be fast at typing speech, you need to have several skills:

- **Spelling** in order to hit the right keys in the right order for words you hear.
- **Finger speed** in order to hit the keys fast enough. Generally, the speed curve for typing is very simple: the more keys you can hit correctly in a minute, the faster you will be able to type. This is presents a problem for people who hit a wall where they are unable to write faster even after extensive training.

In short, **typing involves hitting keys sequentially in the right order.**

## Striking keys on a steno machine

**In steno,** there is really only one kind of key. It's a key that, if pressed alone, will perform an action, and if pressed with other keys, will perform a different and potentially unrelated action.

Unlike keyboarding, the difference between commands, symbols, and modifiers is not determined at the key level.

Instead, there's a level of abstraction. Any combination of a set of keys (including a single key) can be mapped to any set of actions. So in typing, you have one key that maps to all of `t`, `h`, and `e` and you must use all three of them to accomplish writing `the`. In steno, we map a single keystroke to the word `the` because it's so common in English. This is an example of one key with a single stroke mapping to three "actions" (`t`, `h`, and `e`.)

Hitting a set of keys in steno is called a *stroke*.

Stenographers have an order to the keys in order to refer consistently to the keys they hit. If you wanted to indicate on Qwerty that you hit the `t`, `h`, and `e` keys in no particular order, you could say `the`, `teh`, `eth`, `eht`, `het`, or `hte`. In steno, we have a rule so that the order of the keys will always be the same so that when you hit `TOP` it's always read and talked about as `top` and not `pot`, `tpo`, `opt`, or anything else.

**A steno stroke ends up mapping to roughly a syllable.** While many proper English syllables can be formed, sometimes they are nonsensical. There are too many consonants that don't really make sense together (`SKPATD`) or there's no vowel (`P-L`) or it's just a single key (`W`), but the bulk of strokes map to simple sounds that you should be able to decipher: `POT`, `MOM`, `KAT`, `SHOP`, `TRAK`, `TRUBL`. Additionally, syllables can be strung together to form more complex words. For example: `WIN/DOE` or `UN/RE/MARK/-BL`.

While there is something to be said for the complexity of a stroke, usually the number of keys is less important than when typing. To hit five keys on a steno machine is usually about as easy as pressing one. This means that, for the same effort as one stroke, we can express *a lot more* than a single letter. And that's where steno's speed comes from.

## What a steno strokes maps to

- State
  - Spacing
  - Capitalization
- Symbols
- Affix
  - Prefix
  - Suffix
- Words
- Briefs
- Phrases

## Capitalization and spacing

To contrast with typing, capitalization and spacing are handled automatically. As you provide words and symbols on the steno machine, the output is joined logically. The system is designed such that in standard writing, providing a stroke that maps to a sentence-ending period will output as you'd expect: attached to the last word, and causing the next word to be capitalized. There's some state involved here which you can manually override.

Let's take a quick look at how a stenographer might key in a sentence, with each slash indicating a new stroke: `let/the/cat/be/(period)/he/is/not/in/a/great/mood/(semicolon)/someone/tried/to/bathe/him/(period)/I/think/it/was/John/(period)` and the final output is `Let the cat be. He is not in a great mood; someone tried to bathe him. I think it was John.` The spacing between words and lack of spacing before punctuation is automatic. Capitalization of "let" and "he" is done automatically. "I" and "John" are always capitalized and the steno machine outputs them that way.

Of course, while this is sufficient for most writing, there are cases when you need to override the defaults. There are strokes that allow you to force a capitalization, uppercase an entire word, force the a proper name to be lower, suppress spacing, insert extra spaces, and all sorts of little modifications depending on what you need.

## Symbols

One huge advantage that stenography has over traditional typing is the range of input characters you can use.