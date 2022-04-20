
# DOC2DB

This is the GitHub project to the thesis with the title "DOC2DB: Turning text into relational data structures automatically".

## Abstract

With the exponential growth of textual data available in digital formats, it is becoming increasingly
important to derive insights from these vast quantities of data in an automated way. Accordingly, recent
advances in the field of structured information extraction have proposed a number of approaches for
differently specified task target settings.
In this thesis, we introduce the new target setting of structured, unsupervised information extraction
from topic-focused document collections to relational databases with a given database schema and
investigate two novel approaches to tackle the challenges of performing information extraction without
further constraints on the input data without any dependency to external resources. More specifically, we
focus on the possibilities of canonicalizing results of relation extraction and named entity recognition for
generating deduplicated and related database entries in our first approach as well as on the employment
of canonicalized relation structures for unsupervised entity linking to create foreign key relations in our
adapted second approach. Prior research in the field of information extraction has proposed a vast
number of different approaches that however are often either restricted in the input configuration like
document type, domain or length or in the dependency from external knowledge structures.
Although not providing comparable performance results to other systems, the experiment-driven design
and development of our approaches reveal the potential strengths and weaknesses of each of them and
evaluate them in a qualitative manner using two newly constructed datasets from different domains,
which can build the basis for further research.


## Getting Started

### Dependencies

This notebooks works with Python 3.9 and spaCy versione 3.1.2.

### Installing using requirements.txt

All needed packages are listed in the requirements.txt file.
Create an empty enviroment with Python 3.9 and install all package dependencies using the following command:
```
pip install -r requirements.txt
```

### Installing using enviroment.yml

If you use conda enviroments you can set up the enviroment with all needed packages using the enviroment.yml file:
```
conda env create --file environment.yaml
```

### Working Examples
The code is made available as Jupyter Notebooks. Notebooks in the folder 'Working Examples' are meant to be run directly for trying out different parts of the DOc2DB System. Further Instruction are available in the notebooks themselves.

### Preliminary Experiments
This folder contains the Jupyter notebooks with the preliminary experiments.
To execute these notebooks, download the data from the following [link](https://drive.google.com/file/d/1XDsaEOO8EKBuz-Bsi9qwj_0XFVweMQgH/view?usp=sharing) and place the contents of the zip folder into the folder called "files" in the directory.

### Experiments
This folder contains some experiments that have been performed. The Notebooks are meant for viewing only.

## Help

In case of any issues please contact: s.syed@itces.com

## Authors

Contributors names and contact info

Samar Syed
 s.syed@itces.com
 
 ## Acknowledgments
Libraries
* [Open-IE Python Wrapper](https://github.com/philipperemy/stanford-openie-python)
* [spaCy](https://spacy.io/)
* [Coreferee](https://github.com/msg-systems/coreferee)

