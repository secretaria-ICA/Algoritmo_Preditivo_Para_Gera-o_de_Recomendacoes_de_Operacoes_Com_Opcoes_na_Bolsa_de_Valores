# Algoritmo Preditivo Para Geração de Recomendações de Operações com Opções na Bolsa de Valores Mobiliários

#### Aluno: [Anderson da Silva Nascimento - Mat: 192.671.149](https://github.com/diqeliba)
#### Aluno: [Adriana Costa e Silva - Mat: 192.671.006](https://github.com/Drica3d)
#### Aluno: [Douglas Leandro Dias Brandão - Mat: 192.671.042](https://github.com/dougbrandao)
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

O objetivo do trabalho foi desenvolver um algoritmo gerador de recomendações de operação com "Opções" na bolsa de valores. Especificamente trabalhamos com "Venda de PUTS (Opções de Venda)".

As PUTS "são instrumentos que conferem a seus titulares o direito de vender um ativo em uma data futura, por um preço predeterminado (strike)". Podem ser usados pelo comprador como instrumentos de proteção, já que garantem o direito de vender o ativo por um preço pré-determinado (strike da Opção). Dessa forma, há proteção para eventuais quedas nos preços. 

Além disso, as PUTS podem ser usadas como forma de gerar renda. Ao vender PUTs, o vendedor se compromete a comprar um ativo a um determinado preço. Porém, em troca, ele recebe um valor imediato como prêmio. Caso o preço do ativo não caia, ele não será executado e o vendedor ficará com o valor do prêmio.

Nesse projeto foi utilizada a estratégia de geração de renda, objetivando encontrar pontos em que seja improvável uma queda no preço do ativo. Dessa maneira, torna-se possível vender PUTS sem ser exercido, monetizando com os valores dos prêmios das vendas das PUTS.

Utilizamos uma base histórica dos preços da ação EGIE3 (ação com fundamentos interessantes e boa pagadora de dividendos). Os melhores resultados preditivos foram alcançados utilizando algoritimos "Randon Forest", com parâmetros otimizados com "RandomSearch" e "GridSearch".

### Abstract <!-- Opcional! Caso não aplicável, remover esta seção -->

<!-- trocar o texto abaixo pelo resumo do trabalho, em inglês -->

The objective of this work was to develop an algorithm that generates recommendations for trading with "Stock Options". Specifically we work with PUTS (Selling Options).

"PUTS are instruments that grant their holders the right to sell an asset at a future date, for a predetermined price (strike)". They can be used by the buyer as protection instruments, as they guarantee the right to sell the asset for a predetermined price (Option strike). In this way, there is protection against any price drops.

Furthermore, PUTS can be used as a way to generate income. When selling PUTs, the seller agrees to buy an asset at a certain price. However, in return, he receives immediate value as a prize. If the price of the asset does not fall, the "seller" will not be executed and he will keep the premium amount.

In this project, the "income generation strategy" was used, aiming to find points where it´s most unlikely a considerable drop in prices. In this way, it becomes possible to sell PUTS, receive a value as a prize, and probably not have to buy the asset.

We used a historical basis of EGIE3 stock prices (stock with interesting fundamentals and good dividend payer). The best predictive results were achieved using "Randon Forest" algorithms, with parameters optimized with "RandomSearch" and "GridSearch".

---

Matrícula:

- Anderson da Silva Nascimento - 192.671.149
- Adriana Costa e Silva - 192.671.006
- Douglas Leandro Dias Brandão - 192.671.042

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
