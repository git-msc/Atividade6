# Atividade6

## Branch dev

16. Exclusão do arquivo2.js
17. Criação do arquivo4.js
18. Inserção da linha abaixo no arquivo4.js:
```JavaScript
console.log("commit três")
```
19. Remoção do arquivo2.js na branch dev (`git rm arquivo2.js`)
20. Adição do arquivo4.js na branch dev (`git add arquivo4.js`)
21. Realização do terceiro commit na brench dev (`git commit -m "três"`) 
22. Adição da linha abaixo no arquivo1.js
```JavaScript
console.log("commit quatro")
```
23. Adição do arqivo1.js na branch dev (`git add arquivo1.js`)
24. Realização do quarto commit na brench dev (`git commit -m "quatro"`)
25. Realização de push no GitHub na origin dev (`git push origin dev`)
26. Criação da brench temp (`git brench temp`)
27. Saída da brench dev e entrada a brench temp (`git checkout temp`)

>***Passos 28 a 36 na brench temp***

37. Merge das brenches temp e dev (`git merge dev temp`)
38. Realização de push no GitHub na origin dev (`git push origin dev`)
39. Exclusão do arquivo4.js
40. Alteração da primeira linha do arquivo1.js 

De: 
```JavaScript
console.log("commit um")
``` 
Para:
```JavaScript 
console.log("commit um_alterado para commit seis")
```
41. Remoção do arquivo4.js na brench dev (`git rm arquivo4.js`)
42. Adição do arquivo1.js na brench dev (`git add arquivo1.js`)
43. Realização do sexto commit na brench dev (`git commit -m "seis")
44. Saída da brench dev e entrada na brench main
