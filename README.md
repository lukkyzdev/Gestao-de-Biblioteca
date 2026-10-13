# <img align="center" alt="Python" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"> Gestão de Biblioteca | Python OOP & Data Visualization

Um sistema de gestão de acervo literário desenvolvido em Python. O projeto funciona como um mini-CRUD (Create, Read, Update, Delete) operando em memória, unindo os fundamentos de **Programação Orientada a Objetos (POO)** com a **Visualização de Dados**.

## 🎯 Objetivo do Projeto
O desenvolvimento deste sistema teve como foco a criação de uma arquitetura de código limpa e modular. O objetivo foi validar a capacidade de estruturar dados complexos através de objetos e, em seguida, extrair métricas visuais desses mesmos dados.
- Consolidação dos pilares de Orientação a Objetos em Python (Classes, Instâncias e Atributos).
- Implementação de algoritmos de busca e listagem iterativa sobre coleções de dados (Listas).
- Integração de bibliotecas externas para geração de relatórios visuais baseados no estado da aplicação.

## 💻 Tecnologias e Arquitetura Aplicada
- **Python (Core):** Linguagem base utilizada para a lógica de negócio.
- **POO (Modelagem):** Criação da classe `Livro` para encapsular a estrutura de dados (Título, Autor, Gênero, Quantidade).
- **Matplotlib:** Biblioteca de visualização gráfica importada para processar a distribuição do acervo e renderizar gráficos analíticos.

## 🚀 Como Funciona a Lógica
A aplicação é gerida através de funções específicas que manipulam a base de dados (uma Lista em memória que atua como a "estante" da biblioteca):
1. **Cadastro e Ingestão:** A função `cadastrar_livro()` instancia novos objetos da classe `Livro` e anexa-os à lista principal.
2. **Consultas (Read & Search):** Funções dedicadas para varrer a lista e exibir o acervo completo (`listar_livros()`) ou isolar um registo específico através de validação de Strings (`buscar_livro()`).
3. **Geração de Insights (Gráficos):** A função `gerar_grafico()` contabiliza a frequência de cada categoria (Gênero) dentro da lista de objetos e utiliza o Matplotlib para plotar um gráfico de barras, oferecendo uma visão imediata da distribuição do acervo.

## 📊 Execução e Demonstração Visual

Abaixo, é possível visualizar o resultado da execução do script, apresentando as listagens no terminal de comandos e a renderização do gráfico de distribuição:

> **Painel de Execução e Gráfico de Acervo:**
> 
> ![Código em Execução](./images/resultado.png)

> **Estrutura de Classes e Lógica do Código:**
> 
> ![Código 1](./images/code1.png)
> ![Código 1.1](./images/code1.1.png)

## 📂 Acesso ao Código Fonte
Toda a modelagem da classe, funções de gestão e rotinas de plotagem podem ser analisadas no ficheiro principal:
- [📄 SistemaSimplesDeGerenciamentoDeLivrosEmUmaBiblioteca.py](https://github.com/lukkyzdev/SistemaSimplesDeGerenciamentoDeLivrosEmUmaBiblioteca/blob/main/SistemaSimplesDeGerenciamentoDeLivrosEmUmaBiblioteca.py)

---
*Desenvolvido por Lucas Fontes com foco na aplicação de metodologias orientadas a objetos e análise visual de dados em Python.*
