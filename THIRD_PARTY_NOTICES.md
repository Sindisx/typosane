# Third-party notices

## FrequencyWords Russian frequency list

The bundled `ru_50k.txt` file comes from
[`hermitdave/FrequencyWords`](https://github.com/hermitdave/FrequencyWords),
2018 Russian corpus list.

Bundled file SHA-256:
`6095f507cc167488ec66ada5a85ac50433503a08ad24a07c6eabdf54352c4e7f`.

MIT License

Copyright (c) 2016 Hermit Dave

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

The copyright line above applies only to the FrequencyWords corpus.

## cointegrated RuBERT-tiny2

The bundled Core ML candidate scorer and `rubert_tiny2_vocab.txt` are derived
from [`cointegrated/rubert-tiny2`](https://huggingface.co/cointegrated/rubert-tiny2)
by David Dale. The source model is pinned to revision
`e8ed3b0c8bbf4fb6984c3de043bf7d2f4e5969ae` and is used solely as a local
masked-language-model scorer for prevalidated Russian correction candidates.

Source `model.safetensors` SHA-256:
`26ebb6db2a68593c54c74902d7a74f332da66297693f965cc9f1b0af4abf3894`.

Bundled vocabulary SHA-256:
`f056a69b097422652053bf87565c35543e5d81540ca4b7dddd28de4157a969e0`.

The model card at the pinned revision declares the MIT license but does not
publish a separate copyright line or `LICENSE` file. Attribution is preserved
above. The MIT permission and warranty terms reproduced in this notice apply
to this model as well; the FrequencyWords copyright line does not.

**Distribution blocker:** before any binary containing this model is released,
obtain or verify the copyright notice that the MIT license requires preserving,
or replace the model with an asset whose redistribution record is complete.

## ai-forever RuBERT-base

The bundled `RuBERTBaseCandidateScorer` Core ML model and
`rubert_base_vocab.txt` are derived from
[`ai-forever/ruBert-base`](https://huggingface.co/ai-forever/ruBert-base),
pinned to revision `05f37a2ca9e333fd18f30cd0c96c68d274793c69`. Slovolad's
fixed-shape wrapper returns normalized scores only for prevalidated candidate
IDs; it cannot generate arbitrary replacement text.

Source `pytorch_model.bin` SHA-256:
`6ab6521e029933cfd0731798544bf7d51876905752e760919c94e5eb4e37f851`.

Bundled Core ML weight SHA-256:
`11954cd014bdff0cb73981df1bedd0c5bb816092ff6a8c45b1ecf5aea29ddf47`.

Bundled vocabulary SHA-256:
`bbe5063cc3d7a314effd90e9c5099cf493b81f2b9552c155264e16eeab074237`.

The model card declares the Apache License 2.0. The complete license text is
included as `LICENSE.ai-forever-RuBERT.Apache-2.0.txt`.

## Goudron Russian spelling dictionary 1.0.8

The bundled `ru_spelling_forms.txt` membership dictionary is a deterministic
NFC/lowercase/byte-sorted transformation of the official generated word list
from [`Goudron/ru-spelling-dictionary`](https://github.com/Goudron/ru-spelling-dictionary),
release 1.0.8, commit `69a18ae079084f11569f5190ac2080289055ef5e`.

The upstream project and this separate transformed dictionary resource are
licensed under the Mozilla Public License 2.0. The complete readable source
form is the bundled newline-delimited resource itself; the full MPL 2.0 text is
included as `LICENSE.Goudron-Russian-Dictionary.MPL-2.0.txt`.

Upstream generated list SHA-256:
`3519d33eb85dc5d3821b9d1af7b33ef723579e72f4633d495d41762a4b7dd2b7`.

Bundled normalized list SHA-256 (2,344,579 forms):
`f70963b6ec39fe1872993abd13083d8f8ef7226f3bc26d22aac7e078e5c41856`.
