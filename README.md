# Project 7 - WordPress Pentesting

Time spent: **10** hours spent in total

## Pentesting Report
1.
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 1.1
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: 
      <img src="https://github.com/Mackpiano96/Week-7-Project-WordPress-vs.-Kali/blob/master/xxs%20walkthrough.gif" width="800">
  - [ ] Steps to recreate: first type the script exploit into the comments section. View the page and hover over the comment.
  - [ ] Affected source code:  "<a href="" onmouseover='alert("XXS")'>test link</a>"
 2.
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 1.1
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: 
    <img src="https://github.com/Mackpiano96/Week-7-Project-WordPress-vs.-Kali/blob/master/xxs%20recording2.gif" width="800">
  - [ ] Steps to recreate: go to a page with a link... modify the source code to include an XSS alert.
  - [ ] Affected source code: "onclick='alert("XXS")'"
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
3. 
  - [ ] Summary: 
    - Vulnerability types: IDOR
    - Tested in version: 1.1
    - Fixed in version: 4.___
  - [ ] GIF Walkthrough: 
  <img src="https://github.com/Mackpiano96/Week-7-Project-WordPress-vs.-Kali/blob/master/IDOR.gif" width="800">
  - [ ] Steps to recreate: Create 2 pages, navigate to second page by changing a number in the URL
  - [ ] Affected source code: N/A
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)

## Resources
- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)
GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2018] [Katelyn Mack]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
