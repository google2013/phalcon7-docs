Class **Phalcon\\Assets\\Filters\\Jsmin**
=========================================

*implements* :doc:`Phalcon\\Assets\\FilterInterface <Phalcon_Assets_FilterInterface>`

.. role:: raw-html(raw)
   :format: html

:raw-html:`<a href="https://github.com/dreamsxin/cphalcon7/blob/master/ext/assets/filters/jsmin.c" class="btn btn-default btn-sm">Source on GitHub</a>`

Deletes the characters which are insignificant to JavaScript. Comments will be removed. Tabs will be replaced with spaces. Carriage returns will be replaced with linefeeds. Most spaces and linefeeds will be removed.


Methods
-------

public *$content*  **filter** (*string* $content)

Filters the content using JSMIN



