# Tópicos Avançados em Engenharia de Software e Sistema de Informção

## Atividade 1 | Tópicos Avançados 2026-1 | Equipe JUD 4 | KAIO - 202611006147

Eu faço parte da Equipe 4 (Domínio Jurídico) e fiquei responsável por:

Questões abertas: 83 a 94

Questões de múltipla escolha: 862 a 984

### Links da atividade

Github: https://github.com/kaioc89/Topicos_Avancados_2026-1_Equipe_JUD_4_atividade1_Kaio

Youtube: https://www.youtube.com/watch?v=qAP6T9f4UmA (OBs.: O gravador finalizou aos 15 minutos e cortou o vídeo, mas já estava apenas encerrando a apresentação)

Relatório: https://drive.google.com/file/d/1DKxi_FWVIGwCGN1yHxJZAx64YCSY7UCW/view?usp=sharing

### Tutorial para reproduzir o experimento
Acessar o arquivo **Atividade1.ipynb**

#### Para preparar o ambiente
- Executar comandos em:
    Instalação de dependências
    Inicialização

#### Para executar as questões objetivas
- Executar comandos em:
    Carregar avaliação
    Interface de Avaliação -> Definir modelo, quantização e questões


#### Para executar as questões abertas
- Executar comandos em:
    Carregar questões e guidelines
    Carregar avaliação
    Interface de Avaliação -> Definir modelo, quantização e questões


#### Descrição dos Arquivos

- **Atividade1.ipynb**: Notebook contendo o código e análises realizadas na atividade.
- **curadorias.csv**: Arquivo com os resultados da curadoria das questões.
- **oab_guidelines.jsonl**: Arquivo contendo as diretrizes da OAB em formato JSON Lines.
- **oab_questions.jsonl**: Arquivo com as questões da OAB em formato JSON Lines.
- **resultados/**: Diretório contendo os resultados das análises realizadas.
  - **abertas/**: Resultados das questões abertas.
    - Exemplos:
      - `relatorio_final_google_gemma_2_2b_it.json`: Relatório final gerado pelo modelo Google Gemma 2.2B.
      - `relatorio_final_meta_llama_Llama_3.2_3B_Instruct.json`: Relatório final gerado pelo modelo Meta LLaMA 3.2B.
      - `relatorio_final_Qwen_Qwen2.5_3B_Instruct.json`: Relatório final gerado pelo modelo Qwen 2.5B.
      - **v_bertimbau_unicamp_ptt5/**: Subdiretório com relatórios adicionais gerados pelo modelo BERTimbau Unicamp PTT5.
  - **objetivas/**: Resultados das questões de múltipla escolha.
    - Exemplos:
      - `gemma2_2b_it_results.json`: Resultados gerados pelo modelo Gemma 2.2B.
      - `llama3_2_3B_results.json`: Resultados gerados pelo modelo LLaMA 3.2B.
      - `Qwen_Qwen2.5_3B_Instruct_results.json`: Resultados gerados pelo modelo Qwen 2.5B.

### Observações

- Certifique-se de que os arquivos estão devidamente organizados para facilitar a navegação e análise.
- Para mais informações sobre os modelos utilizados, consulte os relatórios disponíveis na pasta `resultados/`.
