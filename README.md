# Full Dvorak TOTEM Config

This layout is faithful to the original Dvorak layout for alphabetic keys. All key combinations possible on a standard keyboard are possible in this keymap with minimal cognitive load on the user.

The following features are implemented in their own layers
- Alphabet
- Modifier keys (shift, tab, esc, win, ctrl, alt, caps)
- 

## Design Details

### Problems

- There are not enough empty characters to have all keys on one layer, and introducing layers occludes characters on lower layers. This is practically unavoidable.
- If a key often has combinations with base layer characters, it is a 'modifier' key. It needs special consideration to avoid making character combinations impossible.
- A momentary layer consumes the finger triggering it, making other keys that would ususally be pressed by that finger inconvenient to press.
- If hold/tap style behaviour is used on characters, repeat functionality is disabled, this is not ideal.

### Solutions

My 'modifier' layer is duplcated for each side of the keyboard, allowing for practically all combinations as the user decides which half of the keyboard to occlude, this is done with minimal complexity for the user and avoids common workaround pitfalls like keys moving around and duplicate keys at the lower layers.

Additional layers that have modifier combinations, like navigation, have been made completley one-sided so that modifiers still work.

### Notes

I am hesitant to modify thumb keys across layers out of preference, however, the space and enter key (depending on side) are safe to overwrite within the modifier layer as well as the opposite modifier key if you are sure you will never want both layers active at the same time.
- Backspace is on the right as I use it more than delete and my right hand is dominant. Consider making fewer mistakes if this is an issue.
