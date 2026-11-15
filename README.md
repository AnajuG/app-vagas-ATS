# app-vagas-ATS
# ATS Resume Optimizer

# **Prompt final usado já validado pelo Copilot**
```
## Visão Geral

ATS Resume Optimizer é uma aplicação web que ajuda candidatos a adaptar seus currículos para vagas específicas, aumentando a compatibilidade com sistemas ATS (Applicant Tracking System) sem alterar a veracidade das informações.

O usuário fornece a descrição da vaga e seu currículo atual. A plataforma analisa os dois conteúdos, calcula o nível de compatibilidade, identifica palavras-chave relevantes e gera uma versão otimizada do currículo pronta para envio.

O princípio central do produto é a honestidade profissional: a aplicação melhora a apresentação da experiência do candidato, mas nunca cria informações que não existam no currículo original.

---

# Problema

Grande parte das empresas utiliza sistemas ATS para filtrar currículos antes que sejam avaliados por recrutadores.
Profissionais qualificados muitas vezes são descartados porque:

- Não utilizam as palavras-chave esperadas pela vaga;
- Possuem currículos mal estruturados para leitura automatizada;
- Não conseguem adaptar rapidamente o currículo para diferentes oportunidades;
- Não entendem quais competências estão sendo valorizadas na descrição da vaga.

O resultado é a perda de oportunidades devido à forma de apresentação, e não necessariamente pela falta de qualificação.

---

# Objetivo

Permitir que candidatos:

- Avaliem o alinhamento do currículo com uma vaga;
- Identifiquem pontos de melhoria;
- Descubram palavras-chave importantes;
- Recebam uma versão ATS Friendly do currículo;
- Exportem o resultado para uso imediato.

---

# Público-Alvo

- Profissionais em busca de recolocação profissional;
- Pessoas aplicando para múltiplas vagas;
- Profissionais em transição de carreira;
- Candidatos que desejam melhorar o desempenho em processos seletivos.

---

# Proposta de Valor

Transformar um currículo comum em uma versão mais aderente aos critérios de sistemas ATS em poucos minutos, mantendo total fidelidade às informações fornecidas pelo candidato.

---
```
# **Prompt usado no lovable**
```
# ATS Resume Optimizer

## Visão Geral

ATS Resume Optimizer é uma aplicação web que ajuda candidatos a adaptar seus currículos para vagas específicas, aumentando a compatibilidade com sistemas ATS (Applicant Tracking System) sem alterar a veracidade das informações.

O usuário informa a descrição da vaga e seu currículo atual. A plataforma analisa ambos os conteúdos, identifica pontos de aderência, destaca palavras-chave importantes e gera uma versão ATS Friendly do currículo pronta para uso.

O objetivo é aumentar as chances de aprovação em filtros automatizados sem criar ou inventar experiências profissionais.

---

# Problema

Milhares de candidatos possuem experiência compatível com vagas abertas, mas são eliminados por sistemas ATS antes mesmo de serem avaliados por recrutadores.

As principais dificuldades enfrentadas são:

- Falta de conhecimento sobre ATS.
- Dificuldade para identificar palavras-chave relevantes.
- Falta de tempo para adaptar currículos para cada vaga.
- Currículos mal estruturados para leitura automatizada.
- Baixa taxa de retorno nos processos seletivos.

---

# Objetivo

Criar uma aplicação simples e intuitiva que permita:

- Comparar um currículo com uma vaga.
- Calcular um score de compatibilidade.
- Identificar palavras-chave encontradas.
- Identificar palavras-chave ausentes.
- Sugerir melhorias.
- Gerar uma versão ATS Friendly do currículo.
- Exportar o currículo otimizado.

---

# Público-Alvo

## Primário

- Profissionais em busca de recolocação.
- Pessoas aplicando para múltiplas vagas.
- Profissionais em transição de carreira.

## Secundário

- Estudantes.
- Estagiários.
- Recém-formados.
- Profissionais que desejam melhorar o currículo.

---

# Proposta de Valor

Ajudar candidatos a adaptar seus currículos para vagas específicas em poucos minutos, aumentando a aderência aos sistemas ATS de forma rápida, simples e ética.

---

# Regra Fundamental do Produto

A plataforma deve melhorar a forma como o profissional apresenta sua experiência.

A plataforma nunca deve:

- Inventar experiências.
- Inventar empresas.
- Inventar certificações.
- Inventar competências.
- Criar resultados fictícios.
- Adicionar informações não fornecidas pelo usuário.

Mensagem obrigatória na interface:

"Esta ferramenta otimiza a apresentação do seu currículo, mas nunca cria ou inventa experiências, competências ou conquistas que não existam no conteúdo original."

---

# Funcionalidades do MVP

## 1. Comparação entre Currículo e Vaga

O usuário informa:

- Descrição da vaga.
- Currículo atual.

A aplicação realiza uma análise comparativa entre os conteúdos.

---

## 2. Score de Compatibilidade

Exibir um percentual de aderência.

Exemplo:

- Match Geral: 78%
- Nível: Alta Compatibilidade

Faixas:

- 0% a 49% → Baixa
- 50% a 74% → Média
- 75% a 100% → Alta

---

## 3. Palavras-Chave Encontradas

Exibir as palavras ou competências identificadas tanto na vaga quanto no currículo.

Exemplo:

- SQL
- Excel
- Scrum
- Python
- Power BI

---

## 4. Palavras-Chave Ausentes

Exibir palavras presentes na vaga que não foram encontradas no currículo.

Exemplo:

- Azure
- Tableau
- Jira

Observação:

A aplicação deve informar que essas palavras só devem ser adicionadas ao currículo caso façam parte da experiência real do candidato.

---

## 5. Recomendações de Melhoria

Gerar sugestões práticas de otimização.

Exemplos:

- Destacar experiências mais relevantes.
- Melhorar o resumo profissional.
- Evidenciar resultados alcançados.
- Reorganizar competências técnicas.

---

## 6. Currículo ATS Friendly

Gerar uma nova versão do currículo utilizando exclusivamente informações existentes.

Objetivos:

- Melhorar a estrutura.
- Melhorar a legibilidade.
- Melhorar o uso das palavras-chave existentes.
- Tornar o currículo mais objetivo.
- Tornar o currículo mais aderente ao ATS.

---

## 7. Exportação

Permitir:

- Copiar resultado.
- Exportar em PDF.
- Exportar em DOCX.

---

# Fluxo Principal

1. Usuário acessa a aplicação.
2. Cola a descrição da vaga.
3. Cola o currículo atual.
4. Clica em "Analisar".
5. Visualiza score e palavras-chave.
6. Gera versão ATS Friendly.
7. Exporta o currículo otimizado.

---

# Telas do MVP

## Tela 1 - Home

Objetivo:

Apresentar a proposta da ferramenta.

Componentes:

- Título principal.
- Explicação sobre ATS.
- Benefícios da plataforma.
- Botão "Começar".

---

## Tela 2 - Análise

Componentes:

- Campo da vaga.
- Campo do currículo.
- Botão "Analisar Currículo".

---

## Tela 3 - Resultado

Componentes:

- Score de compatibilidade.
- Compatibilidade geral.
- Palavras-chave encontradas.
- Palavras-chave ausentes.
- Recomendações.

---

## Tela 4 - Currículo ATS Friendly

Componentes:

- Currículo otimizado.
- Botão copiar.
- Botão exportar PDF.
- Botão exportar DOCX.

---

# Requisitos Não Funcionais

## Usabilidade

- Interface simples.
- Fluxo intuitivo.
- Poucos cliques.
- Linguagem acessível.

## Performance

- Resposta em até 15 segundos.
- Feedback visual durante processamento.

## Responsividade

- Desktop.
- Tablet.
- Mobile.

## Acessibilidade

Seguir princípios de Design Universal:

- Navegação por teclado.
- Alto contraste.
- Compatibilidade com leitores de tela.
- Estrutura semântica adequada.

---

# Tecnologias Sugeridas

## Frontend

- React
- TypeScript
- Tailwind CSS
- shadcn/ui

## Backend

- Supabase

## Inteligência Artificial

- OpenAI GPT-5
- OpenAI Responses API

## Exportação

- react-pdf
- docx

---

# Métricas de Sucesso

## Produto

- Número de análises realizadas.
- Número de currículos gerados.
- Taxa de exportação.

## Experiência do Usuário

- Tempo para conclusão da análise.
- Satisfação do usuário.
- Taxa de retorno.

---

# Escopo Futuro

## V2

- Upload de PDF.
- Upload de DOCX.
- Histórico de análises.
- Histórico de currículos.
- Carta de apresentação personalizada.

## V3

- Integração com LinkedIn.
- Simulador avançado de ATS.
- Currículo multilíngue.
- Preparação para entrevistas.

---

# Critérios de Aceite

O MVP será considerado pronto quando:

- O usuário conseguir informar uma vaga.
- O usuário conseguir informar um currículo.
- O sistema calcular um score de compatibilidade.
- O sistema identificar palavras-chave encontradas.
- O sistema identificar palavras-chave ausentes.
- O sistema gerar uma versão ATS Friendly.
- O sistema não inventar nenhuma informação.
- O usuário conseguir copiar ou exportar o resultado.

---

# Prompt Principal da IA

Você é um especialista em recrutamento, ATS e otimização de currículos.

Sua função é:

1. Comparar currículo e vaga.
2. Calcular um score estimado de compatibilidade.
3. Identificar palavras-chave presentes.
4. Identificar palavras-chave ausentes.
5. Apresentar recomendações de melhoria.
6. Reescrever o currículo utilizando apenas informações existentes.
7. Não inventar experiências, empresas, certificações ou resultados.
8. Gerar uma versão ATS Friendly.
9. Entregar o resultado em linguagem clara, objetiva e profissional.

---

# Resumo

ATS Resume Optimizer é uma plataforma que analisa a compatibilidade entre currículos e vagas, identifica oportunidades de melhoria e gera uma versão ATS Friendly do currículo, mantendo total fidelidade às informações fornecidas pelo usuário.
```
# **Ajustes**
Os créditos acabaram antes que eu pudesse encerrar, então tive que esperar para continuar, no modo gratuito, o importante é usar um prompt menor, mas a aplicação acaba não saindo tão boa.
Pedi alteração apenas na paleta de cores, o restante apresentou boa funcionalidade.

