# BIOMD0000000273: Pokhilko2010_CircClock

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000273.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000273.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000273 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Data assimilation constrains new connections and components in a complex, eukaryotic circadian clock model. **   
Pokhilko A, Hodge SK, Stratford K, Knox K, Edwards KD, Thomson AW, Mizuno T,
Millar AJ. _Mol Syst Biol._2010 Sep 21;6:416.
[20865009](http://www.ncbi.nlm.nih.gov/pubmed/20865009),  
**Abstract:**   
Circadian clocks generate 24-h rhythms that are entrained by the day/night
cycle. Clock circuits include several light inputs and interlocked feedback
loops, with complex dynamics. Multiple biological components can contribute to
each part of the circuit in higher organisms. Mechanistic models with morning,
evening and central feedback loops have provided a heuristic framework for the
clock in plants, but were based on transcriptional control. Here, we model
observed, post-transcriptional and post-translational regulation and constrain
many parameter values based on experimental data. The model's feedback circuit
is revised and now includes PSEUDO-RESPONSE REGULATOR 7 (PRR7) and ZEITLUPE.
The revised model matches data in varying environments and mutants, and gains
robustness to parameter variation. Our results suggest that the activation of
important morning-expressed genes follows their release from a night inhibitor
(NI). Experiments inspired by the new model support the predicted NI function
and show that the PRR5 gene contributes to the NI. The multiple PRR genes of
Arabidopsis uncouple events in the late night from light-driven responses in
the day, increasing the flexibility of rhythmic regulation.


