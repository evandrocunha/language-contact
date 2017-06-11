# Plano de Batalha

## Indivíduo

  - Idade: susceptibilidade. Idade aumenta a cada iteração da simulação.
  - Nasce com um vocabulário pequeno, mas enquanto está novo recebe muitos "itens" a cada contato. À medida em que envelhece, passar a ir recebendo cada vez menos itens a cada contato.
  - Cada palavra do vocabulário do indivíduo tem uma frequência, dada pela lei de Zipf.
  - Mutação: dependente e independente de contato linguístico. Mais forte quando há contato.
 

## Comunidade

  - Grafo (barabasi_albert do NetworkX). Testar outros tipos de grafos também.
  - Distribuição de arestas entre indivíduos (vértices do grafo) é aleatória, mas é inversamente proporcional ao tamanho do grafo.
  - Se existe uma aresta entre dois indivíduos no grafo, há contato linguístico entre eles.

## Contato Linguístico

  - Foco da narrativa do artigo: o que acontece quando há contato linguístico?
  - Contato linguístico (na maioria das vezes) adiciona palavras ao vocabulário dos envolvidos. Se a palavra já existir no vocabulário do indivíduo, a frequência dessa palavra é incrementada. Caso contrário, a palavra é adicionada com frequência igual a 1.
  - Distribuição de probabilidade para ver se há troca de palavras ou não?
  - Palavras pouco frequentes desaparecem á medida em que indivíduos morrem.
  
### Resultados do contato linguístico:
    
  1. Empréstimo.
  2. Language shift. Troca de palavras mais frequênte em uma direção.
  3. Stratal influence. Medir quantas palavras da língua dominada passam a fazer parte da língua dominadora.
  4. Criação de novas línguas:
    - Pidgin
    - Creolização
  5. O que propriedades de grafo (Betweeness, etc.) nos dizem no contexto de criação de novas línguas?
  
