# SEI 2019 CTF Challenge

A website which guides players through a series of pages. Each page provides an obscure hint to what the next page's URL is. The final page has the final answer

Theme: Programming Languages (the theme is secret, players have to figure it out)

Each page is named after the clue from the previous page, and provides the clue for the next one

# Pages:

## Part 1

- first.html (Tutorial): a page stating that the next step is at "second.html"
- second.html: A picture of a Ruby
- ruby.html: The alphabet, with C missing
- c.html: A picture of a pearl
- perl.html:

## Intermission 1:

Grab all the answers, put them on a text file (one per line, no extra whitespace). The link for the 2nd part is given by the keccak256 hash function of that file

## Part 2

- alfjasdfhjasdkfchjasfhfclasfkl.html: a picture of Julia Roberts, but the file has no extension. players have to download it and figure it out
- julia.html: Something like [this](https://www.uberchord.com/wp-content/uploads/2016/11/AdobeStock_98163991-1024x682.jpeg) (but the link to the img tag is hidden somehow. players have to go to the inspector tools)
- fsharp.html: A picture of a snake (but players have to call a JS function that's declared in the page, which makes the image pop up)
- python.html: A picture of an apple, and some kind of script for a movie or something (but the page redirects to Rick Roll by default. players have to either disable JS, or use curl to see the source)
- applescript.html: A picture of a condom (but the image only shows if the useragent is the brave browser)
- latex.html: A GIF of an assembly line at a factory (ou a Fronha do Proença)
- assembly.html: [This](https://as2.ftcdn.net/jpg/00/52/32/83/500_F_52328328_G8EfhNeW1h4fXLNnYccCUWjKG16EUopb.jpg) picture (but we show the base64 encoding instead of the actual image)

## Intermission 2:

TODO

## Part 3

- brainfuck.html: Some obscure picture from Puppet Master (the movie, or the HoN character)
- puppet.html: A picture of Gordon Ramsay (could be just his voice instead)
- chef.html: The text "!true"
- false.html: Some excerpt by a shakespear poem
- shakespeare.html: A gif of water turning into ice
- solidity.html: A picture of a black hole
- singularity.html: You won
- 

Send the full list of answers in a text file to @naps62 somehow (he's online, you'll figure it out)
