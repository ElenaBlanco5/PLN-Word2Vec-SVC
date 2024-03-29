# Processament de llenguatge natural amb Word2Vec i SVM

## Descripció del projecte
La idea general d'aquest projecte consisteix en la creació d'un algoritme que processi frases de text d'una llargada de 13 paraules extretes d'anotacions de la base de dades clíniques d'un hospital oncològic amb l'objectiu de classificar-les en tres classes: 0 (no metàstasi), 1 (no se sap) i 2 (metàstasi).

### Desenvolupat amb:
Aquest projecte ha estat programat en Python 3.7.9.
- [Pandas](https://pandas.pydata.org/)
- [Sklearn](https://scikit-learn.org/stable/)
- [Gensim](https://pypi.org/project/gensim/)

## Sobre la base de dades
Les dades emprades per entrenar els models no seran proporcionades ja que són de domini privat, tot i així es proporcionarà una breu però suficient descripció d'aquestes. La base de dades consta de tres columnes: una correspon a l'identificador del pacient, altra a la frase extreta del seu curs clínic i per últim l'etiqueta de la frase (0, 1 o 2). Múltiples files poden correspondre a diferents frases extretes del curs clínic d'un mateix pacient, en altres paraules, un pacient pot tenir més d'una fila en el conjunt de dades. S'han preprocessat les frases eliminant accents, signes de puntuació i caràcters especials.

## Requeriments
### Prerequisits
- [Python](https://www.python.org/)
- [Conda/Miniconda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

### Instalació
1. Crear un entorn virtual de Python amb Conda, copiant la següent comanda al teu terminal.
```bash
conda create -n myenv python=3.7.9
```

2. Activar-lo i instal·lar els requeriments.
```bash
conda activate myenv
python -m pip install -r requirements.txt
```
