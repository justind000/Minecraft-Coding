# My Tutorial

## Step 1

Here is some text.

## Step 2

Congratulations, you did it!

## Step 3 - Show the temperature

Get a ``||player:ontravelled||`` block and place it in the value slot of ``||basic:show number||``.

```blocks
player.onTravelled(WALK, function () {
    if (blocks.testForBlock(TOP_SNOW, pos(0, 0, 0))) {
        player.say("burr!")
    }
})
```