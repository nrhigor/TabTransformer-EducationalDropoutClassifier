# Análise de Evasão em Cursos de Engenharia Elétrica utilizando TabTransformer
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/nrhigor/TabTransformer-EducationalDropoutClassifier/blob/master/README.en.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/nrhigor/TabTransformer-EducationalDropoutClassifier/blob/master/README.md)

Este repositório contém o código e os dados utilizados no Trabalho de Conclusão de Curso (TCC) de Engenharia Elétrica do CEFET-MG, que investiga a evasão em cursos de Engenharia Elétrica no Brasil por meio de um modelo de aprendizado de máquina baseado no **TabTransformer**.

## Descrição do Projeto

O projeto tem como objetivo classificar instituições de ensino superior (IES) com base nos índices de evasão de alunos. Para isso, foi utilizado o **TabTransformer**, que adapta os mecanismos de atenção do _transformer_ para lidar com dados tabulares.

Os dados utilizados no estudo foram extraídos do Censo da Educação Superior do INEP, abrangendo o período de 2014 a 2023. Com essa abordagem, buscou-se compreender padrões e fatores de risco que influenciam a evasão nos cursos de Engenharia Elétrica, contribuindo para o desenvolvimento de estratégias mais eficazes de retenção estudantil.

## Tecnologias Utilizadas

- **Linguagem**: Python 3.12
- **Bibliotecas Principais**:
  - `pandas` (manipulação de dados)
  - `numpy` (operações matemáticas)
  - `tensorflow` e `keras` (implementação do TabTransformer)
  - `matplotlib` e `seaborn` (visualização de dados)
  - `imbalanced-learn` (balanceamento de classes)
  - `scikit-learn` (métricas de avaliação e clusterização)

## Instalação

Para utilizar este projeto localmente, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/nrhigor/TabTransformer-EducationalDropoutClassifier.git
   cd TabTransformer-EducationalDropoutClassifier
   ```
2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Contato

Autor: **Higor Nunes Resende**  
Orientadores: **Prof. Everthon de Souza Oliveira** e **Prof. Giovani Guimarães Rodrigues**    
Instituição: *Centro Federal de Educação Tecnológica de Minas Gerais (CEFET-MG)*  
Email: [nrhigor@gmail.com](mailto:nrhigor@gmail.com)

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

