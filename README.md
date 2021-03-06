Deprecated!
==============

Use the [seven_zip](https://github.com/daptiv/seven_zip) cookbook which replaces this one.

7-zip Cookbook
==============
[7-Zip](http://www.7-zip.org/) is a file archiver with a high compression ratio. This cookbook installs the full 7-zip suite of tools (GUI and CLI).


Requirements
------------
### Platform
- Windows XP
- Windows Vista
- Windows Server 2003 R2
- Windows 7
- Windows Server 2008 (R1, R2)
- Windows 8
- Windows Server 2012

### Cookbooks
- windows


Attributes
----------
- `node['7-zip']['home']` - location to install 7-zip files to.  default is `%SYSTEMDRIVE%\7-zip`


Usage
-----
### default
Downloads and installs 7-zip to the location specified by `node['7-zip']['home']`.  Also ensures `node['7-zip']['home']` is in the system path.


License & Authors
-----------------
- Author:: Seth Chisamore (<schisamo@opscode.com>)

```text
Copyright:: 2011, Opscode, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
