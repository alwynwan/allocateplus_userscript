# Allocate+ Student++

#### Version 0.10 / 10/02/20

A CSS userscript to make Allocate+ Student use the entire screen and provide an optional dark mode

## Usage

### Without dark mode
1. Get a userstyle extension for your browser (e.g. Stylus for Chrome)
2. Go to [this link](https://userstyles.org/styles/180064/allocate-student-full-screen-dark-theme).
3. Click 'Customize Settings'
4. Set whatever accent colour you wish
5. Click 'Install Style'

### Activating dark mode
1. Open the `userstyle.css` file in any text editor
    - OR go to your userstyle extensions's dashboard and click edit on the style in there  
2. Remove the `/*` and `*/` that surround the `body` block.
```
/*body {
    --bg-col: #333333;
    --text-col: white;
    --bg-dark: #222222;
    --bg-darker: #111111;
    --bg-light: #444444;
    --bg-lighter: #555555;
    --accent-col: #af72e6;
}
*/
```
will become:
```
body {
    --bg-col: #333333;
    --text-col: white;
    --bg-dark: #222222;
    --bg-darker: #111111;
    --bg-light: #444444;
    --bg-lighter: #555555;
    --accent-col: #af72e6;
}
```
3. Save the .css file

## Version History / Changelog
- 0.11
    - Fixed top bar colours
    - Themed session timeout page background
    - Released to Userstyles, made accent colour pickable
- 0.10
    - Finished theming preferences table
    - Themed mobile popout menu 
- 0.0.5
    - Fixed accent colour not working on some elements
    - Started theming preferences
- 0.0.4
    - Added accent colour
    - Fixed theming on timetable
- 0.0.3
    - Started theming timetable
- 0.0.2
    - Started theming Home tab
- 0.0.1
    - Widened the containers to fill entire screen

## License: MIT
```
MIT License

Copyright (c) 2020 Alwyn Wan

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