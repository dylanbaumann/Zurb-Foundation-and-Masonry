Zurb's Foundation + Masonry
=====================

This is my example of implementing Zurb's Foundation 5 (most recent at publish date) with jQuery Masonry.

Unfortunately, integrating Masonry with Foundation can be tricky since both are attempting to control the image in different ways (Foundation wants to resize and Masonry wants to reposition). The best way to tackle this issue is to use a foundation container as the Masonry container, the images inside will not resize, but will reposition within the fluid container while centering the container to avoid awkward margin issues which appear on the right-side of containers when images cannot be placed into an extra column.

Applying the masonry call onto a 'large-12' container within foundation has the same effect though, it will automatically choose the first image as the base-width of a psuedo column when creating columns to fit inside of the container. More information about specifics can be found on the jQuery masonry website, http://masonry.desandro.com/.

I claim no ownership to any of the contained files since it is a simple integration of two existing elements, Zurb's Foundation and jQuery Masonry.
