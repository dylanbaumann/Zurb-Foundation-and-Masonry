ZurbFoundationMasonry
=====================

This is a super rudimentary example of implementing Zurb's Foundation 5 (most recent at publish date) with jQuery Masonry.

Unfortunately since masonry is being used we must ignore the resizing of images for a hard-px based measurement. This is set up similarly where as the container shrinks in size the images will not resize but the columns will rearrange to accomidate, the new container will then center itself accordingly to avoid ugly margin issues on the right side of a column where images are missing. This is the best solution for integrating a masonry into a responsive framework (see pinterest site).

Applying the masonry call onto a 'large-12' container within foundation has the same effect though, it will automatically choose the first image as the base-width of a psuedo column when creating columns to fit inside of the container. More information about specifics can be found on the jQuery masonry website, http://masonry.desandro.com/.

I claim no ownership to any of the contained files since it is a simple integration of two existing elements, Zurb's Foundation and jQuery Masonry.
