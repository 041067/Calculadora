# Calculadora de Sistemas Lineares — Regra de Cramer 🧮

# Visão Geral 🧑‍💼
Este repositório contém uma Aplicação Web de Calculadora de Matrizes desenvolvida com HTML, CSS e JavaScript, projetada para resolver sistemas de equações lineares utilizando o Método da Regra de Cramer.
A aplicação foi criada com propósito educacional e didático, integrando conteúdos de Matemática (Álgebra Linear) ao currículo do curso Técnico em Desenvolvimento de Sistemas, sendo utilizada por alunos do 3º ano do Ensino Médio Integrado.

# Contexto Acadêmico 👨‍🏫
A Regra de Cramer é um método direto para encontrar as soluções de sistemas lineares – especialmente útil para sistemas com número de equações igual ao número de incógnitas. A técnica exige o cálculo de determinantes de matrizes quadradas para determinar cada variável do sistema. 

# Este projeto permite que estudantes:
visualizem matrizes de coeficientes e resultados;
calculem determinantes;
manipulem entradas do sistema;
obtenham soluções automáticas via JavaScript.
# Tecnologia Utilizadas 👨‍💻
| Tecnologia               | Finalidade                    |
| ------------------------ | ----------------------------- |
| **HTML5**                | Estrutura da interface        |
| **CSS3**                 | Estilização responsiva        |
| **JavaScript (Vanilla)** | Lógica de cálculo e interação |
O uso de JavaScript puro (sem frameworks) garante compatibilidade ampla e foco no aprendizado dos fundamentos da linguagem.

# Principais Funcionalidades 👨‍💻
✔️ Inserção dinâmica de coeficientes e constantes para sistemas lineares
✔️ Cálculo automático de determinantes e soluções com Regra de Cramer
✔️ Validação de estrutura quadrada da matriz
✔️ Feedback visual de erro para entradas inválidas
✔️ Interface educativa e responsiva para navegadores modernos

# Como Usar ✅
1. Abra a aplicação no navegador (arquivo index.html)
2. Insira os valores da matriz de coeficientes e o vetor de constantes.
3. Clique em “Calcular”.
4. Os resultados serão exibidos dinamicamente.
5. Entrada inválida ou sistema sem solução exibe mensagem de aviso contextualizada.

# Estrutura do Repósitorio 💡
/
├── index.html           # Página principal da calculadora
├── css/
│   └── styles.css       # Estilos e layout da interface
├── js/
│   └── main.js          # Lógica de cálculo da regra de Cramer
├── img/                 # Imagens eg. ícones ou ilustrações
└── README.md            # Documentação técnica

# Detalhes da Implantação 📐
O script principal (main.js) realiza:
1. Leitura de entradas do formulário
2. Construção das matrizes de coeficientes
3. Cálculo de determinantes
4. Substituição das colunas e solução de variáveis
5. Exibição dos resultados com tratamento de erros
Este fluxo segue as etapas matemáticas clássicas da Regra de Cramer.

# Próposito Educacional 👨‍🏫
Este projeto é ideal para:
aulas práticas de programação web básica;
atividades de integração entre lógica computacional e matemática aplicada;
reforço de conceitos como arrays, loops, funções e DOM no JavaScript.
Professores podem reutilizar o código e adaptá-lo para outras técnicas de resolução (por exemplo, eliminação de Gauss ou Decomposição LU).

# Licença 🪪
Este projeto é distribuído sob a licença MIT — livre para uso, cópia e modificação com atribuição adequada.

# Contribuição e Suporte 📞
Contribuições são bem-vindas!
Se quiser sugerir melhorias ou integrar novos métodos numéricos, abra uma issue ou pull request.
