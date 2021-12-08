# Game hangman

This application is a simple console game in Ruby.

## Description

The word to guess is represented by a row of dashes,
representing each letter of the word. Player have only
7 times to make mistake. If the suggested letter does
not occur in the word, program draws one element of
a hanged man stick figure as a tally mark. Russians 
letters "Ё" and "Й" is equivalent russian "Е" and "И".

## Getting Started
* Open program dir in console

Clone program repo
```
git clone git@github.com:StanTim/HangMan.git
```
```
bundle install
```
To add any words in game just open ```data/words.txt``` and input words with new line
### Executing program
* Open program dir in console

* Run file main.rb:
```
ruby main.rb
```

## Authors

Stanislav A. Timanov
[1694569@mail.ru](1694569@mail.ru)

## Version History

* See [commit change](https://github.com/StanTim/HangMan/commits/main)
 or See [release history](https://github.com/StanTim/HangMan/releases)

## License

(c) 2021 Stanislav A. Timanov

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

## Inspiration

 - ["Hangman" on Wiki](https://en.wikipedia.org/wiki/Hangman_(game))
