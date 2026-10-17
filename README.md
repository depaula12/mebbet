# MEB BET

Quiz de estudo com tema de cassino para a disciplina MEB-01 do ITA: responda questões com fórmulas, administre sua banca e arrisque parte do ganho na roleta.

**Demo:** https://mebbet.vercel.app

## Como funciona

- Cada partida tem 30 questões em 3 blocos: 10 fáceis, 10 intermediárias e 10 difíceis. O jogador começa com 1000 de banca.
- Cada acerto rende um prêmio (100, 250 ou 600, conforme o bloco) e cada erro desconta um terço dele. Pedir dica custa 25% do prêmio e eliminar uma alternativa custa 40%.
- Sequências de acertos dão um bônus, de até 2x.
- Na roleta, o jogador escolhe um multiplicador no slider e a chance de acerto cai conforme ele sobe (95% ÷ multiplicador, no máximo 95%).
- Há um ranking da sala. A primeira partida de cada jogador é a oficial e o ranking também mostra a melhor. Partidas em andamento podem ser retomadas.

## Stack

- HTML, CSS e JavaScript puros, em um único arquivo (`index.html`), sem etapa de build
- KaTeX para as fórmulas, com CDNs de reserva
- Supabase para perfis, partidas e ranking
- Efeitos sonoros e trilha gerados no navegador (Web Audio API)
- Deploy na Vercel

## Rodando localmente

Abra o `index.html` no navegador ou sirva a pasta com qualquer servidor estático, por exemplo `python -m http.server`.
