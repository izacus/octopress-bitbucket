Bitbucket aside for Octopress blog
===================================

This is an aside plugin listing Bitbucket repositories based on default Octopress GitHub plugin.

Installation
--------------

1. Copy `bitbucket.html` into `source/_includes/asides` directory.
2. Copy `bitbucket.js` into `source/javascripts` directory.
3. Add bitbucket configuration parameters to your `_config.yml` file:

```
default_asides: [ ..., asides/bitbucket.html, ...]

bitbucket_user: <username>
bitbucket_show_profile_link: true
bitbucket_skip_forks: true
```

That's it. Note that repo output is limited to a single API page right now.


License
===================================


(The MIT License)

Copyright © 2013 Jernej Virag

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.