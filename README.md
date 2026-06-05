# 🪐 Mission Control AI — Operação Ares-V

## 🚀 Equipe de Engenharia Aeroespacial
* **Pedro Soares de Souza** — RM: 571285
* **Paulo Henrique Lira Bilac de Araujo** — RM: 569496
* **Olavo Dadario Vianna Barreto** — RM: 569272

═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═

## 🛰️ Sobre o Projeto
Este repositório contém a solução desenvolvida para o **Global Solution 2026.1**, focada na disciplina de *Prompt and Artificial Intelligence*. O objetivo principal é consolidar um ecossistema inteligente de monitoramento e telemetria focado no gerenciamento de uma missão espacial experimental de suporte à vida.

A arquitetura do software foi totalmente desenvolvida em Python para rodar no ecossistema do **Google Colab**, segmentada em duas camadas de controle:

* **Matriz de Decisão Autônoma (Hardware):** Lógica computacional em loop que processa os sensores físicos em tempo real, disparando diretrizes automáticas de segurança imediata ao detectar anomalias.
* **Núcleo de Inteligência Cibernética (IA Generativa):** Integração com o modelo de linguagem **Llama 3.2 (1B)** rodando localmente via **Ollama**. A IA atua como um consultor especialista de bordo (CyberIA), interpretando os dados operacionais agregados para gerar pareceres técnicos detalhados e preditivos.

═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═

## 📊 Demonstração dos Ciclos Operacionais
O sistema simula o comportamento da espaçonave através de janelas temporais dinâmicas (ciclos de varredura), demonstrando a adaptabilidade e a resposta dos algoritmos perante flutuações e falhas físicas.

### 🟢 Ciclo 01 — Estado Nominal / Operação Segura
Neste estágio inicial, todos os sistemas operam sob condições regulamentares ideais. A automação permanece em modo de monitoramento preventivo e a CyberIA reporta estabilidade absoluta na nave.

![Ciclo 1](assets/Ciclo%201%20-%20Nível%20estável.png)

### 🟡 Ciclo 02 — Alerta de Descompressão e Suporte Crítico
Simulação de anomalia por vazamento de pressão interna e queda severa de oxigênio disponível nos módulos. O sistema de hardware dispara os protocolos de isolamento pneumático e a IA emite um diagnóstico imediato de risco biológico.

![Ciclo 2](assets/Ciclo%202%20-%20Nível%20moderado.png)

### 🔴 Ciclo 03 — Crise por Radiação Cósmica Elevada
Cenário crítico gerado por uma tempestade solar geomagnética de forte impacto. Os sensores detectam picos severos de radiação de fundo, provocando o acionamento emergencial automático dos defletores de plasma (escudos em força máxima), enquanto a IA orienta procedimentos de proteção biológica.

![Ciclo 3](assets/Ciclo%203%20-%20Nível%20elevado.png)

═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═

## 🛠️ Pilha Tecnológica
* **Linguagem Base:** Python 3 (Scripts de automação, lógica de hardware e controle terminal)
* **Motor de IA Local:** Ollama e Llama 3.2 1B (Processamento de linguagem natural e inferência sintática)
* **Ambiente de Desenvolvimento:** Google Colab (Servidor de computação unificado na nuvem)

═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═

## ⚙️ Instruções de Execução

O ecossistema foi projetado para rodar de forma 100% abstrata e automatizada na nuvem, eliminando a necessidade de qualquer configuração manual no hardware local.

1. Ative o ambiente de simulação clicando no link oficial do projeto:
   👉 [Acessar Notebook no Google Colab](https://colab.research.google.com/drive/1_eo7Fq87CIzqbr_XEbFKoHgJX9TGY3l-?usp=sharing)
2. Certifique-se de conectar a uma instância de execução ativa fornecida pelo Google.
3. No menu superior da interface, navegue até **Ambiente de Execução** e selecione a opção **Executar tudo** (`Ctrl + F9`).
4. O script instalará silenciosamente as dependências, injetará o pacote `zstd` necessário para a extração do Ollama, fará o download da engine de IA e exibirá o painel em tempo real.

═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═\═

## 🎬 Apresentação Técnica em Vídeo
O vídeo de defesa conceitual e demonstração prática do projeto possui menos de 3 minutos de duração. O material apresenta os integrantes da equipe, a justificativa da arquitetura montada e o sistema respondendo e processando os ciclos ao vivo:

👉 [**Assistir ao Vídeo de Demonstração — Operação Ares-V**](https://link-do-video.com)
