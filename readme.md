`Floating-Point Parameters` - MATLAB Code for Parameters of Floating-Point Arithmetics
==========

About
-----

`float_params` is a MATLAB function for obtaining the parameters of several
floating-point arithmetics.  The parameters are built into the code and are
not computed at run time.

The parameters are

- the unit roundoff,
- the smallest positive (subnormal) floating-point number,
- the smallest positive normalized floating-point number,
- the largest floating-point number,
- the number of binary digits in the significand (including the
         implicit leading bit)

and the arithmetics supported are 

- bfloat16,
- IEEE half precision (fp16),
- IEEE single precision (fp32),
- IEEE double precision (fp64),
- IEEE quadruple precision (fp128).

The code was developed in MATLAB R2018b and works with versions at least
back to R2016b.

License
-------

See `license.txt` for licensing information.

