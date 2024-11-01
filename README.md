# FAIR Chemistry Data

## Research Question

Can we predict the activity of a compound within the human body?

## Data Types

### Essential

* Compound InChI (string) - acts as our unique identifier
* Compound Smiles (string)
* Compound InChI (string)
* List of compound synonyms (and their type) (list of lists containing strings, e.g. [[name 1, research code], [name 2, IUPAC Name]])
* Protein Target (list of lists), where protein target has a unique identifier of a UniProtKB accession, annotations also include protein family, aminmo acid sequences, and species.
* Known binding affinities (IC50, list, same order as in the protein target, could also be a list of lists, e.g. [[target 1, affinity], [target 2, affinity]])

### Additional
* Synonyms (strings), sources
* 2d mol file (string/blob)
* known adverse effects (list)
* Other measured attributes, e.g. Kd (list)
* PAINS annotation(s) (boolean) -- does the molecule contain a functional group known to be "super active", i.e. shows up in assays even if the molecule itself is inactive
* protein target 3D structure(s) (list, same order and PT list)
* protein target associated disease(s) (list)
