Lorem.js Dummy Text/Image Generator jQuery and Native JS
========================================================
A Lorem Ipsum creator service written on JavaScript.


Implementation
--------------

Implementation of Lorem.js is so simple,

You just download and add

    <script src="path/to/lorem.js"></script>

into your website/application and run.


Usage:

    var lorem = new Lorem;
    lorem.type = Lorem.TEXT;
    lorem.query = '2p';
    lorem.createLorem(document.getElementById('lorem'));


Querying
--------

Lorem.js has a simple query language: "how many?, what?"

    2p = 2 paragraphs
    5s = 5 sentences
    6w = 6 words
    1-6w = between 1 and 6 words

That's it.

Dummy Images
------------

Lorem.js uses lorempixel.com for images.

Usage:

    var lorem = new Lorem;
    lorem.type = Lorem.IMAGE;
    lorem.query = 'sports';
    lorem.createLorem(document.getElementById('lorem'));



Feel free to ask questions.
