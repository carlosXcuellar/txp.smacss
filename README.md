txp.smacss
==============

A barebones Textpattern theme using [Bourbon](http://bourbon.io/) and [Neat](http://neat.bourbon.io/) and following [SMACSS](http://smacss.com/) guidelines.

Requires [cnk_versioning](https://github.com/cuellarllar/txp.smacss/blob/master/textpattern/plugins/cnk_versioning.txt) plugin.

Demo site: [http://txp-smacss.carloscuellar.net/](http://txp-smacss.carloscuellar.net/)

## Install

1. Drop [/txp.smacss](https://github.com/cuellarllar/txp.smacss) in the root directory of your Textpattern project.
2. Install Textpattern plugin [cnk_versioning](https://github.com/cuellarllar/txp.smacss/blob/master/textpattern/plugins/cnk_versioning.txt) and edit the path in it's source to point to [/txp.smacss/textpattern/_templates](https://github.com/cuellarllar/txp.smacss/tree/master/textpattern/_templates). Follow cnk_versioning's own instructions via the plugin's help if you are not already familiar with how it works.
3. Sally forth.

## Using Sass

    $ cd txp.smacss 
    $ gem install sass
    $ sass --watch scss:css
