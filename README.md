# MindSense

Aplicação web que analisa sentimentos em textos usando o modelo LLaMA 3.3 da Groq API.

## O que faz

O MindSense recebe um texto escrito pelo utilizador e devolve (no idioma que recebeu o texto):
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

## Modo de demonstração

Por defeito, o MindSense funciona em **modo de demonstração** com respostas simuladas,suporte para dois idiomas(EN\PT) sem necessidade de chave API. Este modo é útil para testar a aplicação sem configuração adicional.

### Para usar a API real (opcional)

1. Obtenha uma chave gratuita em [console.groq.com](https://console.groq.com).
2. Crie um ficheiro `js/config.js` com o conteúdo:
   ```javascript
   const GROQ_KEY = 'gsk_aqui_a_sua_chave';
   
## Estrutura do projeto
mindsense/
├── index.html 
├── css/
│ └── style.css 
├── js/
│ └── script.js 
└── assets/
└── images/ 

## Demonstração

O projeto está disponível em:  
[https://adel13073.github.io/Mindsense](https://adel13073.github.io/Mindsense)


## Créditos
Projeto desenvolvido por Adelmária George no âmbito da cadeira de Sistemas Inteligentes da Universidade Óscar Ribas.



Projeto desenvolvido no âmbito da cadeira de Sistemas Inteligentes da Universidade Óscar Ribas.
