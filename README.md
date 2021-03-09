# php-rs

Bindings for the Zend API to build PHP extensions natively in Rust. Inspired by [killertux/solder](https://github.com/killertux/solder) and its predecessors.

Very much a work-in-progress. The library will likely have to change name before being published on `crates.io`, as `php-rs` is already taken.

## Usage

See the [example project](example/skel). There is inline documentation. Starting by creating a C extension is a good start as well.

## Contributions

Contributions are very much welcome. I am a novice Rust developer and any suggestions are wanted and welcome. Feel free to file issues and PRs through Github.

## License

```
MIT License

Copyright (c) 2021 David Cole <david.cole1340@gmail.com>

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
```