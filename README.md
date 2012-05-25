mPDF
====

This is non-official repository for [mPDF](http://mpdf.bpm1.com)

This repository was created only for my tasks, you can use it at your own risk:

Installation
------------

Add mPDF to your vendors:

    git submodule add http://github.com/yashchar/mPDF.git vendor/mpdf
    
Or you can use deps file:

    [mpdf]
    git=http://github.com/yashchar/mPDF.git
    target=/mpdf

Add both to your autoload:

    // app/autoload.php
    $loader->registerNamespaces(array(
        // ...
        'mPDF'             => __DIR__.'/../vendor/mpdf',
        // ...
    ));

Usage
---------------------

Watch examples directory