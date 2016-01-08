## `plotmaker` 
This a python/c++ project to make plots from a ROOT tree.


## how to run ? 

### produce a plotcard 
* Produce the plotcard using a processe.json files and input root file. 
* The tree name must be specified

```bash
./makeplotcard.py --load data/100000/output_VBFHToGG_M-125_13TeV_powheg_pythia8_numEvent100000_histos.root\
	          --out plotcard.json\
	          --tree  VBFMVADumper/*VBFDiJet
```
* the `*` will be replaced automatically by the remaining name of the tree found in the `VBFMVADumper` directory.
* This is for the use of [flashgg](https://github.com/cms-analysis/flashgg) type dumper trees only, a more standard version will be pushed soon

### produce a stacked plots
* To run `heepi` plotmaker you have to run the script `plot`
* you can print the options of the script by typing:
```bash


```

* For flashgg users at imperial you can find a plotcard example in the subdirectory configs
* 



