# FetchUSMWebsite
This JavaScript program uses fetch to make a asynchronous call to http://catalog.usm.edu/preview_program.php?catoid=17&amp;poid=7796&amp;returnto=973 (Links to an external site.) Once the html code is obtained, a JavaScript object is created and the non-link words, such as GEC01, are inserted as keys, and the list of courses are inserted as values. An array is used for the courses. An object is used for each course. For example, { ENG101 : [ 'Composition One', '3hrs'] }
