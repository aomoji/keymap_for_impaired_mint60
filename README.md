# keymap_for_impaired_mint60

Alternative keymap for mint60 that has impaired Esc, Tab, Caps lock, Left shift key.

[keymap image](./image/keymap.png)


If you want to enable mouse key, change `MOUSEKEY_ENABLE` in `rules.mk` and write the mouse settings in `config.h` .

```
MOUSEKEY_ENABLE = yes       # Mouse keys(+4700)
```

```
// mouse settings
#define MOUSEKEY_DELAY             5
#define MOUSEKEY_INTERVAL          10
#define MOUSEKEY_MAX_SPEED         3
#define MOUSEKEY_TIME_TO_MAX       5
```
