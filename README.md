# Sticky & Wicked: a critical introduction to urban data

![sticky_and_wicked](sticky_and_wicked.png)
_This image was generated with the assistance of AI._

## Overview
This repository contains code and documentation for

```
    Class       ARCH 6131 Urban Design Methods / Skills / Tools 1
                The Gensler Family AAP NYC Center
                Fall 2023
                Monday 3:30 PM to 6 PM

    Instructor	Brian Ho
                brian@brian-ho.io
```

All files are organized according to the class modules:

- Measure
- Scale
- Validate

The majority of code is intended to be run in a Google Colab notebook to manage dependencies. This repository also includes some example data, Grasshopper scripts, and Rhino files.

Please cite the author and course when using code in any personal
or professional projects. See `LICENSE` for more information.

## Basic Setup
In order to run the notebooks in this repository you will need to:
1.  [Create a GitHub account](https://github.com/signup). You can use a personal email (and can always add additional emails later). If you already have a GItHub account, you can use that one.

2. [Add Colaboratory](https://workspace.google.com/marketplace/app/colaboratory/1014160490159) to your Cornell Google Workspace account. It's free!

3. Authorize Colaboratory to access GitHub. You can do this by clicking the "Open in Colab" button at the top of any notebook for the first time, and enabling access to GitHub. Please make sure to **check the option to "Access private repositories and organizations".**

## Running Locally
If you want to clone this repository and run it locally, you can do so. This was developed using Python 3.10 on Mac OS. Cloning this repository from GitHub is not in scope for the course and will require setting up `git` a personal access token — reach out if you'd like to try.

1. Set Python to 3.10 — note that `rhino3dm` does not have a build available on PyPi that is compatible with Python 3.11+

2. Create a virtual environment:
    ```
    $ python -m venv venv/
    ```

3. Activate environment:
    ```
    $ source /venv/bin/activate
    ```

3. Install dependencies:
    ```
    $ pip install -r requirements.txt
    ```