## Current Projects - UNDIES - Unreal Numerical Data Interpolation ExtensionS

- FloatBacon concept piece decomposes a float variable into a low mantissa float, an int64, and a 53-item byte map of numerator/prime number fractions that comprise internal storage for a fattened up float variable.


- Next steps:
    isolated tests on importance of automatic float scaling
    adding parameterization and loop breaks to FloatBacon concept piece, with further vison of a production-ready tool
    calculation optimization paths for write many/read less and for predictable values, for instance caching input values
