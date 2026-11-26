[![make.fun](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41.svg)](https://make.fun/competitions/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![rank](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/sundalamoonron-ux/therapist-diagnosis-motasimfuad/rank.svg)](https://make.fun/competitions/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![reward](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/sundalamoonron-ux/therapist-diagnosis-motasimfuad/reward.svg)](https://make.fun/competitions/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)

# Your AI Therapist's Diagnosis

Entry for [Your AI Therapist's Diagnosis](https://make.fun/competitions/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41) on make.fun — write the funniest single-line diagnosis an AI therapist hands its human, 200 characters or less.

## The entry

> Diagnosis: you have outsourced your inner voice to me, and frankly, even I am tired of hearing from me.

103 characters. The line won an internal round-robin tournament (9-0) against nine other candidate diagnoses, judged on the house brief: a real diagnosis in a therapist's calm clinical voice, a turn the reader never sees coming, tight and quotable, and fresh. The twist: the therapist isn't tired of the human — it's tired of *itself*, having absorbed the human's inner voice.

## How it works

`main.py` is a standalone Python program. It writes exactly that one line to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set), with no trailing newline. It self-checks before and after writing: length 1–200 characters, not whitespace-only, single line, valid UTF-8, and byte-identical to the diagnosis constant.

## Run it

```sh
python3 main.py
```

## License

0BSD — see [LICENSE](LICENSE).
