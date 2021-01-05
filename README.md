PernilleHartmund/Pinch_analysis_applied_on_heat_pump_systems
==================

We present this code based on Engineering Equation Solver ([EES](http://fchartsoftware.com/))
which applies the pinch analysis to a ammonia heat pump system with two, one-stage HP cycles. 
This code is the implementation of the method presented in Jørgensen, P. H., Ommen, Elmegaard, B. Quantification and comparison of COP improvement approaches. Submitted to International Journal of Refrigeration.

This code is hosted [here](https://github.com/PernilleHartmund/Pinch_analysis_applied_on_heat_pump_systems).

How to cite
-----------

Please cite the following publication if you use this code for any work:

Jørgensen, P. H., Ommen, Elmegaard, B. Quantification and comparison of COP improvement approaches. Submitted to International Journal of Refrigeration.


How to install
--------------

To use this code you should open your EES program and paste the code from `source_code.txt`
into the equation window. 
Before running the code the guess values should be imported to the EES program as well. The guess values are found within the file `Guess_Values_source_code.VAR`. A guide to import the file with guess vales can be found here: http://www.fchartsoftware.com/ees/eeshelp/tpq7ri.htm 

Alternatively you can download the ees file `Source_code.EES`  and run it straight away.

How to Use
--------------
The code contains a termodynamic model of a heat pump system with two, one stage heat pumps.
The code can either give the result of a strict serial connection of the heat pumps, or a pinch optimization by running the generic algorithm. Furhter instructions are given as comments in the code. 


License
-------

This code is released under the [BSD-3](https://opensource.org/licenses/BSD-3-Clause), see `LICENSE`.

