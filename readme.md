# Tree of Savior Addon: Weight Percentage Calculator

A lightweight addon showing the weight percentage of your backpack.

## Usage:
Type `/weight` in chatbox, and then the results are shown in messages.

![type `/weight` in chatbox](https://github.com/hiiwave/TosAddon-weightpercentage/blob/master/demo/command.JPG)

![result image](https://github.com/hiiwave/TosAddon-weightpercentage/blob/master/demo/output1.JPG)

## More commands:
`/weight 0.5` to filter out categories with weight <= 5%

`/weight potion` to separate *potion* from *Consume*

![result](https://github.com/hiiwave/TosAddon-weightpercentage/blob/master/demo/output2.JPG)

## Note:
The total weight (in backpack) shown in result only includes items inside backpack. It does not include wore equipment.

That is, `total weight in all` = `total weight in backpack` + `total weight of wore equipments`

The percentage shown is calculated over `total weight in backpack`, which is a bit larger than the percentage over `total weight in all`.

## Contibution:
Pull request is welcome :)
