# Env-MCRO-XL
 The XL version of my MCRO pad

##

### KLE information and LAYOUT Macro
```json
[{a:7},"","","",""],
[{y:-0.75,x:4.25,a:4},"Enc"],
[{y:-0.5,x:5.5},"Layer"],
[{y:-0.75,a:7},"","","",""],
[{y:-0.5,x:4.25,a:4},"Enc"],
[{y:-0.5,a:7},"","","","",{x:1.5,a:4},"Layer"],
[{y:-0.25,x:4.25},"Enc"],
[{y:-0.75,a:7},"","","",""]
```

```c
#define LAYOUT( \
	K00, K01, K02, K03, K04,           \
	K10, K11, K12, K13, K14, K15,      \
	K20, K21, K22, K23, K24, K25,      \
	K30, K31, K32, K33  \
) { \
	{ K00,   K01,   K02,   K03,   K04,   KC_NO, KC_NO }, \
	{ K10,   K11,   K12,   K13,   K14,   K15,   KC_NO }, \
	{ K20,   K21,   K22,   K23,   K24,   K25,   KC_NO }, \
	{ K30,   K31,   K32,   K33,   KC_NO, KC_NO, KC_NO }  \
}
```