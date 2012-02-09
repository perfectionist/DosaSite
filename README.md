# Day 2 #

## Creating a simple webpage using HTML5, CSS and JavaScript ##

This was a simple exercise showing basic HTML coding and a stylesheet.

## Multimarkdown version ##
This same webpage can created using [Multimarkdown Syntax] version 3.5 (see [download page]).  Multimarkdown is a superset of the Markdown syntax and in this case the css file was included by using the `css` meta tag  and the title by using `title` meta tag. Meta tags are at the beginning of the file. The `index1.md` file looks like 

    css:	stylesheets/dosasite.css
    author:	David Loeffler
    title:	Dosa Diner
    
    # ![Restaurant Logo][1]Dosa Diner #
    
    
    ## The Restaurant ##
    The Dosa Diner offers casual lunch and dinner fare in a hip atmosphere. The menu changes regularly to highlight the freshest ingredients.
    
    ## Catering Services ##
    You have fun... we'll do the cooking. Dosa Diner Catering can handle events from snacks for bridge club to elegant corporate fundraisers.
    
    ## Location and Hours ##
    Deccan Corner in Pune, India;
    Monday through Thursday 11am to 9pm, Friday and Saturday, 11am to midnight
    
    [1]: images/dosa.jpg "Restaurant Logo"

I used [Multimarkdown Composer] for composing `index1.md` and [Mou] which is a simpler markdown editor for this page. But you can use any plain text editor if you know the syntax. Exporting to HTML took care of all the HTML tags.  

[Multimarkdown Syntax]: http://fletcherpenney.net/multimarkdown/
[download page]: https://github.com/fletcher/peg-multimarkdown/downloads/
[Multimarkdown Composer]: http://multimarkdown.com/ "Multimarkdown and Markdown editor"
[Mou]: http://mouapp.com/ "Markdown editor"