# CaptchaDataAnalysis
Este repositório é um estudo sobre como reconhecer e analisar imagens de CAPTCHA usando Machine Learning. O objetivo é treinar um modelo para identificar os caracteres presentes nas imagens.
A base de dados utilizada é a CAPTCHA Images do Kaggle, que contém várias imagens de CAPTCHAs com diferentes estilos e distorções.

---

### Descrição da base de dados escolhida
A base **"CAPTCHA Images"** disponibiliza uma coleção de imagens de CAPTCHAs com diferentes estilos e níveis de distorção, representando desafios comuns em sistemas de autenticação.

[Link para a base de dados no Kaggle](https://www.kaggle.com/datasets/fournierp/captcha-images)

---

### Justificativa da escolha da técnica de Machine Learning

Para este projeto, utilizamos a técnica de **classificação**, pois o objetivo é ensinar um modelo a reconhecer os caracteres presentes nos CAPTCHAs.

**Por que classificação?**
- Cada imagem contém uma sequência de letras e números, e o modelo precisa aprender a identificar corretamente quais caracteres estão presentes.
- Como temos um conjunto limitado de possíveis respostas (as letras de A-Z e os números de 0-9), a classificação funciona bem para esse tipo de problema.

Além disso, temos o uso de **Redes Neurais Convolucionais (CNNs)**, elas também são muito utilizadas nesse tipo de tarefa, pois conseguem identificar padrões visuais automaticamente, com formatos das letras e números, mesmo quando há distorções ou ruídos na imagem. 
Isso ajuda o modelo a melhorar a precisão e tornar o reconhecimento de CAPTCHAs mais eficiente.

---

### Explicação breve dos objetivos da análise 

O principal objetivo dessa análise é **ensinar um modelo de Machine Learning a reconhecer os caracteres dos CAPTCHAs**. 

Queremos que, ao receber uma imagem, ele consiga identificar corretamente as letras e números, mesmo que a imagem tenha distorções ou ruídos.
Com isso, podemos entender melhor como os modelos de inteligência artificial lidam com esse tipo de desafio e como eles podem ser usados para automatizar a leitura de CAPTCHAs. Além disso, essa análise pode ajudar a melhorar sistemas de reconhecimento de texto em imagens, o que pode ser útil em diversas áreas, como acessibilidade e segurança digital.
