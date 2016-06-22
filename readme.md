###This is the ReadMe

####Assignment: Practice working in teams with Github by working on this "client project" for a local bike shop!

Team: Christian, Gabe, Travis

- Breakdown:
 - Travis is on the Header
 - Christian is on the Main
 - Gabe is on the Footer


- Travis' notes


- Christian's notes
  1. Took a second to make sure the CSS pathway was right and good to sass --watch in the master
  2. then figuring out how to resolve a very strange github merge compability issue became a problem
    - eventually I just had to create a .gitignore that ignored all .css and .map files
  3. when I was ready to start making the desktop version it didn't want to override the previous rules because I didn't realize I had one more level of nesting in the original, which meant one more level of specificity
  4. one image was slightly taller than the other two
    - thus I spent awhile and eventually added a whole extra full-width media query just to make sure the max-width of its parent would make sure that one image didn't keep jutting out below its siblings
    - now it resizes smoothly across all widths
  5.Travis had some issues with pushing to github so I'm just pasting his code into my branch and merging it from there

- Gabe's notes
