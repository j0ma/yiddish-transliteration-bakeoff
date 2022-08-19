# Yiddish transliteration bake-off

Both [uroman](https://github.com/isi-nlp/uroman) and [yiddish](https://www.github.com/ibleaman/yiddish) make mistakes when transliterating Yiddish.

Let's see how each of them does against the multi-orthography Yiddish text corpus by Saleva (2020).

## How to run

Just run `./bakeoff` and give it the `uroman` command as a command line argument.

Predictions will be under `./predictions` and diffs from gold standard under `./diffs`.

## References

> Saleva, Jonne. "A Multi-Orthography Parallel Corpus of Yiddish Nouns." Proceedings of the 12th Language Resources and Evaluation Conference. 2020.
