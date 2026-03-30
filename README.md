# Operação Global Exchange - Lista 05

## Descrição do Projeto
Este projeto apresenta um sistema de conversão de moedas em C#, desenvolvido no terminal com foco em IHC, UX e robustez.

O programa recebe um valor em reais, solicita a cotação do dólar e exibe o valor convertido de forma clara e organizada.

---

## Heurísticas Aplicadas

### 1. Visibilidade do Status do Sistema
O sistema informa ao usuário o que está acontecendo durante o processamento com as mensagens:

- Conectando ao Banco Central...
- Calculando taxas...

Isso evita a sensação de travamento e melhora a experiência do usuário.

### 2. Prevenção de Erros
Foi utilizado `try/catch` para tratar entradas inválidas.
Se o usuário digitar algo incorreto, o sistema exibe uma mensagem de erro amigável em vez de quebrar.

### 3. Estética e Design Minimalista
O sistema utiliza:
- título formatado
- separadores visuais
- cores no terminal
- resultado destacado

Esses elementos deixam a interface mais agradável e fácil de entender.

---

## Estrutura do Repositório

- `ConversorExpert/` → código-fonte do projeto
- `evidencia-final.png` → print do sistema funcionando
- `README.md` → documentação do projeto

---

## Reflexão de Encerramento

Após passar por essas 4 missões, minha visão sobre “apenas escrever código” mudou bastante. Eu percebi que não basta fazer o programa funcionar. Também é importante pensar em como o usuário vai entender, usar e reagir ao sistema. Mensagens claras, prevenção de erros e um visual mais organizado fazem muita diferença na experiência. Programar não é só lógica, mas também criar algo que seja fácil, seguro e agradável para quem usa.
