# 📊 Flamengo Data Analytics - Modo Carreira ⚽

Um painel analítico e interativo de desempenho técnico inspirado na estética de dados, evolução e menus de **EA FC/FIFA**. O projeto monitora as estatísticas e os atributos de 12 jogadores do elenco profissional do Flamengo.

🌐 **Acesse o sistema online aqui:** [COLE O SEU LINK AZUL DO GITHUB PAGES AQUI]

---

## 🚀 Funcionalidades Principais

* **🧬 Perfil de Atributos (Gráfico Radar):** Exibe 5 eixos técnicos de campo (Gols, Assistências, Defesas, Dribles e Velocidade) com fechamento milimétrico e preenchimento dinâmico.
* **📈 Histórico de Desempenho (Gráfico de Linhas):** Linha do tempo monitorando a consistência dos atletas entre os anos de 2022 e 2026.
* **🎛️ Painel de Seleção Rígido:** Botões horizontais altos integrados ao layout que alternam de jogador instantaneamente.
* **🔲 Cards Estáticos Espelhados:** Duas caixas inferiores de tamanho fixo (`310px`) que impedem quebras de layout. Elas exibem a função tática, tempo de vínculo e recordes calculados de campo.
* **🎨 Identidade Visual Sintonizada:** O contorno das caixas e a linha do atributo especial **Geral** mudam de cor em tempo real para herdar a cor neon exclusiva de cada jogador.

---

## 🧠 Lógica e Algoritmos Utilizados (Ciência da Computação)

1. **Cálculo Automatizado do "Overall" (Geral):** O sistema varre a matriz de dados, calcula a média aritmética dos 5 atributos principais e gera uma barra visual adaptativa (`■■■■■□□□□□`) baseada no valor.
2. **Tratamento de Instabilidade de Cache (Plotly Native):** Implementação de isolamento rígido por chaves indexadas individuais (`annotations[2].text`), eliminando congelamentos de tela e o bug crônico do "6º valor" no gráfico polar.
3. **Persistência de Estado Local (F5 Proof):** Injeção automatizada da tag `<title>` e compilação do projeto para uma estrutura estática em HTML puro (`index.html`), permitindo atualizações de página livres de falhas de conexão de porta de rede.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Plotly Graph Objects** (Engine visual matemática)
* **Plotly Subplots** (Grid de renderização simultânea)
* **HTML/CSS Inline** (Formatação interna de texto em monotype e renderização de tabelas)

---

## 📌 Conclusão e Aplicação no Mercado (Sports Analytics)

Este projeto simula um ambiente real de **Scouting e Inteligência de Mercado** utilizado por clubes de alto rendimento. A arquitetura foi desenhada para resolver três pilares do mercado de tecnologia esportiva:

1. **Tomada de Decisão Baseada em Dados:** Centralização de métricas de desempenho (Gols/Assistências) e dados de staff (Tempo de Contrato/Função) em uma única tela, otimizando o planejamento de elenco (Squad Planning).
2. **Engenharia de Interface Avançada:** Uso de técnicas de design responsivo e manipulação de strings via código para garantir que o usuário consuma relatórios complexos de forma visual e intuitiva (Data Storytelling).
3. **Eficiência de Processamento:** Substituição de servidores pesados por uma aplicação estática leve baseada em compilação HTML nativa, reduzindo o custo de infraestrutura e eliminando gargalos de carregamento.

O painel demonstra maturidade em Engenharia de Software ao transformar dados brutos em inteligência visual estável, servindo como uma base sólida para sistemas de monitoramento de atletas em tempo real.

> *"No mundo do futebol moderno, os dados moldam o ego dos craques."* 👁️🔬
