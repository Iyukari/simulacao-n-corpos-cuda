# UDe acordo com Política de uso de IA generativa

## Ferramentas usadas
Durante o desenvolvimento deste trabalho foram utilizadas ferramentas de IA generativa como apoio ao estudo, escrita e desenvolvimento da aplicação, taiz ferramentas foram

- ChatGPT(OpenAI)
- Gemini(Google
- Kimi AI(geração de slides)
  
## Etapas em que a IA foi utilizada

## 1. Fundamentação teórica

A IA foi utilizada para auxiliar na explicação de conceitos relacionados a:

- computação paralela;
- arquitetura CUDA;
- Taxonomia de Flynn;
- hierarquia de memória em GPUs;
- Leis de Amdahl e Gustafson.

Os textos gerados foram revisados, reorganizados e reescritos pelo trio antes da inserção no artigo.


## 2. Desenvolvimento do código

A IA foi utilizada para:

- esclarecimento sobre kernels CUDA;
- entendimento da utilização de memória compartilhada;
- correção de erros no Google Colab;
- organização da estrutura do código em Python com Numba CUDA.

Todo o código foi estudado e adaptado pelo grupo.

## 3. Geração de gráficos e slides

A IA auxiliou:

- Na organização visual dos slides

## Exemplos de Prompts Utilizados

## Exemplo 1

Prompt:
"Explique como funciona a memória compartilhada (shared memory) em CUDA e como ela pode otimizar aplicações de N-corpos."

Resposta obtida:
A resposta apresentou corretamente o conceito de shared memory e explicou a redução de acessos à memória global.

O que foi aproveitado
- Conceito de memória compartilhada;
- relação entre latência e desempenho.
  
O que foi descartado/corrigido
- Alguns exemplos fornecidos estavam genéricos;
- foi necessário adaptar a explicação especificamente para a simulação de N-corpos.

## Exemplo 2

Prompt:
"Explique por que a implementação GPU Shared pode não apresentar desempenho muito superior à versão GPU Naive em simulações de N-corpos com poucas partículas."

Resposta obtida:
A IA explicou que o uso de memória compartilhada pode não gerar grandes ganhos quando o tamanho da entrada é pequeno, devido ao overhead de sincronização entre threads e ao custo adicional de gerenciamento da shared memory.

O que foi aproveitado
- Explicação sobre overhead de sincronização;
- relação entre tamanho da entrada e eficiência da GPU;
- impacto da memória compartilhada no desempenho.
  
O que foi corrigido
- Algumas explicações estavam muito genéricas;
- foi necessário adaptar a resposta aos resultados reais obtidos nos experimentos do trabalho.

## Exemplo 3

Prompt:
"Explique a diferença entre CPU e GPU em aplicações paralelas."

Resposta obtida:
A IA apresentou uma comparação entre arquiteturas focadas em baixa latência (CPU) e alta taxa de paralelismo (GPU).

O que foi aproveitado
- Explicação conceitual;
- exemplos de aplicações científicas.
  
O que foi revisado
- Reescrita acadêmica do texto;
- adaptação ao contexto do artigo.

## Reflexão dos Integrantes

Bruno A. M. de Abreu Filho:
Usei para complementar parte do relatório, é muito útil pois dá informações muito precisas e relevantes, incrementando muito no conteúdo da pesquisa, o único ponto negativo são as referências inexistentes.

Emily I. S. Hamano:
O uso da IA ajudou na estruturação do artigo, na explicação de conceitos complexos e na organização da apresentação. Porém, devo ressaltar que alguns aspectos de revisão deram um pouco mais de trabalho do que pesquisando do zero, porém infelizmente o prazo nos foi muito curto, foi bom porque nos deu uma base, mas tivemos que corrigir algumas coisas. Um exemplo foi o uso de IA para gerar slides, teve uma boa base, seguiu o nosso artigo, entretanto, aspectos como tamanho de fonte, distribuição de espaço, imagens, gráficos e tabelas deixou a desejar. Portanto, o uso de IA generativa foi de muita ajuda quando se refere a auxilio com alguns deslizes ou outros, mas que facilitaram o nosso trabalho, tendo em vista, o curto prazo.

Pedro Costa Freitas:
O uso da IA contribuiu significativamente para o aprendizado individual durante o desenvolvimento do projeto. A ferramenta auxiliou na compreensão de conceitos de computação paralela, arquitetura CUDA, threads, kernels e shared memory, além de ajudar na implementação e depuração do código. Apesar do apoio fornecido pela IA, foi necessário estudar os conceitos, executar testes, interpretar os resultados e compreender o funcionamento das implementações para conseguir explicar corretamente as decisões tomadas no projeto.
