🧮 Calculadora Simples — React JS

## Projeto desenvolvido em React JS para criar uma calculadora simples capaz de realizar operações matemáticas básicas.

_📁 Estrutura do projeto_
src/
├── components/
│   ├── FormCalculadora.jsx
│   └── FormCalculadora.css
├── App.jsx
└── App.css
📌 Desenvolvimento
# 1. Criação da pasta Components

Foi criada a pasta components dentro da pasta src. Ela é utilizada para organizar os componentes do projeto.

# 2. Criação do FormCalculadora.jsx

Dentro de components, foi criado o arquivo FormCalculadora.jsx.

Nesse componente foram adicionados:

Campo para o primeiro número;
Campo para o segundo número;
select para escolher a operação;
Botão Calcular;
Botão Limpar;
Área para exibir o resultado.

Também foi utilizado o useState para armazenar os números, a operação selecionada e o resultado.

# 3. Criação do FormCalculadora.css

Foi criado o arquivo FormCalculadora.css para realizar a estilização do componente.

Foram aplicados estilos em:

Título;
Campos de entrada;
Select;
Botões;
Área de resultado;
Caixa principal da calculadora.
_➗ Operações_

A calculadora realiza quatro operações:

__Símbolo Operação__
+	Adição
-	Subtração
*	Multiplicação
/	Divisão
# 📚 Conceitos utilizados
Componentes React;
useState;
input;
select;
Eventos onChange e onClick;
Funções JavaScript;
switch;
Renderização condicional;
CSS.
🚫 Validações

O sistema verifica se os dois números foram preenchidos e impede a divisão por zero.

🚀 Como executar
npm install
npm run dev

Depois, acesse o endereço disponibilizado pelo Vite no navegador.

👩‍💻 Autora

Isabelli Queiroz

Projeto acadêmico desenvolvido no SENAI.
