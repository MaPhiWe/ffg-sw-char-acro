FFG Star Wars Character for Acrobat
===================================

> Custom, form-fillable, character sheets for the Star Wars Roleplaying games.

Summary
-------

Character sheets for **Edge of the Empire**, **Age of Rebellion**, and **Force
and Destiny**. 

![EotE Gray Front](./pub/img/aurebesh-eote-g-front.png)
![AoR Gray Front](./pub/img/aurebesh-aor-g-front.png)
![FaD Gray Front](./pub/img/aurebesh-fad-g-front.png);

In **color** too!

![EotE Front](./pub/img/aurebesh-eote-front.png)
![AoR Front](./pub/img/aurebesh-aor-front.png)
![FaD Front](./pub/img/aurebesh-fad-front.png);

And now, **form fillable** in [Adobe Reader][reader].

Get the goodies in the [pub](./pub) directory (_form fillable versions have a
'-ff' at the end of the filename_).

### Caveats 

> I highly recommend using the latest version of [Adobe Reader][reader] with
> these.  Although they can be used with other PDF readers, I can not guarantee
> that they will appear as intended, or save the form field data in the correct
> way.

I only used form fields.

There is no interactiveness to these.

This was in an effort to make these as wildly useful as possible.


[reader]: http://get.adobe.com/reader/ "Adode Reader"

Usage
-----

### Skills ###

![Skills Usage](./pub/img/skill-usage.png)

* Fill in the circle if it is a _career_ skill.
* Fill the bottom triangle of the _pool_ box for each rank of a
  characteristic you have for that skill
* Fill in the top part when you get a rank.
* This way you can read it as 'filled', 'filled', 'half' equals
  'proficiency', 'proficiency', 'ability' (or for the color obsessed 'yellow',
  'yellow', 'green').
* _Alternatively_ you can use a slash for ability, and an opposite slash (which
  makes an 'X') to indicate ability/proficiency.

### Development Trees ###

![Development Tree Usage](./pub/img/development-tree-usage.png)

* Put an 'X' in the box if you have purchased that column/row of the tree.
* For powers, and other trees where an ability spans multiple columns, put a
  line through the relevant boxes.
* Use the _Abilities_ section to actually summarize the individual abilities that
  come from purchasing the talents.


Internationalization (i18n)
---------------------------

* [German](./README.de.md)

In the interest of making these available to the widest possible audience, I'm
working on a way to layout my illustrator files using JavaScript.

By incorporating a simple database of strings (eg. a JavaScript file) in the
script that lays out the page I can quickly create new versions with regionlized
strings.

### Translations

The illustrator template(s) and scripts will all be available in this repository
for your own use at some point. However, until I've finished the i18n scripts and
documented the process to run the various scripts in Illustrator® and Acrobat®,
it's probably easiest for others to translate database files and I generate the
localized version.

1. Fork this repository.

2. In your fork, copy the existing 'en.js' file inside the
   [lib/i18n/strings](lib/i18n/strings) directory and name it with the
   appropriate [BCP 47](BCP47) code (find a [discussion on language tags
   here][language-tags]).

3. At the top of the file are a couple of strings that need to be changed to
   reflect the current language, and any language that it is based on.

   The first is the one right after the `new Strings(`. This one sets the
   current language name. Use a BCP 47 code (i.e: 'fr', 'fr-CA', 'en-GB',
   etc...).

   The second is the commented out `base: 'en'` line. Un-comment that line.
   Unless you are creating a more regionalized version of the strings ('fr-CA',
   from 'fr') leave it as 'en', otherwise set it to the more generic language code.

4. Update the strings in the file.

5. When you are ready, issue a pull request for me to incorporate your changes.

6. Given my schedule, I will post the resulting PDFs as soon as I can.

[language-tags]: http://www.w3.org/International/questions/qa-choosing-language-tags
[BCP47]: https://tools.ietf.org/html/bcp47

Report an Issue
---------------

* [Bugs](http://github.com/jhamlet/ffg-swchar-acro/issues)
* Contact the author: <jerry@hamletink.com>


License
-------

> Copyright (c) 2014 Jerry Hamlet <jerry@hamletink.com>
> 
> Star Wars and all related terms are the registered trademarks of LucasFilm
> Limited, its associated bodies, and the Disney Corporation. Edge of the
> Empire, the dice symbols, and associated rules terminology are the property of
> Fantasy Flight Games. As such, the author of this document makes no claim of
> ownership to any of the afore-mentioned material.
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy of
> this software and associated documentation files (the "Software"), to deal in
> the Software without restriction, including without limitation the rights to
> use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
> the Software, and to permit persons to whom the Software is furnished to do so,
> subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
> 
> The Software shall be used for Good, not Evil.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
> FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
> COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
> IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
> CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
> 
