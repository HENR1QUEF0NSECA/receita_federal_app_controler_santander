# 📄 Organizador de Imposto de Renda em Excel
Simplifique a organização dos seus documentos e prepare sua declaração do Imposto de Renda de forma rápida, centralizada e sem erros.

## 📖 Sobre o Projeto
A declaração anual do Imposto de Renda da Pessoa Física (IRPF) exige a organização de dezenas de documentos, como informes de rendimentos, notas de corretagem e extratos bancários. Perder-se nesse mar de informações é muito fácil.

Este projeto, desenvolvido como desafio para um bootcamp da DIO, é um aplicativo em Excel criado para ser um centralizador inteligente de informações, auxiliando o contribuinte a organizar todos os dados necessários para a declaração oficial de forma simples e intuitiva.

## ✨ Estrutura e Funcionamento
A ferramenta foi desenhada com uma estrutura modular e navegação facilitada, imitando a experiência de um aplicativo, com botões que levam o usuário para cada seção específica.

O fluxo de trabalho é organizado da seguinte forma:

### 📄 TITULAR

É a tela inicial, onde o contribuinte insere seus dados pessoais básicos, como nome e CPF. Funciona como a página de identificação do declarante.
#### 🏦 AUX_BANCOS

Uma planilha auxiliar que funciona como um pequeno banco de dados. Ela armazena a lista dos principais bancos e seus respectivos CNPJs. O objetivo é garantir a integridade dos dados e facilitar o preenchimento nas outras abas através de listas suspensas.
### 📝 INFORMES

O coração do sistema. Nesta aba, o usuário lança todos os dados presentes nos Informes de Rendimentos recebidos de fontes pagadoras (empresas, bancos, corretoras). Aqui são registrados os rendimentos tributáveis, isentos e os impostos retidos na fonte.
### 💹 NOTAS

Uma seção dedicada a anotações e registros mais detalhados. É ideal para controlar operações de renda variável, como a compra e venda de ações, onde é preciso registrar informações das notas de corretagem para apuração de ganhos de capital.

## 🛠️ Tecnologias e Recursos Utilizados
Microsoft Excel: Plataforma central de desenvolvimento.
Tabelas Inteligentes: Para garantir que os dados estejam bem estruturados e que as fórmulas sejam dinâmicas.
Validação de Dados: Utilizada para criar listas suspensas a partir da aba AUX_BANCOS, evitando erros de digitação no CNPJ da fonte pagadora.
Fórmulas Avançadas: Uso de funções como PROCV ou PROCVX para buscar informações (como o CNPJ de um banco) e SOMASES para totalizar os rendimentos e impostos que serão usados na declaração final.
Hiperlinks em Formas: Para criar o sistema de navegação intuitivo entre as diferentes abas da planilha.

## 🚀 Como Utilizar
Abra o arquivo receitaapp-DIO.xlsx.
Comece pela aba TITULAR e insira seus dados.
Use os botões de navegação para ir até a aba INFORMES e lance seus rendimentos.
Utilize a aba NOTAS para detalhar operações específicas, se necessário.
Após consolidar tudo, use os totais calculados pela planilha para preencher o programa oficial da Receita Federal com mais segurança e agilidade.

## 👨‍💻 Autor
Feito com dedicação por Henrique Fonseca.
