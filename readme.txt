Implementations of short-term synaptic plasticity for NEURON.

This archive contains 3 mod files that implement the short term 
synaptic plasticity model described in
  Varela, J.A., Sen, K., Gibson, J., Fost, J., Abbott, L.R., 
  and Nelson, S.B.. 
  A quantitative description of short-term plasticity at 
  excitatory synapses in layer 2/3 of rat primary visual cortex.
  Journal of Neuroscience 17:7926-7940, 1997.

fdsintf.mod is an integrate & fire cell.

fdsexpsn.mod and fdsexp2s.mod are double-exponential 
conductance-change mechanisms based on ExpSyn and Exp2Syn.

NOTES:  

1.  The important parts of this package of files are the 
synaptic mechanisms, not the "cells."  The synaptic mechanisms
are reusable in models of artificial and biophysical neurons.  
The "cells," however, are only the remotest abstractions of a 
V1 layer 2/3 pyramidal neuron.  The "integrate and fire cell" 
is not a specific representation of any particular neuron, 
and the "biophysical neurons" are just single compartments 
that serve as hosts for the conductance change synaptic 
mechanisms.

2.  For information about NEURON's model description language 
NMODL and how to compile mod files see the Documentation 
page at NEURON's WWW site ( http://www.neuron.yale.edu/ ), 
especially the FAQ link on that page.
 
Updated 20110810 by NTC for compatibility with recent versions 
of NEURON.

Contact ted.carnevale@yale.edu if you have questions about 
this implementation of the model described by Varela et al..
