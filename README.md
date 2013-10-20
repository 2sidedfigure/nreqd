# nreqd

*v0.0.1*

Find the required CommonJS modules in the given path(s).

## Usage

```sh
./nreqd options [path...]
```

One or more paths may be supplied to search recursively. If no path is
supplied, the current directory will be recursively searched. Only plain-text
files will be examined.

### Options

  - **h**: Show usage.
  - **V**: Show version.
  - **l**: Show only relatively referenced modules.
  - **L**: Show only global or search-path referenced modules

## Author

± ryan (ryan@2-si.de). Development was and continues to be sponsored by
[YellowBot](http://www.yellowbot.com).

## License

Copyright (c) 2013 Ryan Ettipio

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
