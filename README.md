# TLM-1: Tiny Language Model

**[Switch it on →](https://revbrd.github.io/tiny-language-model/)**

If a large language model is large, what's a tiny one? This one. A pea-green handheld from a
1980s that never happened, running a bigram Markov chain and calling itself a language model.

Feed it text on the training tape, press TRAIN, press SPEAK, and it babbles. Flip it into
✻ THINKING mode for 100% more memory (two words instead of one) and it will show you every step of
its deliberation, all of which is real, and then tell you how long it thought.

## The part that isn't a joke

Use the probe to hand it a phrase it has never seen. It doesn't guess badly. It can't guess at
all: the tape prints `DEAD END` and perplexity reads **∞**, because the model gave that word a
probability of exactly zero.

That ∞ is the edge where looking things up stops and generalising would have to begin. Larger
models don't get past it by having seen more phrases. They get past it by computing a
distribution instead of retrieving one.

## Credits

Made by [RevBrd](https://github.com/RevBrd) with Claude.

## License

MIT. See [LICENSE](LICENSE).
