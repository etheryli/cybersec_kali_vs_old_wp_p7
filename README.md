# Hung_Nguyen_Cybersecurity_University

# Project 7 - WordPress Pentesting

Time spent: **6** hours spent in total

> Objective: Find, analyze, recreate, and document **three (required) to five (optional) vulnerabilities** affecting an old version of WordPress

## Pentesting Report


1. (Required) 4.0-4.7.2 - Authenticated Stored Cross-Site Scripting (XSS) in YouTube URL Embeds
  - [x] Summary: 
    - Vulnerability types: Stored XSS in WP Core
    - Tested in version: 4.2
    - Fixed in version: 4.2.13
    - Patched in version: 4.7.3
    - CVE-ID: CVE-2017-6817
  - [x] GIF Walkthrough: 
    - [Link 1](https://i.imgur.com/NJzr7hf.gifv)
  - [x] Steps to recreate: 
  - Open up a post to edit to add an embed Youtube video URL
  - Modify the embed Youtube URL like this example:
  - "[embed src='https://youtube.com/embed/12345<svg onload=alert(1)>'][/embed]" 
  - Publish the post with any title and the injected XSS embed URL
  - An error message will display when the post is viewed
  - [x] Affected source code:
    - [Link 2](https://github.com/WordPress/WordPress/commit/419c8d97ce8df7d5004ee0b566bc5e095f0a6ca8)
2. (Required) 3.6.0-4.7.2 - Authenticated Cross-Site Scripting (XSS) via Media File Metadata
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 2](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
3. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 3](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
    
## Assets

List any additional assets, such as scripts or files:


## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2017] [Hung Nguyen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
