### Inline-style links

This is an [example link](http://example.com/).  
This is an [example link](http://example.com/ "With a Title").


### Reference-style links

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"


The implicit link name shortcut allows you to omit the name of the link, in which case the link text itself is used as the name.  
Just use an empty set of square brackets — e.g., to link the word “Google” to the google.com web site, you could simply write:

[Google][]

And then define the link:

[Google]: http://google.com/


Markdown supports a shortcut style for creating “automatic” links for URLs and email addresses: simply surround the URL or email address with angle brackets.  
What this means is that if you want to show the actual text of a URL or email address, and also have it be a clickable link, you can do this:

<http://example.com/>
