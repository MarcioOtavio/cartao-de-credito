
![Programação-Cartão de crédito - Um projeto em Java](https://github.com/MarcioOtavio/cartao-de-credito/assets/114531896/8bbf10bb-8c79-4df9-8476-53c52778b469)

# Cartão de crédito

App de simulação de um cartão de crédito com um limite de crédito determinado no início do uso e que registra as compras e informa o saldo.

## 🔨 Funcionalidades do projeto

O App simula a transação de compra de um produto recebendo a  descrição e valor. Existe um limite determinado pelo usuário no início da aplicação e a medida que ele realiza essas compras seu limite decresce. Todo armazenamento é mantido em memória do App através de listas e coleção de dados e exposto ao usuário no momento em que ele já não possui mais saldo para realizar compras.

![]![Captura de tela 2024-02-01 205233](https://github.com/MarcioOtavio/cartao-de-credito/assets/114531896/8399fb01-7011-4970-bf12-cd12103be0c1)
ra.gif)

## ✔️ Técnicas e tecnologias utilizadas

Ao aprofundar-me nos conceitos de ArrayList, LinkedList, HashMap e outras estruturas de dados, adquiri não apenas uma compreensão sólida de como utilizá-las em Java, mas também desenvolvi a capacidade de discernir quando aplicá-las de maneira eficaz em cenários específicos. Essa expertise revelou-se especialmente valiosa ao embarcar na construção de um aplicativo que simula um cartão de crédito.

No contexto do desenvolvimento de um aplicativo de simulação de cartão de crédito, a escolha adequada de estruturas de dados é crucial para garantir um desempenho eficiente e uma experiência do usuário otimizada. Utilizando ArrayList, por exemplo, pude gerenciar facilmente uma lista dinâmica de transações, permitindo uma fácil iteração e manipulação dos dados. A flexibilidade oferecida por essa estrutura de dados tornou-se evidente ao lidar com operações de adição, remoção e consulta de transações no histórico do cartão.

A LinkedList, por sua vez, revelou-se útil ao trabalhar com operações que envolvem frequentes inserções e remoções no meio da lista. Dessa forma, consegui otimizar a performance em casos em que a ordem das transações ou a necessidade de atualizações frequentes eram um aspecto crítico para a simulação do histórico do cartão de crédito.

No gerenciamento eficiente de informações associadas a transações, como datas, valores e descrições, a aplicação de HashMaps mostrou-se indispensável. Essa estrutura de dados permitiu-me associar dados específicos a cada transação de maneira rápida e eficaz, proporcionando uma busca eficiente e acesso direto às informações necessárias durante a simulação.

Além disso, a compreensão do momento certo para aplicar essas estruturas de dados foi crucial para otimizar o desempenho do aplicativo. Por exemplo, ao utilizar um ArrayList para armazenar o histórico de transações e um HashMap para gerenciar detalhes específicos de cada transação, consegui equilibrar eficiência e organização de dados.

Em suma, aprofundar-me nas estruturas de dados Java foi instrumental na construção de um aplicativo que simula um cartão de crédito. Essa expertise não apenas simplificou a manipulação de dados, mas também contribuiu para a eficiência e a qualidade da experiência do usuário. A capacidade de aplicar os conhecimentos adquiridos em situações práticas foi um passo significativo na minha jornada como desenvolvedor, mostrando como a escolha adequada de estruturas de dados pode impactar positivamente o desenvolvimento de aplicativos do mundo real.

## 🎯 Desafio

Tela de detalhes do produto

![Captura de tela 2024-02-01 210248](https://github.com/MarcioOtavio/cartao-de-credito/assets/114531896/22cd8417-0cf9-4b43-928c-a939ea096e01)


Você pode [acessar o código fonte do projeto][(https://github.com/MarcioOtavio/cartao-de-credito)]

## 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o Intellij. Para isso, na tela de launcher clique em:

- **Open an Existing Project** (ou alguma opção similar)
- Procure o local onde o projeto está e o selecione (Caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo)
- Por fim clique em OK

O Intellij deve executar algumas tasks do Gradle para configurar o projeto, aguarde até finalizar. Ao finalizar as tasks, você pode executar o App 🏆 

## 📚 Mais informações do curso

Gostou do projeto e quer conhecer mais? Você pode [acessar o curso](https://cursos.alura.com.br/course/java-listas-colecoes-dados) que desenvolve o projeto desde o começo!

