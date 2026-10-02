# komposite_public

Files the Komposite app downloads at first run. Nothing else lives here: this is not the app's
source code.

## EmbeddingGemma (on-device story matching)

The release `embeddinggemma-300m-29888fce` holds two files, copied unmodified from
[`litert-community/embeddinggemma-300m`](https://huggingface.co/litert-community/embeddinggemma-300m)
(revision `29888fce`):

| File | Bytes | SHA-256 |
|---|---|---|
| `sentencepiece.model` | 4,683,319 | `d6daa52d93d7aad10e8388bd526c4e501d914b47177398d1d9621f1fe48438c7` |
| `embeddinggemma-300M_seq256_mixed-precision.tflite` | 179,131,736 | `37115ef7bff76cd37dd86abe503ff511b1032bf85fc624a85c49c84899e92bc5` |

Komposite checks each file against these SHA-256 values before using it.

### Licence and use restrictions

Gemma is provided under and subject to the Gemma Terms of Use found at
[ai.google.dev/gemma/terms](https://ai.google.dev/gemma/terms). See the `NOTICE` file, which is
also attached to the release.

EmbeddingGemma is a model derivative of Gemma. No files have been modified beyond the
quantization already applied by the model's publisher.

By downloading or using these files you agree to the Gemma Terms of Use, including the use
restrictions in the Gemma Prohibited Use Policy at
[ai.google.dev/gemma/prohibited_use_policy](https://ai.google.dev/gemma/prohibited_use_policy).
You may not use them in any way that policy prohibits, and if you pass them on you must pass on
these terms and the `NOTICE` file with them.
