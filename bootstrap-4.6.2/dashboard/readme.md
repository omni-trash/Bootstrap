# Based on Youtube-Vid 2017 "Build A CMS Admin Bootstrap Theme From Scratch"

- https://www.youtube.com/watch?v=pXbEcGUtHgo
- Bootstrap 4.6.2
- jQuery 3.6.0

## Colors
- https://work.smarchal.com/twbscolor/

## Components
- https://getbootstrap.com/docs/4.6/components/

## Editor
- https://ckeditor.com/blog/CKEditor-4.6.1-released/
- https://cdnjs.cloudflare.com/ajax/libs/ckeditor/4.19.1/ckeditor.js

## Icons
- https://useiconic.com/open/
- https://github.com/iconic/open-iconic

## Changes
- https://getbootstrap.com/docs/4.0/migration/
- Bootstrap Glyphen Fonts removed (this project use open-iconic now)
- grid system moved to flexbox
- new breakpoint in grid system (768px, iPad Mini), all levels pushed up, so ``col-md-6`` is now ``col-lg-6``
- switched from ``px`` to ``rem`` units
- headings are larger and some other elmenents
- ``well`` is now ``card``
- ``navbar`` no longer include ``margin-bottom`` (and ``card``, ``list-group`` ... see general.css)
- Dropdowns requires Popper (included in bootstrap.bundle.min.js)

