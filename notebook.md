# Fungi vesicles project

Collaboration with Quimi Vidaurre Montoya, Ricardo Kriebel

# Data

Quimi shared as a google drive `Claudia_data.rar`, which I unrar in my laptop:
```shell
brew install unrar
unrar x Claudia_data.rar
```
and then uploaded to a google shared drive.


## Meeting with Quimi (5/13) to discuss data
- not all leaves in images, only highlighted in tree PDF
- leaf names match folders with images
- long stem = conidiophores with one or multiple vesicles
- Interest in different vesicule shapes (I-V in PDF `Escovopsis_Microscopic-structures.pdf`)
- Some even present a shape like F (in PDF `Escovopsis_Microscopic-structures.pdf`)
- Quimi will redo a divergence times tree with the subset of taxa


# Scripts

From Ricardo: 
- [R Momocs](https://momx.github.io/Momocs/index.html)
- `Escovopsis_vesicle_analysis.Rmd`

# Minutes meeting 5/22
- In paper `2015_Meirelles_Shared_Escovopsisparasites.pdf`, they use a binary trait for ancestral reconstruction: cylindrical/globose
- New info in our analysis:
    - samples from broad geographical distribution
    - co-evolution with ants? not according to estimated divergence times
    - fungi group with information on vesicles => hypothesis: biological pressure to lose the vesicles
    - hypothesis: "esporos" moving from vesicle to conidiophore
- Unlike existing paper:
    - we have a bigger tree (with 5 markers, unlike only one)
    - we do not want to binarize trait

Next steps:
- Claudia: Create dropbox folder with data, send invitation to gmail
- Quimi will put the estimated tree in the folder
- Ricardo+Quimi: Work on drawing the vesicles; Quimi will download and install GIMP