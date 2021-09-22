
> Open deze pagina op [https://teacherpinky.github.io/wait-until-blocks/](https://teacherpinky.github.io/wait-until-blocks/)

## Usage

### wait until button is pressed

Waits until button A is pressed before the next line of code is executed. You can also choose button B or A + B.

```blocks
WaitUntilBlocks.waitUntilButtonPressed(Button.A)
```

### wait until button is released

Waits until button A or B is released before the next line of code is executed. You can also choose button B or A + B.

```blocks
WaitUntilBlocks.waitUntilButtonReleased(Button.A)
```

### wait until pin is pressed


Waits until the chosen pin is pressed before the next line of code is executed. You can choose pin 0, 1 and 2.


```blocks
WaitUntilBlocks.waitUntilPinPressed(TouchPin.P0)
```

### wait until pin is released


Waits until the chosen pin is released before the next line of code is executed. You can choose pin 0, 1 and 2.


```blocks
WaitUntilBlocks.waitUntilPinReleased(TouchPin.P0)
```

### wait until sound level is below

Waits until the sound level is below a chosen value before the next line of code is executed.

```blocks
WaitUntilBlocks.waitUntilSoundLevelBelow(80)
```


## Gebruiken als extensie

Deze repository kan worden toegevoegd als **extensie** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klik op **Nieuw project**
* klik op **Extensies** onder het tandwielmenu
* zoeken naar **https://github.com/teacherpinky/wait-until-blocks** en importeren

## Dit project bewerken ![Badge buildstatus](https://github.com/teacherpinky/wait-until-blocks/workflows/MakeCode/badge.svg)

Om deze repository te bewerken in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* klik op **Importeren** en klik vervolgens op **Importeer URL**
* plak **https://github.com/teacherpinky/wait-until-blocks** en klik op importeren


#### Metadata (gebruikt voor zoeken, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
