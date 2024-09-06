# Engadidos (plugins) cos dicionarios de galego

Para construir os ficheiros comunidade, desde o proxecto hunspell 
empregouse a orde:

```
$ scons aff=norma,trasno,unidades dic=comunidade,rag,norma,trasno,unidades,uvigo,wikipedia,wiktionary rep=comunidade,rag,wikipedia
```

Para construir a versión volga (=DRAG):
```
$ scons dic=norma,rag/gl/abreviaturas,rag/gl/correcto
```

Os cartafoles da versión thunderbird e firefox son iguais, cambia o 
manifiest.

