# 🎯 Desafio Criativo: Acelerando Sua Produtividade Pessoal com IA

> Projeto desenvolvido para o desafio de projeto da [DIO](https://www.dio.me/) — *"Desafio Criativo: Acelerando Sua Produtividade Pessoal com IA"*.

## 💡 Sobre o exercício

Um bom prompt nasce de **intenção clara, contexto e instruções específicas**. Neste desafio, o prompt final foi construído em 3 etapas, cada uma adicionando uma nova peça até chegar a um comando completo e pronto para orientar uma IA a produzir exatamente o resultado esperado.

**Tema escolhido:** aplicar o exercício ao meu próprio processo de estudo, conectando com o projeto [miniguia-estudos-notebooklm](https://github.com/cRzIN1804/miniguia-estudos-notebooklm) — usando IA para me ajudar a manter consistência nos estudos sobre Engenharia de Prompts.

---

## 🧱 Passo 1: Defina a intenção

**O que fazer:** descrever o que se quer que a IA faça e para quem.

**Modelo:**
```
Quero que a IA gere [tipo de conteúdo] para [público], com o objetivo de [resultado].
```

**Preenchido:**
```
Quero que a IA gere um plano de revisão semanal para estudantes autodidatas de
Engenharia de Prompts e IA Generativa, com o objetivo de manter consistência nos
estudos até a conclusão do miniguia temático.
```

---

## 🧱 Passo 2: Adicione contexto e restrições

**O que fazer:** detalhar como a resposta deve ser construída (estilo, limite de tamanho, o que evitar).

**Modelo:**
```
Considere o seguinte contexto: [contexto]. O conteúdo deve ter [formato].
Evite [o que evitar].
```

**Preenchido:**
```
Considere o seguinte contexto: tenho cerca de 1 hora por dia disponível, uso o
NotebookLM com 5 fontes abertas já selecionadas sobre o tema, e prefiro estudar
em blocos curtos e objetivos. O conteúdo deve ter formato de tabela com dias da
semana e tarefas específicas. Evite sugestões que exijam mais de 1 hora diária,
materiais pagos ou ferramentas além do NotebookLM.
```

---

## 🧱 Passo 3: Una tudo em um prompt final

**O que fazer:** revisar tudo, conectar as ideias e escrever um único comando.

### ✅ Prompt final

```
Quero que a IA gere um plano de revisão semanal para estudantes autodidatas de
Engenharia de Prompts e IA Generativa, com o objetivo de manter consistência nos
estudos até a conclusão do miniguia temático. Considere o seguinte contexto:
tenho cerca de 1 hora por dia disponível, uso o NotebookLM com 5 fontes abertas
já selecionadas sobre o tema, e prefiro estudar em blocos curtos e objetivos.
O conteúdo deve ter formato de tabela com dias da semana e tarefas específicas.
Evite sugestões que exijam mais de 1 hora diária, materiais pagos ou ferramentas
além do NotebookLM.
```

---

## 🔎 Resultado obtido ao testar o prompt

Ao rodar esse prompt final em uma IA (ex: Claude, ChatGPT ou NotebookLM), o resultado esperado é uma **tabela com 7 linhas (uma por dia da semana)**, cada uma com uma tarefa objetiva de até 1 hora relacionada ao tema (ex: "Segunda-feira → Ler fonte 1 e anotar 3 conceitos novos no glossário"), sem depender de ferramentas pagas — validando que a intenção, o contexto e as restrições definidos nos Passos 1 e 2 realmente moldaram a resposta final.

---

## 📌 Aprendizado principal

A diferença entre um prompt genérico ("me dá um plano de estudos") e este prompt final é que aqui **cada elemento (intenção + contexto + restrições) elimina uma fonte de ambiguidade**, reduzindo a chance da IA "chutar" um formato, tom ou nível de esforço que não sirva para a realidade de quem está pedindo.

---

*Projeto desenvolvido como parte da trilha de Inteligência Artificial da [Digital Innovation One (DIO)](https://www.dio.me/).*
