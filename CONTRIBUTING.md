# Como contribuir

## Procedimentos

### Certificações

* Se for adicionar/alterar alguma **certificação**, adicione/altere no arquivo [./certificacoes/README.md](./certificacoes/README.md).

* Deve-se seguir a estrutura:

```
## Sumário

* [Nome da certificação](#nome-da-certificacao)

### Nome da certificacao

Instituição | Valor | Períodos | Lugares | Observações
---- | ----- | ---- | ----- | ------------
Nome da certificação  | <ul><li>**Total:**<li><li>R$ 1.000,00 em 10 x R$ 100,00</li></ul> | <ul><li>**Dias:**</li><li>Segundas e Quartas</li><li>**Horário:**</li><li>19:00 às 22:40</li><li>**Carga Horária:**</li><li>400</li><li>**Meses:**</li><li>18</li></ul> | <ul><li>**Unidade Vila Maria**</li>Rua xpto, 000 – Vila Maria CEP: 0000-001</li></ul> | <ul><li>Local de fácil acesso</li></ul>

```

### Graduações / Pós-graduações e MBAs

* Se for adicionar/alterar alguma **graduação**, adicione na pasta [graduacoes](./graduacoes).

* Se for adicionar/alterar alguma **Pós-graduação ou MBA**, adicione na pasta [pos-graduacoes-mbas](./pos-graduacoes-mbas).

* Deve se manter a estrutura de ano e o arquivo `README.md` dentro do mesmo. Quando não houver o ano corrente, deve-se criar a pasta referente ao mesmo e o arquivo de `README.md`. Exemplo:

```
pos-graduacao-e-mba/2016
pos-graduacao-e-mba/2016/README.md

pos-graduacoes-e-mbas/2017
pos-graduacoes-e-mbas/2017/README.md
...
```

* Novos arquivos de `README.md` devem possuir a estrutura:

```
# Informações referentes ao ano de <Ano>

## Sumário

* [Nome do curso](#nome-do-curso)

### Nome do curso

### Instituições em <Estado - Cidade>

Instituição | Valor | Períodos | Lugares | Observações
---- | ----- | ---- | ----- | ------------
Nome do curso  | <ul><li>**Total:**<li><li>R$ 1.000,00 em 10 x R$ 100,00</li></ul> | <ul><li>**Dias:**</li><li>Segundas e Quartas</li><li>**Horário:**</li><li>19:00 às 22:40</li><li>**Carga Horária:**</li><li>400</li><li>**Meses:**</li><li>18</li></ul> | <ul><li>**Unidade Vila Maria**</li>Rua xpto, 000 – Vila Maria CEP: 0000-001</li></ul> | <ul><li>Local de fácil acesso</li></ul>
```

## Procedimentos de envio

Para enviar a sua contribuição, faça um fork do projeto.

```
git clone https://github.com/carlohcs/certificacao-graduacao-pos-graduacao-mba.git
```

Depois, crie um branch com seu nome de usuário:

```
git checkout -b <seu usuário do Github>
git checkout -b carlohcs # Exemplo
```

Faça sua implementação nesse branch. Quando tiver finalizado, faça um commit com todas as suas alterações e envie para o Github.

```
git add .
git commit -m "Adiciona certificação de..."

git push origin <seu usuário do Github>
git push origin carlohcs # Exemplo
```

Finalmente, faça um pull request no Github, com sua implementação.

### Recomendações

* As mensagens de commits devem ser em pt-BR no modo imperativo. (ex.: Adiciona certificação de PHP...)
* Certifique-se de estar colocando/alterando o conteúdo no arquivo/local correto. **Lembre-se que as graduações estão separadas da pasta de Pós-graduação/MBA**, bem como o as **certificações**.
