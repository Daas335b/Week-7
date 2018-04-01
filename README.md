Project 7 WordPress Pentesting
Time spent: 16 hours in total

## Pentesting Report

1. (Required) Vulnerability Name is Cross-site scripting
  - [ ] Summary: 
    - Vulnerability types:  Cross site scripting
    - Tested in version: 4.2
    - Fixed in version: 4.7.5
  - [ ] GIF Walkthrough: <img src='put your name here.gif'/>
  - [ ] Steps to recreate: 
 as admin.http://wpdistillery.vm/wp-admin
  I went to a page.  In the comment section I wrote the following
  - [ ] Affected source code: http://klikki.fi/adv/wordpress2.html      CVE-2015-3440
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  - [ ] Summary: 
  
  2. - Vulnerability types:  large Media file with XSS
    - Tested in version: 4.2
    - Fixed in version: 4.7.3
  - [ ] GIF Walkthrough: <img src='put your file name here.gif'/>
  - [ ] Steps to recreate: Downloaded a moon image file from the internet that was 3.2mb.  Changed the name of the file .  I logged into wordpress media page and dragged my large file with the name <svg onload='alert(228)'>
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  
3. (Required) , CVE-2018-6389
  - [ ] Summary: an attack that forces an end user to execute unwanted actions on a web application in which they're currently authenticated
    - Vulnerability types:
    - Tested in version:4.2
    - Fixed in version: 4.9
  - [ ] GIF Walkthrough: <img src='put your file name here.gif'/>
  - [ ] Steps to recreate:Create a file that was larger than 65kb .  Inserted this script at the beginning of the file......
  Paste my script on the comments section and a sign saying hello wrld came up.
  
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2018] [Sandy Keh]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
