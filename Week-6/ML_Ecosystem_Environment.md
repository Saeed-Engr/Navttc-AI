
# ML Ecosystem & Environment

## Creating a Virtual Environment (Anaconda)

1. **Open Anaconda Prompt**

2. **Create a New Environment**

   ```bash
   conda create --name myenv
   ```

3. **Specify Python Version (Optional)**

   ```bash
   conda create --name myenv python=3.12
   ```

4. **Install Specific Packages (Optional)**

   ```bash
   conda create --name myenv python=3.12 numpy pandas
   ```

5. **Activate the Environment**

   ```bash
   conda activate myenv
   ```

## Managing Virtual Environments

- **List all Environments**

  ```bash
  conda env list
  ```

- **Remove an Environment**

  ```bash
  conda remove --name myenv --all
  ```

---

## Installing ML Packages in Anaconda

### Step 1: Open Anaconda Prompt or Terminal

- On **macOS** or **Linux**, open your terminal.

### Step 2: Activate Your Anaconda Environment

```bash
conda activate myenv
```

### Step 3: Install the ML Package

You can install ML packages using either `conda` or `pip` depending on availability.

#### Using `conda`

```bash
conda install package_name
```

For example, to install `scikit-learn`:

```bash
conda install scikit-learn
```

#### Using `pip`

First, install `pip` if not already installed:

```bash
conda install pip
```

Then use `pip` to install packages:

```bash
pip install package_name
```

Example:

```bash
pip install tensorflow
```

---

### Step 4: Verify the Installation

Open Python and run:

```python
import package_name
```

To verify `scikit-learn`:

```python
import sklearn
print(sklearn.__version__)
```
