<div align="center">
  <h1>Wirebond Detection and Analysis</h1>
  <p>This guide will walk you through the steps to set up and run wirebond detection and analysis.</p>
</div>

---

### Step 1: Set Up the Environment
Create and activate the Conda environment using the provided `environment.yml` file.

```
conda env create -f environment.yml
conda activate Wirebond
```

### Step 2: Run Wirebond Detection
Execute the wirebond detection script to process the data.

```
python3 wirebonddetect.py
```

### Step 3: Analyze the Results
After running the detection script, analyze the results using the analysis script.
But change the path to the modules inside `analyze_results.py`

```
base_dir = os.path.join('/home/hgc-qc-web/Wirebond/', 'Modules') #change with your location of Modules
```

Finally run
```
python3 analyze_results.py
```

---
