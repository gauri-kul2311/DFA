# DFA
Problem Statement :
Hard code a DFA, display the DFA using graphics library and show if the input string will be accepted by the DFA.

Requirements :
The project is Python3 only, tested on Python 3.5 and 3.6.

Installation :

From PyPi using pip:
pip install pysimpleautomata

From source:
python setup.py install
pip install -r requirements.txt


IO is managed by PySimpleAutomata.automata_IO module:
from PySimpleAutomata import automata_IO

DOT and JSON file are supported for input and output. AFW use only JSON because alternate automata doesn’t have a “natural” graph representation.
DOT is a plain text graph description language. This format is recommend for DFAs and NFAs because permits to have natively both a graphical representation and an easy to read plain-text.


