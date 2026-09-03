Projeto de Versionamento

A ideia é simples: na branch main existe uma receita original. Cada integrante do grupo cria sua própria branch e modifica essa receita de acordo com seu gosto.

Como funciona

A main possui a receita base (receita_bolo) do projeto.

Cada integrante cria uma branch, por exemplo:

git checkout -b (receita-nome do integrante)

Depois, pode alterar ingredientes, quantidades ou o modo de preparo.

Após as mudanças:

git add .
git commit -m "Alterando a receita ao meu gosto"
git push origin receita-juan
