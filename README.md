# Cancer Evolution Simulator

An interactive educational web app showing how mutations, growth rates and
chemotherapy can affect cancer cell populations over time.

**Live demo:** https://tarankaurbansal.github.io/cancer_evolution_simulator/

## What it does
- Simulates an original clone (green) and a mutated clone (blue) with a
  higher growth rate
- Lets you adjust mutation chance, number of generations and chemotherapy
  strength, then shows a live population graph
- Models chemotherapy as a single treatment that removes a proportion of
  both clones

## How it works
The simulation start with an original cancer cell clone and uses a probability of
mutation to introduce a second clone with a higher growth rate. The populations are 
then tracked across generations, with chemotherapy applied at a chosen point to
reduce the number of cells in both clones. The model was first developed in python using
NumPy and Matplotlib before being adapted into an interactive website. 

## Built with
Python (NumPy, Matplotlib), HTML, GitHub Pages

## Notes
This is a simplified educational model, not a realistic model of cancer
growth.

## Authors
Taran Kaur Bansal and Ruchi Raja
