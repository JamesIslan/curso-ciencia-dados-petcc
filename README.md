# Análise de Dados das Turmas da UFRN (2023-2024)

## Sobre o Projeto

Este repositório contém a análise de dados referente às turmas da Universidade Federal do Rio Grande do Norte (UFRN) para os anos de 2023 e 2024. O objetivo principal é utilizar técnicas de ciência de dados para examinar quase 60.000 registros do portal de dados abertos da instituição, identificando padrões, inconsistências e insights que possam auxiliar na gestão acadêmica e administrativa.

A análise aborda temas como a discrepância na oferta de turmas entre os diferentes campi, a preferência dos alunos por docentes internos, a distribuição de turmas por turno e a sobrecarga de solicitações em determinadas matrículas.

## Tecnologias Utilizadas

* **Python**: Linguagem principal utilizada para a análise.
* **Pandas**: Para manipulação e limpeza dos dados.
* **Matplotlib** e **Seaborn**: Para a visualização dos dados e criação de gráficos.
* **Scikit-learn**: Para a aplicação de algoritmos de clusterização (K-Means).
* **Jupyter Notebook**: Para a apresentação interativa do código e dos resultados.

## Estrutura do Repositório

* `projeto_petcc.ipynb`: O notebook Jupyter contendo todo o código de limpeza, análise e visualização dos dados.
* `/raw_data`: Diretório que armazena os arquivos `.csv` originais com os dados das turmas de cada semestre.
* `relatorio_final.pdf`: O relatório final do projeto, que resume a metodologia, os resultados e as conclusões da análise.

## Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone <url-do-repositorio>
    ```
2.  **Instale as dependências:**
    Certifique-se de ter o Python instalado. Em seguida, instale as bibliotecas necessárias:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn jupyter
    ```
3.  **Execute o Jupyter Notebook:**
    Navegue até o diretório do projeto e inicie o Jupyter:
    ```bash
    jupyter notebook
    ```
4.  **Abra o notebook:**
    No seu navegador, abra o arquivo `projeto_petcc.ipynb` e execute as células de código para ver a análise completa.

## Principais Conclusões

A análise revelou diversos pontos de interesse, entre eles:

* **Assimetria na Oferta:** O Campus Central concentra mais de 85% das turmas, indicando uma grande diferença na oferta de cursos entre a capital e o interior.
* **Preferência por Docentes:** Turmas ministradas por docentes internos (com SIAPE) apresentam uma procura significativamente maior em comparação com as de docentes externos.
* **Demanda por Turno:** Existe uma preferência clara por turmas nos turnos matutino e vespertino, com menor procura pelo noturno.
* **Sobrecarga de Turmas:** Muitas turmas, especialmente as com capacidade para até 150 alunos, recebem um número de solicitações superior ao de vagas ofertadas.

## Como Contribuir

Contribuições são bem-vindas! Se você tiver sugestões para melhorar a análise, adicionar novas visualizações ou corrigir algum problema, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Autor

* **Joamerson Islan Santos Amaral**

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
