# Third-Party Notices

Chessimal is built on open-source components. Their licences are reproduced or referenced
below, as those licences require when the software is distributed in binary form. Each
component remains under its own licence; nothing in Chessimal's own `LICENSE` limits the
rights those licences grant you.

This list covers the components linked into the shipped desktop builds. It is maintained by
hand alongside `tool/license_audit.sh` in the application source tree, which enforces that
every dependency is MIT, BSD, Apache-2.0, ISC, Zlib or CC0 — no copyleft code is linked in.

## Chess engine and rules

| Component | Licence | Use |
|---|---|---|
| [Arasan](https://www.arasanchess.org/) 26.0 by Jon Dart | MIT | The chess engine, vendored and compiled into the app |
| [bishop](https://pub.dev/packages/bishop) by Alex Baker | MIT | Move generation, FEN/PGN/SAN |
| [squares](https://pub.dev/packages/squares) by Alex Baker | MIT | The chessboard widget |

## Machine learning

| Component | Licence | Use |
|---|---|---|
| [Maia-2](https://github.com/CSSLab/maia2) (CSSLab, University of Toronto) | MIT | Human-like opponent move prediction |
| [ONNX Runtime](https://onnxruntime.ai/) (Microsoft) | MIT | Runs the Maia-2 model on device |
| [flutter_onnxruntime](https://pub.dev/packages/flutter_onnxruntime) | MIT | Flutter bindings for ONNX Runtime |

## Puzzle content

The bundled puzzle set is derived from the [Lichess open puzzle
database](https://database.lichess.org/#puzzles), released under
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain dedication).
Attribution is not required; it is given with thanks.

## Application framework and packages

[Flutter](https://flutter.dev/) and the Dart SDK (Google) — BSD-3-Clause.

The following pub.dev packages are linked into the app:

| Package | Licence |
|---|---|
| `crop_your_image` | Apache-2.0 |
| `cupertino_icons` | MIT |
| `dio` | MIT |
| `drift`, `drift_flutter` | MIT |
| `ffi` | BSD-3-Clause |
| `flutter_riverpod` | MIT |
| `go_router` | BSD-3-Clause |
| `image` | MIT |
| `image_picker` | BSD-3-Clause |
| `package_info_plus` | BSD-3-Clause |
| `path_provider` | BSD-3-Clause |
| `share_plus` | BSD-3-Clause |
| `sqlite3` (and SQLite itself, public domain) | MIT |
| `url_launcher` | BSD-3-Clause |
| `uuid` | MIT |

## Fonts

Fredoka and Nunito are licensed under the [SIL Open Font License
1.1](https://openfontlicense.org/).

## Licence texts

### MIT License

> Permission is hereby granted, free of charge, to any person obtaining a copy of this
> software and associated documentation files (the "Software"), to deal in the Software
> without restriction, including without limitation the rights to use, copy, modify, merge,
> publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons
> to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or
> substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
> INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
> PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE
> FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
> OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
> DEALINGS IN THE SOFTWARE.

### BSD-3-Clause

> Redistribution and use in source and binary forms, with or without modification, are
> permitted provided that the following conditions are met:
>
> 1. Redistributions of source code must retain the above copyright notice, this list of
>    conditions and the following disclaimer.
> 2. Redistributions in binary form must reproduce the above copyright notice, this list of
>    conditions and the following disclaimer in the documentation and/or other materials
>    provided with the distribution.
> 3. Neither the name of the copyright holder nor the names of its contributors may be used
>    to endorse or promote products derived from this software without specific prior written
>    permission.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS
> OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
> MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
> COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
> EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
> SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
> HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR
> TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
> SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

### Apache-2.0

Full text: <https://www.apache.org/licenses/LICENSE-2.0>

### SIL Open Font License 1.1

Full text: <https://openfontlicense.org/open-font-license-official-text/>
