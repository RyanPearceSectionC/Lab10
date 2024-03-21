# This is my Lab #10 Assignemnt!
## Hello!
Hello, my name is Ryan Pearce and here is my break down of my Lab #10 progress. It'll simply break down what I did and how I did it.

## Starting Up Bootstrap
This section won't really be all that long as Bootstrap is as simple as going onto [bootstrap](https://getbootstrap.com/)'s website and copying two pieces of code to get the latest bootstrap you can get. So the only thing I had to do now was make a reference to a CSS file and link it. I had to make sure my 'Main.css' file link was _under_ the bootstrap one as for some reason Bootstrap seems to like to replace my .css when I place it above.

Otherwise, I made the semenatics that I usually use (those being header, main and footer) before getting straight to work... which I had to figure out what I was going to do. I didn't want to make another programming on game design one despite how pasionate I was about it because I didn't want to to be stale. So I decided to do something simple and basic yet something I could set up with Bootstrap and I decided on the idea of a website listing the pros and cons of the different seasons of the year.

## Cards
First off, I wanted to try to get cards setup for each season, just a general info sort of thing for each one which had it's fair share of problems. Before I get into that, all I have to explain is that the card has a top image, a title, body of text (which was going to just be a description but was changed in favor of making time different from it) and what was going to be a table that had one side which was pros and another which was cons (which both got replaced by unorganized lists). Whenever I made a card however, they would always end up in a column no matter what I did. I did a bit of researching on bootstrap and found out that you can make divs which will act as rows and columns. I knew columns was a thing but for some reason, a outer universal force was making believe that there was only a 'col' and not a 'row' with g-0. I set up two columns and now they look and work great.

# Information Filling
Well, I had to fill a lot for the cards, I managed to come up with pros and cons while using the time from [this website](https://www.timeanddate.com/calendar/seasons.html) even though Winter's start date was a little strange to me since I consider it as started on late October or early November.

## Gallery
Basically all I did was take a bunch of images of the different seasons, bundle them all up in a gallery and allowed a carousel of all the gallery images for ease.

## Contact Us
This was just as simple as the Gallery, I just had to make a form. Not really much I had to do for that.