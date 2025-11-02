For SBA 3 I chose this frontend mentor challenge: https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7

MY SOLUTION LINKS
Repository link: https://github.com/a-zeb/testimonials-grid-section-main
GitHub Pages link: http://a-zeb.github.io/testimonials-grid-section-main/



APPROACH
As for my approach I chose to use the design mockups and start with the
basic HTML and use bootstrap to create the styling.



CHALLENGES
The hardest part was keeping the tall/right column card aligned with the wider cards that span two columns. 
Bootstrap’s default stacking wanted to collapse or misalign those pieces, so I ended up juggling nested rows, 
helpers, and flexbox utilities to keep every testimonial the same height regardless of content length. 
I also had to tweak spacing repeatedly to prevent orphaned quotation marks at larger breakpoints.



REFLECTION
Matching the staggered testimonial layout strictly with Bootstrap was tougher than I expected. 
Daniel’s and Patrick’s cards both needed to span two columns, while Kira’s had to stay tall and isolated on the right. 
Bootstrap’s default stacking fought that arrangement, and getting the heights to line up meant juggling nested rows and column breakpoints. 
I spent time experimenting with align-items-stretch, wrapping certain cards in additional rows, 
and using flexbox helpers so the cards wouldn’t collapse on smaller screens. If I had more time, 
I’d abstract those inline styles into reusable classes and fine-tune the breakpoints some more. 
I'd also like to make better use of components to make the most of built-in bootstrap functionality.