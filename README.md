# Atividade6

## Brench main

01. Criação do arquivo1.js
02. Inserção da linha abaixo no arquivo1.js:
```JavaScript 
console.log("commit um")
``` 
03. Criação do arquivo2.js
04. Inserção da linha abaixo no arquivo2.js: 
```JavaScript
console.log("commit um")
```
05. Adição do arquivo1.js na branch main (`git add arquivo1.js`)
06. Adição do arquivo2.js na branch main (`git add arquivo2.js`)
07. Realização do primeiro commit na branch main (`git commit -m "um"`)
08. Criação do arquivo3.js
09. Inserção da linha abaixo no arquivo3.js: 
```JavaScript
console.log("commit dois")
```
10. Adição do arquivo3.js na branch main (`git add arquivo3.js`)
11. Realização do segundo commit na branch main (`git commit -m "dois"`)
12. Criação da tag 1.0 com a mensagem "versão de início" (`git tag -a 1.0 -m "versão de início"`)
13. Realização de push no GitHub na origin main incluindo a tag 1.0 (`git push origin main --tags 1.0`)
14. Criação da brench dev (`git brench dev`)
15. Saída da brench main e entrada na brench dev (`git brench checkout dev`)

>***Passos 16 a 27 na brench dev***

>***Passos 28 a 36 na brench temp***

>***Passos 37 a 44 na brench dev***

45. Merge das brenches dev e main (`brench merge main dev`)
46. Criação da tag 1.1 com a mensagem "versão de entrega" (`git tag -a 1.1 -m "versão de entrega"`)
47. Realização de push no GitHub na origin main incluindo a tag 1.1 (`git push origin main --tags 1.1`)
