# MindSense

Aplicação web que analisa sentimentos em textos usando o modelo LLaMA 3.3 da Groq API.

## O que faz

O MindSense recebe um texto escrito pelo utilizador e devolve:
- O sentimento dominante (positivo, negativo, neutro, triste, ansioso, raiva, calmo)
- Uma percentagem de confiança
- Emoções secundárias detectadas
- Um conselho personalizado gerado por IA

A aplicação detecta automaticamente se o texto está em português ou inglês e responde no mesmo idioma.

## Tecnologias

- HTML5 e CSS3 (com suporte a tema claro/escuro)
- JavaScript (ES6+)
- Groq API (modelo LLaMA 3.3 70B)
- Web Speech API (para entrada por voz)

## Como usar

1. Abra o ficheiro `index.html` no navegador
2. Escreva um texto sobre como se sente
3. Clique em enviar ou prima Enter
4. A IA analisa o texto e devolve o resultado

Se preferir, pode usar o microfone para ditar o texto.

## Modo offline

Caso não tenha ligação à Internet ou a chave da API não esteja configurada, o MindSense entra em modo de demonstração e devolve respostas baseadas em palavras-chave.

## Estrutura do projeto
