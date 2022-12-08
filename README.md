# Machine Learning: lidando com dados de muuitas dimensões

Neste curso, vamos:

- Aprenda o que são dados de alta dimensionalidade;
- Crie um modelo de Machine Learning para classificação;
- Construa uma matriz de correlação com Pandas e Seaborn;
- Aprenda como selecionar feature com visualizações dos dados;
- Utilize o Scikit-learn para criar modelos de seleção de feature automáticos;
- Aprenda a utilizar técnicas de redução de dimensionalidade (PCA e T-SNE).

## Dataset

A base de dados utilizada durante o curso é da plataforma Kaggle e pode ser
encontrada neste link:

- [Exames](https://github.com/alura-cursos/reducao-dimensionalidade/tree/master/data-set)

## Ambiente de desenvolvimento

1. Criar e ativar o ambiente virtual.

   - É muito importante que o ambiente virtual seja salvo em uma pasta com um nome DIFERENTE de .env. Uma sugestão é .venv.

    ```shell
    conda create -p .venv python=3.9.7
    ```

    - Ativando o ambiente virtual.

    ```shell
    conda activate ../.venv
    ```

2. Ativando o terminal python.

    ```shell
    python
    ```

Pronto! o ambiente está pronto!!!

## Requerimentos extras

- Instalar pacotes no projeto
  - Basta colocar no arquivo 'requeriments.txt' o nome do pacote quer instalar

    ```python
    pip install -r requirements.txt
    ```