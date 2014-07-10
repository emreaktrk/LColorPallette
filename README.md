LColorPallette
==============

A Color Pallette that includes all the colors respects Android Material Design.
Thanks "Marcel Ulbrich" for creating datas.

TODO
-----

* Publish to Maven Central

Setup
-----

Download [```lcolorpallette@1.0.aar```](https://github.com/emreaktrk/ContextualView/blob/master/lcolorpallette@1.0.aar?raw=true) and put it to libs folder.
Add these lines to ```build.gradle``` in app module.

```
repositories {
    flatDir {
        dirs 'libs'
    }
}

dependencies {
    compile(name:'contextualview@1.0.aar', ext:'aar')
}
```

Acknowledgements
----------------

This project uses the API 15 to 19.
It does not uses any library.


Developed By
------------

Emre Akturk
Marcel Ulbrich

License
--------

    Copyright 2014 Emre Akturk.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
