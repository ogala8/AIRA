
# Markivis AIRA: Artificial Intelligence for Review Analysis

An application for sentiment analysis and multi-label classification for Markivis reviews.

Supported languages:

- English


## Authors

- [@omar.galarraga](https://github.com/ogala8)


## Support

For support, email omar.galarraga@polesante.eu or contact Markivis team.


## Installation

Install with pip

```bash
  pip install git+https://github.com/ogala8/AIRA.git#egg=AIRA
```

## Example

```bash
  python -m aira.app
```

Open the app. 
Upload your file (i.e. myreviews.xlsx)
This should create a aiprocessed_myreviews.xlsx file with automatic download possibility. 
All the uploaded files are stored in "original" and the generated files are stored in "results".


## Road Map

- Maximum probability yes/no when conflict
- Test metrics when labels in test file
     
## License

[The MIT License (MIT)](https://choosealicense.com/licenses/mit/)

Copyright (c) 2023 Omar Galarraga, Markivis

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