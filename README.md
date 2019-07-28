# kagerou-style

CSS overrides for the [Kagerou FFXIV parser plugin](https://github.com/hibiyasleep/kagerou) that make it a bit more compact, and stop certain fields from getting clipped. I use it with the columns:

- **Info**: Class Icon
- **Info**: Name
- **DPS**: per Second
- **DPS**: Accuracy (1 - Miss / Swing)
- **Heal**: Heal %
- **Heal**: Overheal
- **Etc**: Deathcount

With different columns, it may not look as good, but honestly I have no idea.

This is terrible, `!important`-ridden CSS, but that's the life you live when you're writing overrides I suppose.

## Installation

Once you have Kagerou set up, go into settings by clicking the gear, then click "More" and paste the contents of [`style.css`](https://github.com/Corvimae/kagerou-style/blob/master/style.css) into the CSS tab's text input.
