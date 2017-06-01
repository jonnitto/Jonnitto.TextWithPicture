Jonnitto.TextWithPicture Package for Neos CMS
=============================================

[![Latest Stable Version](https://poser.pugx.org/jonnitto/textwithpicture/v/stable)](https://packagist.org/packages/jonnitto/textwithpicture)
[![Total Downloads](https://poser.pugx.org/jonnitto/textwithpicture/downloads)](https://packagist.org/packages/jonnitto/textwithpicture)
[![License](https://poser.pugx.org/jonnitto/textwithpicture/license)](https://packagist.org/packages/jonnitto/textwithpicture)

With this package you add a `<picture>` NodeType with text into [Neos CMS](https://www.neos.io).  
Contributions are very welcome!

Lightbox support
----------------

If you want to add lightbox support you can set the super types on the `Picture` node type:

```
'Jonnitto.TextWithPicture:TextWithPicture':
  superTypes:
    'Jonnitto.Picture:Lightbox': true
    'Jonnitto.Picture:Caption': true
```

After that, you can install [Jonnitto.PhotoSwipe](https://github.com/jonnitto/Jonnitto.PhotoSwipe) via composer: `composer require jonnitto/photoswipe`  
Et voilà: You've just included [PhotoSwipe](http://photoswipe.com/)


License
-------

Licensed under MIT, see [LICENSE](LICENSE)
