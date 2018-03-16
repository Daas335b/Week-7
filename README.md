Project 7 WordPress Pentesting
Time spent: 10 hours in total

## Pentesting Report

1. (Required) Vulnerability Name is Cross-site scripting
  - [ ] Summary: 
    - Vulnerability types:  Cross site scripting
    - Tested in version: 4.2
    - Fixed in version: 4.7.3
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
 I logged into wordpress as admin.http://wpdistillery.vm/wp-admin
  I went to a page I created.  In the comment section I wrote the following xss <svg/onload-alert('XSS')
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  - [ ] Summary: 
    - Vulnerability types:  SQL injection with a large file
    - Tested in version: 4.2
    - Fixed in version: 4.7.3
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: I downloaded a large image file from the internet.  One that was more than 2mb. I changed the name of the file to what I wanted to inject.  I logged into wordpress as admin.http://wpdistillery.vm/wp-admin and went to the media page where I dragged my large file with the name <svg onload='alert(228)'>
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: [](my_gif_walkthrough_url)
  - [ ] Steps to recreate: 
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

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
