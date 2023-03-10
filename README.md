# comp20008-workshops

This repository contains the basics of how to store your own workshop content.

---

The step-by-step instructions below will assist you in setting up Jupyter for Visual Studio Code.

Start by cloning this repository to your local machine. You can do this by running the following command in your terminal:

```bash
git clone https://github.com/d4vidsha/comp20008-workshops-demo.git
cd comp20008-workshops-demo
```

It is recommended that you use a virtual environment to install the required libraries. This can be done by running the following commands in your terminal if you're using a Unix-based system:

```bash
python3 -m venv venv
source venv/bin/activate
```

If you're using a Windows-based system:

```bash
python -m venv venv
venv\Scripts\activate
```

If you are not using a virtual environment, you can still follow the steps below.

1. Install required libraries for this subject. You can do this by running the following command in your terminal:

    ```bash
    pip install -r requirements.txt
    ```

2. Install the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) on VSCode.

3. Open the week 1 Jupyter notebook in VSCode by running the following command in your terminal:

    ```bash
    code .
    ```

4. Open the Jupyter notebook by clicking on the `Workshop - Pandas.ipynb` file in the left sidebar.

5. Click on the `Select Kernel` button in the top right corner of the notebook and select the `Python 3` option or the name of your virtual environment.

6. You can now run code cells in the notebook by clicking on the `Run Cell` button in the top right corner of the notebook or by pressing `Shift + Enter`.

7. Enjoy coding!
