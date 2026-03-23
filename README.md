# Miniguia de Estudos: Identificação e Exploração de Falhas Web

![Capa do Projeto](https://images.unsplash.com/photo-1526374965328-7f61d4dc18c5?q=80&w=800&auto=format&fit=crop)

## Contexto e Objetivos
O foco deste caderno temático é a análise de vulnerabilidades em aplicações web e a documentação de falhas de segurança, com foco em operações de red team. O objetivo é consolidar o conhecimento sobre exploração de falhas e criar uma base de consulta rápida para elaboração de relatórios técnicos de cibersegurança e para aplicação prática em laboratórios e aplicações web intencionalmente vulneráveis.

## Curadoria de Fontes
1. OWASP Top 10 2021 (Documentação oficial da fundação).
2. OWASP Web Security Testing Guide - WSTG (Guia de testes práticos).
3. Artigos técnicos sobre a aplicação de Open Source Intelligence (OSINT) no reconhecimento de alvos.

## Engenharia de Prompts e Cicatrizes
Pergunta inicial testada: "Quais são as falhas web mais comuns segundo os documentos?"
Resultado: A IA entregou um texto genérico e superficial.
Troubleshooting: O prompt precisou ser muito mais específico para focar na execução técnica e na elaboração de relatórios.
Prompt ajustado: "Com base no OWASP WSTG, descreva o processo prático de teste para Cross-Site Scripting (XSS) e forneça um exemplo de payload que eu poderia incluir em um relatório de vulnerabilidade."
Resultado final: A IA retornou o passo a passo exato da exploração e a estrutura de texto adequada para documentar a falha encontrada.

## Miniguia de Estudo

### Resumos Estruturados
A fase inicial de qualquer teste ofensivo envolve o uso de OSINT para mapear a superfície de ataque e descobrir subdomínios ou painéis expostos. Após o reconhecimento, a exploração de aplicações web frequentemente esbarra em falhas de injeção (como SQLi) e falhas de controle de acesso. A documentação dessas falhas exige clareza sobre o impacto no negócio e a recomendação de correções, como a sanitização de inputs e o uso de queries parametrizadas no código fonte.

### Glossário
SQLi (SQL Injection): Manipulação de consultas em bancos de dados através de inputs não tratados.
XSS (Cross-Site Scripting): Injeção de scripts maliciosos no lado do cliente.
Red Team: Simulação de ataques reais e táticas de adversários para testar a resiliência de uma organização.
OSINT: Coleta e análise de informações de fontes públicas e abertas.
Payload: Fragmento de código utilizado para validar ou executar uma ação maliciosa durante a exploração.
CVE (Common Vulnerabilities and Exposures): Sistema de pontuação e registro de vulnerabilidades públicas.

### Prompts Reutilizáveis
1. "Atuando como um analista de cibersegurança, escreva o sumário executivo de um relatório explicando o impacto da vulnerabilidade [INSERIR VULNERABILIDADE] com base nos PDFs enviados."
2. "Liste os passos de mitigação em nível de código para a falha [INSERIR FALHA], direcionados aos desenvolvedores da aplicação web."
3. "Quais técnicas de OSINT o documento sugere para a fase de enumeração de infraestrutura do alvo?"
