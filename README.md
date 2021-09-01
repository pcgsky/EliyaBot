# EliyaBot

## Filter usage
`!f [condition1] [condition2] ...`

Basically all conditions are AND combined. Some conditions have OR clause in themselves.
#### Attribute / Elements
- `fire` or `f`
- `water` or `w`
- `wind` or `i`
- `thunder` or `t`
- `light` or `l`
- `dark` or `d`
#### Race
`human` `sprite` `beast` `mecha` `dragon` `undead` `youkai` `plant` `demon` `aquatic`
#### Rarity
`5*` `4*`

You can use `1234*` for not 5-star characters.
#### Power Flip Type
`fist` `sword` `bow` `support` `special`
#### Skill Wait
`sw>600` `sw<=380` `sw==460` (Mention you need to use two equal signs)
#### Gender
`male` `female` `unknown` `lily`
### Text filter
Use `-t <text to filter>` to filter by a text. If the text contains spaces, enclose it by quotes (single or double).
e.g. `-t "skill damage"`

If the search text will not be recognized as a condition, you can emit the `-t`.

You can add additional options before the `-t` part. Options will be applied to all `-t` part after them. You can use `reset` to clear the options.  
