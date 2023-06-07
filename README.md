## Start developing and running this code, you will need to use a virtual environment:

### Use the corresponding git branch:

Switch to the developing branch by typing:

```shell
git checkout develop
```

### Install venv library using:

**For Unix/Mac**

```shell
python3 -m pip install --user virtualenv
```

**For Windows:**

```shell
py -m pip install --user virtualenv
```

### Create the virtual environment by running:

**For Unix/Mac**

```shell
python3 -m venv venv
```

**For Windows:**

```shell
py -m venv venv
```

### Activate the virtual environment by running:

**For Unix/Mac**

```shell
source venv/bin/activate
```

**For Windows:**

```shell
.\venv\Scripts\activate
```

### Now we need to install the required packages:

```shell
pip install -r requirements.txt
```

## Updating Changes

**For updating, it will be necessary to add the corresponding changes by running:**

This will add all changes in the code. For specific changes, specify the file instead of the dot.

```shell
git add .
```

**Next, commit your changes:**

```shell
git commit -m "<description of changes>"
```

**Finally, upload your changes:**

```shell
pacgit push origin develop
```

## Download Changes from github:

```shell
git pull origin
```

** If you want to add new :**
You will need to use a terminal which is active with the virtual environment and use:

```shell
pip install <Packege name>
```

finally update the requirement.txt:

```shell
pip freeze > requirements.txt
```
You can run this code directly from the command line with **"python hhproject.py"**.

You can copy the entire formatted markdown block above.
