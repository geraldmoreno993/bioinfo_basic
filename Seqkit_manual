# Contar la cantidad de cada aminoacido de un archivo fasta de aminoacidos

```
seqkit fx2tab OR756289.1_proteins.fasta | cut -f2 | tr -d '\n' | fold -w1 | sort | uniq -c
```

# Contar la cantidad total de aminoacidos en el total de secuencias dentro de un archivo fasta de aminoacidos

```
seqkit fx2tab OR756289.1_proteins.fasta | cut -f2 | tr -d '\n' | wc -c
```
