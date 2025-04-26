# Sistema de Laudos de Ecocardiograma

Este sistema permite calcular medidas ecocardiográficas, gerar e salvar laudos de ecocardiograma em formato PDF.

## Funcionalidades

- Cálculo automático de medidas ecocardiográficas
- Geração automática de laudos baseados nas medidas e avaliações
- Exportação de laudos em formato PDF
- Interface intuitiva para inserção de dados
- Avaliação das válvulas cardíacas com código de cores

## Como usar

1. Preencha os dados do paciente (nome, data de nascimento, sexo, peso e altura)
2. Insira as medidas ecocardiográficas
3. Clique em "Calcular" para processar os valores
4. Avalie as válvulas cardíacas nas abas correspondentes
5. Clique em "Gerar Laudo" para criar o texto do laudo
6. Utilize o botão "Salvar PDF" para gerar e baixar o laudo em formato PDF
7. Alternativamente, use o botão "Imprimir" para imprimir o laudo

## Geração de PDF

O sistema gera um PDF estruturado contendo:
- Cabeçalho com título
- Dados do paciente
- Conteúdo completo do laudo
- Data do exame
- Paginação para laudos extensos

## Requisitos Técnicos

O sistema utiliza as seguintes tecnologias:
- HTML5, CSS3 e JavaScript
- jsPDF para geração de documentos PDF
- html2canvas para suporte a elementos HTML

## Executando o projeto

Para executar o projeto localmente:

1. Clone o repositório
2. Inicie um servidor HTTP local na pasta do projeto:
   ```
   npx http-server -p 8080
   ```
3. Acesse http://localhost:8080 no navegador

Ou simplesmente abra o arquivo index.html diretamente no navegador. 