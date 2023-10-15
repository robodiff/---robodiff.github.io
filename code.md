## Code

### **Repo:**

[github.com/robodiff/robodiff](https://github.com/robodiff/robodiff)

### **Reproduce our work:**

```
git clone https://github.com/robodiff/robodiff.git
cd robodiff

conda create --name public-robodiff python=3.7.15
conda activate public-robodiff
conda install -c conda-forge libstdcxx-ng=12

pip install -r requirements.txt

python main.py -vv --gui --cpu
```

This will load the first design attempt reported in the paper, and optimize it for 9 gradient descent steps (10 total design attempts).

The first & last design attempts will be visualized to the screen.
