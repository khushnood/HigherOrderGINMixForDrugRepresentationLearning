Title: "Advancing Drug Discovery with Graph Neural Networks: Drug-target representation learning"
This is to reporduced results specially classification based
### Dependency

```
python        3.7.1
torch         1.13.1
numpy         1.18.5
scipy         1.7.3
torch_sparse  0.6.17
pandas        1.3.2
scikit-learn  1.0.2
pandas-flavor 0.6.0
subword-nmt   0.3.8
prettytable   3.7.0
texttable     1.7.0
tqdm          4.66.2
pytdc         0.4.1
loguru        0.7.2
matplotlib    3.5.2
requests      2.27.1
lifelines	  0.27.8
```

pip install subword-nmt==0.3.8 texttable==1.7.0 pytdc==0.4.1 loguru==0.7.2 lifelines

### Dataset

**Davis** Dataset can be found in http://staff.cs.utu.fi/~aatapa/data/DrugTarget/.

To reporuce the results unzip the folder and run:
```
python src/main.py
```
