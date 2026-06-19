# WIP Dvorak TOTEM Config

This layout is faithful to the original Dvorak layout for alphabetic keys. All key combinations possible on a standard keyboard are possible in this keymap with minimal cognitive load on the user.

## Reasoning

### Modifier Keys

- There are not enough empty characters to have all the modifier keys on one layer, and introducing layers occludes characters on lower layers. This is practically unavoidable.
- A momentary layer consumes the finger triggering it, making other keys that would ususally be pressed by that finger inconvenient to press. 
- Even when covering alphabetic characters, the design must be mindful of keeping common key combinations possible.

This is why I have a 'modifier' layer (tab, esc, ctrl, caps, alt, shift) for each side of the keyboard. This allows for practically all combinations as the user decides which half of the keyboard to occlude, this is done with minimal complexity for the user (the layout is the same on each side) and avoids common workaround pitfalls like keys moving around and duplicate keys at the lower layers.

The modifier layer is a safe space for new layer keys that have modifier key combos when there is no space on the base layer. I have also added system and media layer keys to the modifier layers despite not needing them due to ease of use.

### Other

- Layers like bluetooth, volume and macros do not have combination flavoured design constraints.
- Layers that provide keys used in combinations with modifier must be limited to one side.
- If hold/tap style behaviour is used on characters, repeat functionality is disabled, this is not ideal.
- I am hesitant to modify thumb keys across layers, however, the space and enter key (depending on side) are safe to overwrite within the modifier layer as well as the opposite modifier key if you are sure you will never want both layers active at the same time.
- Backspace is on the right as I use it more than delete and my right hand is dominant. Before complaining that it's too far away, consider making fewer mistakes.
- 
