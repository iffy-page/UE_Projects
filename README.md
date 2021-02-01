## Current Projects - UNDIES - Unreal Numerical Data Interpolation ExtensionS

- FloatBacon concept piece decomposes a float variable into a low mantissa float, an int64, and a 53-item byte map of numerator/prime number fractions that comprise internal storage for a fattened up float variable.

    Updates: now commented, with readable function and variable naming! I think that's kinda significant, but keep checking back here and the git logs for more. I'm just spinning my wheels here, too, so feel free to give me your directions!

- Next steps:
    isolated tests on importance of automatic float scaling
    adding parameterization and loop breaks to FloatBacon concept piece, with further vision of a production-ready tool
    calculation optimization paths for write many/read less and for predictable values, for instance caching input values

- Video Updates:

    This is a long silent video totaling 2.5 hours where I go in an add comments to FloatBacon.
    
    https://vimeo.com/505447056  (Part 1)  
    
    https://vimeo.com/505450139  (Part 2)  
    
    https://vimeo.com/507163831 (Part 3)
    
    https://vimeo.com/507191384 (Part 4)
    
    (Part 5 is coming, Vimeo has inexplicably reset my cap once over, so I should be able to upload the end here soon. Only issue now is I don't know how long I have to let VLC stream past -0:00+54:04)
    
    In the end, I forgot you have to add a component to access it, it's fine, I thought I broke something, but let's just ignore that.
    
    https://vimeo.com/507172192 (Annnd, a quick clip just to show, it isn't just a bunch of nodes, it does run, I didn't break it.)
