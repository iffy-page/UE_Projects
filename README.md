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
    
    (Part 3/4 >> converting, check back tonight Jan 27 **It converted and uploaded, I just have to wait for the week on Vimeo to turn over.**)
    
    (In the end, I forgot you have to add it component to access it, it's fine, I thought I broke something, but let's just ignore that.)
    
      
    (Annnd, a quick clip just to show, it isn't just a bunch of nodes, it does run.)