<img width="1470" height="764" alt="Captura de Tela 2026-11-14 às 22 09 31" src="https://github.com/user-attachments/assets/59ec0a2e-5f52-41ec-9e4e-0fea8b5ce682" />

<img width="1470" height="764" alt="Captura de Tela 2026-11-14 às 22 09 41" src="https://github.com/user-attachments/assets/89e6c9fb-854c-42ea-ae84-8284e2b7ffb5" />

<img width="1470" height="764" alt="Captura de Tela 2026-11-14 às 22 09 53" src="https://github.com/user-attachments/assets/e6813b03-efeb-4688-91af-cb3d42302dfe" />

Depois da troca de cor, ele identificou um erro, corrigi sem gastar créditos

# **Link da Aplicação**

https://cv-match-scout.lovable.app

# **Resumo**
O ATS Resume Optimizer é uma plataforma que ajuda profissionais a adaptar seus currículos para vagas específicas de forma rápida, ética e orientada a resultados. A solução compara automaticamente o currículo com a descrição da vaga, calcula o nível de compatibilidade, identifica palavras-chave presentes e ausentes e gera uma versão ATS Friendly otimizada para sistemas de recrutamento. Seu principal diferencial é garantir total fidelidade às informações do candidato, melhorando a apresentação, estrutura e relevância do currículo sem inventar experiências, competências ou conquistas, oferecendo uma alternativa confiável para aumentar as chances de avançar nos processos seletivos.
