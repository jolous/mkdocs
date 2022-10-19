
<!--- 

[atmosfera website](https://atmosfera.usm.my/)

**Bold Text** 

> following points:
- list
- list

{--deleted--}
{++added++}
{~~one~>a single~~}
{==Highlighting==}
{>>and comments can be added inline<<}
---> 
## **Installing Anaconda**

Click on link below to download and install Anaconda Distribution.

[Download Anaconda](https://www.anaconda.com/products/distribution){target=_blank}

After installation open your terminal. 

## **Create New Environment**

Create and activate a new environment.

    conda create --name MkDocs
    conda activate MkDocs

## **Install Packages**

    conda install -c conda-forge mkdocs
    conda install -c conda-forge mkdocstrings
    conda install -c conda-forge mkdocs-material
    conda install -c conda-forge mkdocstrings-python 
    pip install bpython

## **Creating MkDocs Project Structure**

    mkdir MkDocs 
    cd MkDocs 
    mkdocs new .


## **Run MkDocs**

    mkdocs serve

Open a web browser and type `http://127.0.0.1:8000/`

## **Creating Static Pages**

To create static pages you can create an additional `.md` file inside the docs folder and need to be addressed inside the `.yml` file

    touch docs/yml.md

## **Build HTML Documentation**

    mkdocs build


