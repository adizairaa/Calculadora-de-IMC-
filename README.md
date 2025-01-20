
# ⚖️ *Calculadora de IMC*

Este repositório contém uma aplicação web simples inspirada no video da Larissa kich que calcula o **Índice de Massa Corporal (IMC)** com base no peso e altura fornecidos pelo usuário.

---

## 📄 *Descrição do Problema*

O **IMC** é uma métrica amplamente utilizada para avaliar se uma pessoa está dentro do peso ideal em relação à sua altura. A fórmula usada para o cálculo é:

```
IMC = peso (kg) / altura² (m)
```

### Faixas do IMC:
- **Abaixo de 18,5**: Abaixo do peso.
- **18,5 a 24,9**: Peso ideal.
- **25 a 29,9**: Sobrepeso.
- **30 a 34,9**: Obesidade moderada.
- **35 a 39,9**: Obesidade severa.
- **40 ou mais**: Obesidade mórbida.

### 🧮 *Exemplo de Uso*

O usuário insere os seguintes valores:
- Peso: **70 kg**
- Altura: **1,75 m**

O programa calcula e exibe:
- **IMC**: 22,86
- **Descrição**: "Você está no peso ideal!"

---

## 🚀 *Como Usar a Aplicação*

### *Pré-requisitos*
- Um navegador moderno (como Google Chrome, Firefox ou Edge).
- Conexão com a internet (para carregar fontes e ícones externos).

### *Execução*

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/calculadora-imc.git
   cd calculadora-imc
   ```

2. Abra o arquivo `index.html` no navegador.

3. Insira os valores de **peso** (em kg) e **altura** (em metros).

4. Clique no botão **Calcular**.

5. O resultado será exibido com:
   - O valor do IMC.
   - Uma mensagem indicando a faixa de peso correspondente.

---

## 📚 *Detalhes da Implementação*

1. **Validação de Entrada**:
   - Garante que os valores inseridos para peso e altura sejam positivos e válidos.

2. **Cálculo do IMC**:
   - O cálculo é realizado por meio da fórmula padrão, com o resultado arredondado para 2 casas decimais.

3. **Feedback Visual**:
   - Cores diferenciadas para resultados:
     - **Verde**: Peso ideal.
     - **Vermelho**: Atenção para faixas fora do peso ideal.

4. **Estilo e Responsividade**:
   - Interface simples e amigável, adaptada para desktop.

---

## 📂 *Estrutura do Projeto*

```
📦 calculadora-imc
├── 📁 assets
│   ├── 📁 css
│   │   └── style.css
│   ├── 📁 images
│   │   └── ilustration.svg
├── index.html
├── script.js
└── README.md
```

---

## 📊 *Casos de Teste*

Use os seguintes valores para testar a calculadora:

1. **Peso**: 50 kg, **Altura**: 1,60 m  
   Resultado: **IMC**: 19,53, **Descrição**: "Você está no peso ideal!"

2. **Peso**: 85 kg, **Altura**: 1,75 m  
   Resultado: **IMC**: 27,76, **Descrição**: "Cuidado! Você está com sobrepeso!"

3. **Peso**: 110 kg, **Altura**: 1,70 m  
   Resultado: **IMC**: 38,06, **Descrição**: "Cuidado! Você está com obesidade severa!"

---

## 🛠️ *Ferramentas Utilizadas*

- **HTML5**: Estrutura do conteúdo.
- **CSS3**: Estilo e design responsivo.
- **JavaScript**: Lógica de cálculo e manipulação do DOM.
- **Font Awesome**: Ícones visuais.

---

## 🌟 *Conceitos Praticados*

- **Manipulação do DOM**: Utilizando JavaScript para capturar e exibir os resultados.
- **Validação de Dados**: Garantindo que apenas valores válidos sejam processados.
- **Estilo Responsivo**: Interface simples e adaptável para diferentes resoluções.

---

## 🤝 *Contribuições*

Contribuições são bem-vindas! Caso encontre algum problema ou tenha sugestões, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request**.

