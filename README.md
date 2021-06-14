# Atividade6

## Branch dev

18. Exclusão do arquivo2.js
19. Criação do arquivo4.js
20. Inserção da linha abaixo no arquivo4.js:
```JavaScript
console.log("commit três")
```
21. Remoção do arquivo2.js na branch dev (`git rm arquivo2.js`)
22. Adição do arquivo4.js na branch dev (`git add arquivo4.js`)
23. Realização do terceiro commit na brench dev (`git commit -m "três"`) 
24. Adição da linha abaixo no arquivo1.js
```JavaScript
console.log("commit quatro")
```
25. Adição do arqivo1.js na branch dev (`git add arquivo1.js`)
26. Realização do quarto commit na brench dev (`git commit -m "quatro"`)
27. Realização de push no GitHub na origin dev (`git push origin dev`)
28. Criação da brench temp (`git brench temp`)
29. Saída da brench dev e entrada a brench temp (`git checkout temp`)

>***Passos 30 a 38 na brench temp***

39. Merge das brenches temp e dev (`git merge dev temp`)
40. Realização de push no GitHub na origin dev (`git push origin dev`)
41. Exclusão do arquivo4.js
42. Alteração da primeira linha do arquivo1.js 

De: 
```JavaScript
console.log("commit um")
``` 
Para:
```JavaScript 
console.log("commit um_alterado para commit seis")
```
43. Remoção do arquivo4.js na brench dev (`git rm arquivo4.js`)
44. Adição do arquivo1.js na brench dev (`git add arquivo1.js`)
45. Realização do sexto commit na brench dev (`git commit -m "seis")
46. Saída da brench dev e entrada na brench main
