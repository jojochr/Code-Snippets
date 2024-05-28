# Code-Snippets

In this repo ill collect snippets that i use.  
May be overkill since I dont create many of them :D  

Take em if you like.  

# Some Info about Snippets:

There are two unexplained but very practical things in Code-Snippets.  
Namely the two Snippet-Variables $selected$ and $end$.  

They do serve a very neat purpose.  

They are useful if you use "Surround with"-Snippet.  
These Snippets have the special effect that you can highlight code, press STRG + K -> STRG + S to select one of these Surround-Snippets.  
If you do that with the \#region Snippet the selected code will get a \#region before it and a \#endregion behind it.  

This works because in the template for the \#region Snippet the $selected$ Variable represents where the Higlighted contents should go when the snippet is used to surround something.  
And the $end$ Vairable tells Visual Stuidio where your cursor should end up once you end the snippet editing mode.  

Very nice, I didn't know what they were for until I found a Video about it.  